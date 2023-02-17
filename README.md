

Place in `~/.config/nvim`

Old Settings:
`init.vim`
```vim
:set number
:set relativenumber
:set clipboard+=unnamedplus
:set autoindent
:set tabstop=2
:set shiftwidth=4
:set smarttab
:set softtabstop=4
:set mouse=a
```

Find where nvim looks for config files
```vim
:h rtp
```
Noteable:
`$XDG_CONFIG_HOME/nvim/after`