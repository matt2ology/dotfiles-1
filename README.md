Dotfiles
========

After cloning this repo, run `install` to automatically set up the
development environment. Note that the install script is idempotent - running
it multiple times has no effect.

Dotfiles uses [Dotbot][dotbot] for installation.

##### Note: You should edit `~/.gitconfig` to include your name and email.

Programs Used
-------------

### Command Line Tools

* `brew` (for Mac)
* `aptitude` (for Linux)
* `zsh`
* `tmux`
* `vim`
* `ctags` (exuberant)
* `git`
* `autojump`
* `axel`
* `rtorrent`

### Development Software

* `g++` / `build-essential` package
* `python3`
* `sbt`
* `virtualenv`
* `rbenv`

#### Ruby Gems

* `bundler`
* `rails`

Installing Binaries
-------------------

Use `aptitude` or whatever package manager on Linux. Use `brew` on Mac.

To replace coreutils with GNU coreutils on a Mac, do `brew install coreutils`
and follow the instructions to use the commands with their normal names.

Making Local Customizations
---------------------------

You can make local customizations for some programs by editing these files:

* `vim` : `~/.vimrc_local`
* `zsh` : `~/.zshrc_local_before` run before `.zshrc`
* `zsh` : `~/.zshrc_local_after` run after `.zshrc`
* `git` : `~/.gitconfig_local`
* `tmux` : `~/.tmux_local.conf`

License
-------

Copyright (c) 2014 Anish Athalye. Released under the MIT License. See
`LICENSE.md` for details.

[dotbot]: https://github.com/anishathalye/dotbot
