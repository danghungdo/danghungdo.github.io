---
title: My Vim Cheatsheet 
categories: [Notes]
tags: [vim]
date: 2024-05-08
excerpt: "My Vim Cheatsheet"
---

Vim Cheat Sheet
===============

Modes
------
- **Normal Mode**: Default mode for navigation and executing commands.
- **Insert Mode**: Used for inserting text into the document.
- **Visual Mode**: Used for selecting and manipulating text.

Basic Movement
---------------
- `h`: Move cursor left.
- `j`: Move cursor down.
- `k`: Move cursor up.
- `l`: Move cursor right.
- `w`: Move cursor to the beginning of the next word.
- `b`: Move cursor to the beginning of the previous word.
- `^`: Move cursor to the first non-blank character of the line.
- `$`: Move cursorto the end of the line.
- `G`: Move cursor to the end of the file.
- `gg`: Move cursor to the beginning of the file.
- `{number}G`: Move cursor to the specified line number.
- `Ctrl + u`: Move cursor half a page up.
- `Ctrl + d`: Move cursor half a page down.

Editing
--------
- `i`: Enter Insert mode before the cursor.
- `I`: Enter Insert mode at the beginning of the line.
- `a`: Enter Insert mode after the cursor.
- `A`: Enter Insert mode at the end of the line.
- `o`: Open a new line below the current line and enter Insert mode.
- `O`: Open a new line above the current line and enter Insert mode.
- `x`: Delete character under the cursor.
- `dw`: Delete word under the cursor.
- `dd`: Delete the current line.
- `yy`: Yank (copy) the current line.
- `"+y`: Copy to clipboard
- `p`: Paste yanked or deleted text after the cursor.
- `P`: Paste yanked or deleted text before the cursor.
- `"+p`: Paste from clipboard
- `u`: Undo the last change.
- `Ctrl + r`: Redo the last undone change.

Searching and Substitution
---------------------------
- `/pattern`: Search forward for a pattern.
- `?pattern`: Search backward for a pattern.
- `n`: Jump to the next occurrence of the search pattern.
- `N`: Jump to the previous occurrence of the search pattern.
- `:s/old/new`: Substitute the first occurrence of "old" with "new" on the current line.
- `:s/old/new/g`: Substitute all occurrences of "old" with "new" on the current line.
- `:%s/old/new/g`: Substitute all occurrences of "old" with "new" in the entire file.
- `:%s/old/new/gc`: Substitute all occurrences of "old" with "new" in the entire file with confirmation.

Saving and Quitting
---------------------
- `:w`: Save changes to the file.
- `:q`: Quit Vim.
- `:q!`: Quit Vim without saving changes.
- `:wq` or `ZZ`: Save changes and quit Vim.
