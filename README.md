javascriptLint
==============

A fork with tiny little changes to the real http://www.javascriptlint.com project

Changes (thus far):
-------------------
* Raising slightly different error for unreferenced function argument named `_`, `__`, etc.
* Allowing 'ignoring' of unreferenced_ignore_argument
* Hacked the build.py so it doesn't require svn... but VERSION needs manual updating.

Mostly, I use this with my fork of the vim plugin: https://github.com/joshmarshall/javascriptLint.vim
