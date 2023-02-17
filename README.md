
Place in `~/.config/nvim`

Place this package manager in the shell (.config)
[packer.nvim](https://github.com/wbthomason/packer.nvim)
```sh
cd ~/.config
git clone --depth 1 https://github.com/wbthomason/packer.nvim\
 ~/.local/share/nvim/site/pack/packer/start/packer.nvim
```

---

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