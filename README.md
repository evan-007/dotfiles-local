# Dotfiles

My dotfiles using [thoughtbot dotfiles](https://github.com/thoughtbot/dotfiles) as
the base.

## Setup

* clone the thoughtbot dotfiles
* clone this repo to `~/dotfiles-local`
* Run `rcup`

Until I automate nvim setup with a hook:

```
mkdir -p ~/.config/nvim
nvim ~/.config/nvim/init.vim

# init.vim
set runtimepath+=~/.vim,~/.vim/after
set packpath+=~/.vim
source ~/.vimrc
```

make sure `excludesfile = /Users/evanlloyd/dotfiles-local/.gitignore` is in
`~/.gitconfig`

setup global gitignore `git config --global core.excludesfile ~/dotfiles-local/.gitignore`
