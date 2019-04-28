# Git

## Collaboration

## Branching Strategies

* [A successful Git branching model](https://nvie.com/posts/a-successful-git-branching-model/)
  - Similar take from the Git book: [3.4 Git Branching - Branching Workflows](https://git-scm.com/book/en/v2/Git-Branching-Branching-Workflows).

**Take aways:**
* Use ```-no-ff``` when merging into canonical branches to ensure an accurate history history and the ability to easily back out problematic merges.

## How Tos:

### Struturing Tutorials

* [Using Git Tags To Version Coding Tutorials](https://medium.com/@emmawedekind/using-git-tags-to-version-coding-tutorials-cf9ff28fad4f)

## Useful Add-on Bits

* Bash Command Completion Hooks
* Bash Prompts
  - [bash-git-prompt][]
* Bash Scripts
  - [How to clone all repos at once from GitHub?][so-1] - The solutions with `jq` and that take into account both users and organizations are nice.
  - [gitall][] - node module to manage multiple repos at once. Uses a config file for repeated ops.
* [GitTools](https://github.com/GitTools)

[bash-git-prompt]: <https://github.com/magicmonty/bash-git-prompt>
[so-1]: <https://stackoverflow.com/questions/19576742/how-to-clone-all-repos-at-once-from-github/>
[gitall]: <https://www.npmjs.com/package/gitall>
