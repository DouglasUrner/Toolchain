# Writing in Atom using Markdown

A couple of posts on setting up Atom as a writer's editor using Markdown:

* [Atom Flight Manual: Wiriting in Atom][0]
* [Turn Atom into the Best Markdown Editor for Mac][1]
* [Use Atom as your Markdown editor][2]
* [Atom is the best Markdown editor for me][3]
* [How to Set Up & Use Atom as a Markdown Editor][4] - 2017
* [How to Write Faster, Better & Longer: The Ultimate Guide to Markdown][5]

[0]: <https://flight-manual.atom.io/using-atom/sections/writing-in-atom/>
[1]: <https://www.news47ell.com/how-to/atom-best-markdown-editor-mac>
[2]: <https://discountry.github.io/2017/02/15/use-atom-as-your-markdown-editor>
[3]: <https://medium.com/@takezoe/atom-is-the-best-markdown-editor-for-me-76eec18d8185>
[4]: <https://www.portent.com/blog/copywriting/content-strategy/atom-markdown.htm>
[5]: <https://blog.ghost.org/markdown/>

## Packages

Default configuration (as of Atom 1.36.0):

* [language-gfm][] - disabled automatically by [language-markdown][] which includes support for GFM.
* [markdown-preview][]
  - There is a PR (#516) to automatically open and close preview panes - I don't think it is exactly what I want (maintain one preview pane that shows the currently focused Markdown document), but it sounds close. Install patch and test.

These are the core Markdown support packages:

* [language-markdown][] -
* [markdown-writer][]
  - [toolbar-markdown-writer][]
* [markdown-folding][]
* [markdown-preview][] - core package.

The packages below fill some useful niches:

* [markdown-scroll-sync][] - makes the preview track your positon in the edit window.
* [markdown-pdf][]
* [document-outline][]

Table support:

* [atom-csv-markdown][]
* [markdown-table-editor][]
* [table-editor][]
* [tablr][]
* [markdown-table-calc][]

[atom-csv-markdown]: <https://atom.io/packages/atom-csv-markdown>
[document-outline]: <https://atom.io/packages/document-outline>
[language-gfm]: <https://atom.io/packages/language-gfm>
[language-markdown]: <https://atom.io/packages/language-markdown>
[markdown-folding]: <https://atom.io/packages/markdown-folding>
[markdown-pdf]: <https://atom.io/packages/markdown-pdf>
[markdown-preview]: <https://atom.io/packages/markdown-preview>
[markdown-scroll-sync]: <https://atom.io/packages/markdown-scroll-sync>
[markdown-table-calc]: <https://atom.io/packages/markdown-table-calc>
[markdown-table-editor]: <https://atom.io/packages/markdown-table-editor>
[markdown-writer]: <https://atom.io/packages/markdown-writer>
[table-editor]: <https://atom.io/packages/table-editor>
[tablr]: <https://atom.io/packages/tablr>
[toolbar-markdown-writer]: <>
