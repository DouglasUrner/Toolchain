# General Notes on [Atom][]

[Atom Flight Manual][afm] - user's and hacker's manual for Atom.

Notes specific to [writing][atom-writing] and [coding][] with Atom are in their respective sections of this repository.

[Atom Tricks for Ruby Developers](https://www.rubyguides.com/2017/11/atom-tricks-for-ruby-developers/)

[atom]: <atom.io>
[afm]: <https://flight-manual.atom.io>
[coding]: <https://github.com/DouglasUrner/Toolchain/tree/master/Coding>
[atom-writing]: <https://github.com/DouglasUrner/Toolchain/blob/master/Writing/README-Atom-Markdown-Tools.md>

## Developing Atom Packages

* [Flight Manual: Hacking Atom](https://flight-manual.atom.io/hacking-atom/)
* [Create Your First Atom Package](https://blog.eleven-labs.com/en/create-atom-package/)
* [How to Write Atom Packages Using Vanilla JavaScript](https://www.sitepoint.com/write-atom-packages-using-vanilla-javascript/)

## Configuration Management

**Goals:**

* Relatively easy to track and backout configuation changes.
  * Keeping the configuation under git in sync with the "live" configuation.
  * Track why packages were installed (avoid, debug package entanglement).
* Quick and easy to setup a configuation on a new machine – ideally in an OS agnostic way.
* Minimizing the size of the configuation.

The current strategy is to put the configuation files in dot-Atom which is within the Git repo, and make ~/.atom a symlink to dot-Atom (the othe way doesn't work). This means that the packages folder is also tracked in Git – not sure if this is a good thing or a bad thing…

### Stratigies

* Put .atom under revision control
* Atom packages
* External build management tool
* Atom's Portable Mode

## Themes

**Goals:**

* Select the syntax theme based on the file type being edited ([multi-theme-applicator][]).
* A writing syntax theme that is pleasent to look at and that converts to a PDF with good fidelity to the preview.
* A coding syntax theme that takes works well with syntax highlighting, and
* Possibly a presentation theme.

### Install

1. [multi-theme-applicator][]
2. Themes:
   - pen-paper-coffee-syntax
3.

[multi-theme-applicator]: <https://atom.io/packages/multi-theme-applicator>

## Fonts
