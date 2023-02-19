
Place in `~/.config/nvim`

Place this package manager in the shell (.config)
[packer.nvim](https://github.com/wbthomason/packer.nvim)
```sh
cd ~/.config
git clone --depth 1 https://github.com/wbthomason/packer.nvim\
 ~/.local/share/nvim/site/pack/packer/start/packer.nvim
```

---
Find where nvim looks for config files
```vim
:h rtp
```
Noteable:
`$XDG_CONFIG_HOME/nvim/after`


---
# Remap notes
There are a few keybinds in vscode that I really like and use often. I want to continue using these as I transition into using vim or nvim

Ctrl+D
Selects next matching word
> Maybe change this to some keybind in Visual mode

Ctrl+L
Selects Line
> Can already do this with 'V'


Copy lines up or down
