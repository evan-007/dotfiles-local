# Dotfiles

My dotfiles use [thoughtbot dotfiles](https://github.com/thoughtbot/dotfiles) as
the base.

## Setup

* install the thoughtbot dotfiles
* clone this repo to ~/.dotfiles
* check that `~/.vimrc` loads `.dotfiles`:
```
if filereadable(expand("~/.dotfiles/vimrc.bundles"))
  source ~/dotfiles/.vimrc.bundles
endif
```
