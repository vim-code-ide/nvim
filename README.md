# 💤My-Ide

A starter template for [LazyVim](https://github.com/LazyVim/LazyVim).
Refer to the [documentation](https://lazyvim.github.io/installation) to get started.

> 基于前端 React 开发工作者打造的 IDE

## Mac|Linux:

### required

mv ~/.config/nvim{,.bak}

### optional but recommended

mv ~/.local/share/nvim{,.bak}
mv ~/.local/state/nvim{,.bak}
mv ~/.cache/nvim{,.bak}

### Start

- git clone https://github.com/vim-code-ide/nvim ~/.config/nvim
- rm -rf ~/.config/nvim/.git
- nvim

## Windows:

### required

Move-Item $env:LOCALAPPDATA\nvim $env:LOCALAPPDATA\nvim.bak

### optional but recommended

Move-Item $env:LOCALAPPDATA\nvim-data $env:LOCALAPPDATA\nvim-data.bak

### Start

- git clone https://github.com/vim-code-ide/nvim $env:LOCALAPPDATA\nvim
- Remove-Item $env:LOCALAPPDATA\nvim\.git -Recurse -Force
- nvim
