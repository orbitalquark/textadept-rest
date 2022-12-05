# reST

The reST module for Textadept.
It provides utilities for editing reST and Sphinx documents.

**WARNING:** this module is deprecated. It may not work in Textadept 12.0.

## Key Bindings

+ `Ctrl+Alt+J` (`^⌘J` | `M-S-J`)
  Jump to the selected section.
+ `Shift+Enter` (`⇧↩` | `S-Enter`)
  Open the image specified by the directive on the current line.


## Fields defined by `_M.rest`

<a id="_M.rest.DOCUTILS_PATH"></a>
### `_M.rest.DOCUTILS_PATH` (string)

The absolute path to the directory that contains the Python [Docutils][] library if it is
  not in the environment's `PYTHONPATH`.
  The default value is `nil`, which indicates Docutils is installed.

  [Docutils]: http://docutils.sourceforge.net/


## Functions defined by `_M.rest`

<a id="_M.rest.goto_section"></a>
### `_M.rest.goto_section`()

Prompts the user to select a section title to jump to.
Requires the entire document to be styled.

<a id="_M.rest.open_image"></a>
### `_M.rest.open_image`()

Opens the image specified in an "image" or "figure" directive on the current line.


---
