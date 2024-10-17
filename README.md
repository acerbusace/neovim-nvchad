# Configuration for NeoVim based on [NvChad](https://github.com/NvChad/NvChad)

More details on NvChad can be found [here](https://nvchad.com/).

## Install

1. Follow the instructions [here](https://nvchad.com/docs/quickstart/install) to install NvChad pre-requisites.

### macOS

2. Clone this repo to "~/.config/nvim/"
```sh
git clone https://github.com/acerbusace/neovim-nvchad ~/.config/nvim && nvim
```

### Windows

2. Clone this repo to "%USERPROFILE%\AppData\Local\nvim\"
```cmd
git clone https://github.com/acerbusace/neovim-nvchad %USERPROFILE%\AppData\Local\nvim\ && nvim
```

## Additional Information

**This repo is a fork of [NvChad/starter](https://github.com/NvChad/starter) repo**

- The main nvchad repo (NvChad/NvChad) is used as a plugin by this repo.
- So you just import its modules , like `require "nvchad.options" , require "nvchad.mappings"`
