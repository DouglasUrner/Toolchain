# HTML5 Presertation Systems

## [Reveal.js][revealjs]

[revealjs.com][revealjs] the [source][revealjs-github] is on GitHub.

[revealjs-preview][]

[revealjs-md]

[reveal-ck][] - command line tools for generating Reveal.js slides.

online editor https://slides.com free public decks, ala GitHub.

[revealjs]: <revealjs.com>
[revealjs-github]: <https://github.com/hakimel/reveal.js/>
[revealjs-preview]: <https://atom.io/packages/revealjs-preview>
[revealjs-md]: <http://webpro.github.io/reveal-md/>
[reveal-ck]: <>

### Installation and Setup

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

To test:

#### Atom packages and other useful tools


* Atom packages
* reveal-ck
  `gem install reveal-ck`

[zharley]: <https://github.com/zharley>
[zharley-reveal]: <http://zenonharley.com/html5/css3/2015/12/07/presentation-tools-for-programmers-reveal-js.html>
