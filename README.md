# Git commit message inline VIM Plugin

### Installation

Recommended installation with `vundle`:

```vim
  Plugin 'tuanle03/git-message.vim'
```

### Configuration
#### Ignore file-types to display git message
Overwrite the `g:gmi#ignored_filetypes` variable

Example: (it is Default)
```vim
let g:gmi#ignored_filetypes = ['help', 'qf', 'nerdtree', 'fzf']
```
