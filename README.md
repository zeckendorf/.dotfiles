# jenrzzz’s dotfiles
adapted from [mathiasbynens](https://github.com/mathiasbynens/dotfiles)

## Installation
### Using Git and the bootstrap script

Clone this repo to ~/.dotfiles, then run bootstrap.sh to symlink everything to that directory.

### Sensible OS X defaults

When setting up a new Mac, you may want to set some sensible OS X defaults:

```bash
./.osx
```

### Install Homebrew formulae

When setting up a new Mac, you may want to install some common Homebrew formulae (after installing Homebrew, of course):

```bash
./.brew
```

### Caveats
- ```.tmux.conf``` expects [reattach-to-user-namespace](https://github.com/ChrisJohnsen/tmux-MacOSX-pasteboard) to be on your PATH.
- Run ```:BundleInstall``` to install bundles in vim
- [Install powerline](https://powerline.readthedocs.org/en/latest/installation/osx.html#installation-osx)
- Reinstall vim with clipboard support with ```brew install vim --enable-clipboard```
