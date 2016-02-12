# Description

Bullets.vim is a Vim plugin for automated bullet lists.

# Installation

With VimPlug:

```vim
Plug 'dkarter/bullets.vim'
```

Then source your bundle file and run `:PlugInstall`.


# Usage

In markdown or a text file start a bulleted list using `-` or `*`. Press return
to go to the next line, a new list item will be created.


# TODO

- [ ] eliminate trailing bullet on previous line if user pressed <cr> twice
- [x] allow indenting while in insert mode
- [ ] scope the keybindings and functions to markdown and perhaps text
- [ ] allow checkbox auto bullet
- [ ] prefix shortcuts and allow disabling them 
- [ ] add numbered list
- [ ] add alphabetic list
- [ ] allow user to define a global var with custom bullets
- [ ] allow <C-cr> for return without creating a bullet
- [ ] detect lists that have multiline bullets (should have no empty lines between
  lines). (like this list 😆)



