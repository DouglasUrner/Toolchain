# HTML5 Presertation Systems

**Goals:**

* Manage presentations on GitHub.
* Present source using live files (extract on the fly from GitHub?) with syntax highlighting.
* Embed media (e.g., link to a TED talk and play it without a lot of fiddling around).
* Link into Canvas (or another LMS).
* Presenter view with speaker Notes
* Run commands from the presentation.
* Authoring support – ability to write slides in Markdown and, at least, a decent preview mode.
* Generate PDF versions of the slides.

## [Reveal.js][revealjs]

[revealjs]: <revealjs.com>

### Components

#### Core Installation

* [Node.js][]
* [grunt][]
* [Reveal.js][revealjs-github]

[node.js]: <>
[grunt]: <>
[revealjs-github]: <https://github.com/hakimel/reveal.js/>

#### Add-ons

Markdown doesn't have native support for including a file in a Markdown document. There are a number of preprocessors available:

* [MarkdownPP][md-pp]

* [reveal-ck][] - command line tools for generating Reveal.js slides.
  * [Source code][reveal-ck-src]
  * [Documentation][reveal-ck-docs]
* [present][] - command line tools for bootstrapping and managing a Reveal.js presentation.
* [decktape][] - extracts PDF version of a number of different HTML presentation formats from the server.

[md-pp]: <https://github.com/jreese/markdown-pp>

[reveal-ck]: <http://jedcn.github.io/reveal-ck/>
[reveal-ck-src]: <https://github.com/jedcn/reveal-ck>
[reveal-ck-docs]: <https://relishapp.com/jedcn/reveal-ck/docs>
[present]: <https://github.com/zharley/present>
[decktape]: <https://github.com/astefanutti/decktape>

#### Atom Packages

* [revealjs-preview][]
* [revealjs-md][]

[revealjs-preview]: <https://atom.io/packages/revealjs-preview>
[revealjs-md]: <http://webpro.github.io/reveal-md/>

#### Related tools

* [On-line editor at Slides.com][slides.com] – free for public decks, ala GitHub.

[slides.com]: <https://slides.com>

### Installation and Setup

In order to have presenter notes a "full installation" of Reveal.js is required.

#### Reveal full installation

In [Presentation tools for programmers: Reveal.js][zharley-reveal], [zharley][] walks through a good looking Reveal.js setup (from late 2015) with a relatively simple install process:

* `brew install node`
* `npm install -g grunt-cli`
* `git clone https://github.com/hakimel/reveal.js.git`

Then `cd reveal.js` and:

* `npm install`
* `grunt serve`

This tests that Node and Reveal.js are alive and well – if all is right with the world Node should come up and you'll land in a browser looking at a very minimal Reveal presentation.

#### Cloning zharley's setup

* `git clone https://github.com/douglasurner/present.git` (my fork)
* `cd present`
* `npm install`
* `npm install -g decktape`

To test:

#### Atom packages and other useful tools


* Atom packages
* [reveal-ck][]
  `gem install reveal-ck`

[zharley]: <https://github.com/zharley>
[zharley-reveal]: <http://zenonharley.com/html5/css3/2015/12/07/presentation-tools-for-programmers-reveal-js.html>
[reveal-ck]: <https://jedcn.github.io/reveal-ck/>

## How To

### Embed Media

#### Video

A YouTube embed link (iframe) can be pasted into a slide. The following template works well on an otherwise blank slide at 16x9:

```html
<iframe width="1200" height="675"
  src="https://www.youtube.com/embed/VIDEO_ID?rel=0&showinfo=0&modestbranding=1&iv_load_policy=3&nologo=1"
  frameborder="0" allow="encrypted-media" allowfullscreen>
</iframe>
```
[YouTube Embedded Players and Player Parameters]( https://developers.google.com/youtube/player_parameters)

[Using YouTube Modest Branding on Your Website]( http://www.adeliestudios.com/youtube-modest-branding-website/)

[How To Make YouTube Videos Look Great]( http://workshed.com/2014/07/02/make-youtube-videos-look-great/)

#### Audio

To play with a slide or set of slides.

### Presenter Notes

### Include Code

### Export As PDF
