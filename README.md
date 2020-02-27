# tmux config
Personal tmux config

## Pre reqs
* `git clone https://github.com/jimeh/tmux-themepack.git ~/.tmux-themepack`
* `apt-get install xclip` (linux)

## Installation
* `cd ~`
* `git clone https://github.com/windler/tmuxcfg`
* `ln -s -f ./tmuxcfg/.tmux.conf`

## Running tmux
* `export LC_ALL=en_US.UTF-8`
* `tmux`
* Load plugins: `<prefix>-I`

## Bindings
* `a`: secondary prefix
* `<prefix>-e`: edit config
* `<prefix>-r`: reload config
* `<prefix>-I`: load plugins
* `Shift-Arrows`: navigate windows
* `Alt-Arrows`: navigate panes
* `<prefix>-Enter`: edit mode
* `<prefix>-p`: paste
* `<prefix>-P`: choose from paste buffer
* `<prefix>-H/J/K/L`: resize panes
* `<prefix>-m`: toggle mouse on
* `<prefix>-M`: toggle mouse off
