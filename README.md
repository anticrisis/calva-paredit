# Calva Paredit

Structural editing and navigation for Clojure and other LISPs

This is a [Paredit](http://mumble.net/~campbell/emacs/paredit.el) extension for [Visual Studio Code](https://code.visualstudio.com). It is a thin wrapper around [paredit.js](http://robert.kra.hn/projects/paredit-js). You find it inside Code's extansion view and on [the Marketplace](https://marketplace.visualstudio.com/items?itemName=cospaia.paredit-revived).

<p align="center">
<a href="https://marketplace.visualstudio.com/items?itemName=cospaia.paredit-revived"><img width="128px" height="128px" src="https://github.com/PEZ/paredit-for-vscode/raw/master/assets/paredit.png" title="Paredit icon"></img></a>
</p>

Inspired by Atom's [lisp-paredit](https://github.com/jonspalding/lisp-paredit)

## Commands

### Navigation

Default keybinding | Action
------------------ | ------
ctrl+right         | Forward Sexp
ctrl+left          | Backward Sexp
ctrl+down          | Forward Down Sexp
ctrl+up            | Backward Up Sexp
ctrl+alt+right     | Close List

### Selecting

Default keybinding | Action
------------------ | ------
ctrl+w             | Expand Selection
ctrl+shift+w       | Shrink Selection
ctrl+alt+w space   | Select Current Top Level Form

### Editing

Default keybinding | Action
------------------ | ------
ctrl+alt+.         | Slurp Forward
ctrl+alt+<         | Slurp Backward
ctrl+alt+,         | Barf Forward
ctrl+alt+>         | Barf Backward
ctrl+alt+s         | Splice
ctrl+alt+/         | Split Sexp
cmd-delete         | Kill Sexp Forward
cmd-backspace      | Kill Sexp Backward
ctrl+alt+down      | Splice & Kill Forward
ctrl+alt+up        | Splice & Kill Backward
ctrl+alt+(         | Wrap Around ()
ctrl+alt+[         | Wrap Around []
ctrl+alt+{         | Wrap Around {}
ctrl+alt+i         | Indent
---                | Transpose

### Copying/Yanking

Default keybinding | Action
------------------ | ------
ctrl+alt+c ctrl+right         | Copy Forward Sexp
ctrl+alt+c ctrl+left          | Copy Backward Sexp
ctrl+alt+c ctrl+down          | Copy Forward Down Sexp
ctrl+alt+c ctrl+up            | Copy Backward Up Sexp
ctrl+alt+c ctrl+alt+right     | Copy Close List

### Cutting

Default keybinding | Action
------------------ | ------
ctrl+alt+x ctrl+right         | Cut Forward Sexp
ctrl+alt+x ctrl+left          | Cut Backward Sexp
ctrl+alt+x ctrl+down          | Cut Forward Down Sexp
ctrl+alt+x ctrl+up            | Cut Backward Up Sexp
ctrl+alt+x ctrl+alt+right     | Cut Close List


## Why are there two Paredit extensions?

The old Paredit extension, made by [clptn](https://github.com/clptn/code-paredit) seemed abandonded and I couldn't reach him. This extension takes off extactly where clptn left, which was a beautiful and clean extension, almost feature complete, and with just a few bugs. I intend to fix whatever bugs I and others find and have started to add the features I and others miss. I also intend to keep maintaining this extenson and if I find myself not able to do so I will try find another maintaner.

## Maintained by Better Than Tomorrow

* Peter Strömberg
* Pedro Girardi
* You?


I also published and maintain [Calva](https://marketplace.visualstudio.com/items?itemName=cospaia.clojure4vscode), another Visual Studio Code extension. Calva is aimed at making it super easy to get Clojure and Clojurescript coding done. It sports interactive REPLs, inline evaluation and other stuff people from the Emacs Cider world are used to.

## Happy Coding

PRs welcome, file an issue or chat @pez up in the [`#editors` channel](https://clojurians.slack.com/messages/editors/) of the Clojurians Slack. Tweeting [@pappapez](https://twitter.com/pappapez) works too.

[![#editors in Clojurians Slack](https://img.shields.io/badge/clojurians-editors-blue.svg?logo=slack)](https://clojurians.slack.com/messages/editors/)

❤️
