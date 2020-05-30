# Prerequisites
* WSL or (current) Linux dist
* Vim installation with "+python3" support (check with `vim --version` form terminal) you can `sudo apt-get remove vim` and `sudo apt install vim-gtk`if python3 not supported.
* vundle/bundle manager installed. Instructions [here](https://github.com/VundleVim/Vundle.vim.git). Essentially you need: `git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim`

# Installation

* copy this .vimrc to your home folder (assuming vim default behavior)
* in vim (command mode) run `:PluginInstall`
* from https://github.com/powerline/fonts install powerline patched fonts and change terminal fonts to one of the new fonts (settings, general etc.)
* for ycm installation https://ycm-core.github.io/YouCompleteMe/#installation

## additionally
* goes fine with https://github.com/gpakosz/.tmux
* note that gutentags Plugin requires 'ctags' executable
