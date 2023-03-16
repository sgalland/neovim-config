# neovim-config
My Neovim configuration

## Installation
1. On Windows/Mac grab the latest version of Neovim from https://neovim.io/. On Linux check in your package manager.
2. Install vim-plug. See https://github.com/junegunn/vim-plug for installation instructions based on platform.
3. Install a NERD Font from https://github.com/ryanoasis/nerd-fonts. I personally like Fira Code -> https://github.com/ryanoasis/nerd-fonts/releases/download/v2.3.3/FiraCode.zip. Install the font of your choice from the zip file, these are fonts modified for the NERD plugins. On Windows I installed "Fira Code Regular Nerd Font Complete Windows Compatible.ttf" from the zip file. In the configuration file I set the font in init.vim to 'set guifont=FiraCode\ NFM:h11'. If you use a different platform/font you will need to adjust the guifont.
4. See below for the proper configuration directory for Neovim based on your operating sytem. If the directory doesn't exist, create it and place init.vim inside the directory.
5. Run :PlugInstall once Neovim is open.

### Windows
Use the "C:\Users\<username>\AppData\Local\nvim" directory.

### Linux
Use the  "~/.config/nvim" directory.
