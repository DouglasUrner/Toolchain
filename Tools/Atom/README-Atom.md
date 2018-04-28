# General Notes on Atom

Notes specific to writing and coding with Atom are in their respective sections.

## Configuration Management

Goals:

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
