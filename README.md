# Dotfiles

## Installation
Place this alias in .zshrc.
```bash
alias config='/usr/bin/git --git-dir=$HOME/.cfg/ --work-tree=$HOME'
```

Then clone and checkout the repo.
```bash
git clone --recurse-submodules --bare git@github.com:josh-abad/dotfiles.git $HOME/.cfg
config checkout
```

If any of the files exist already, remove or rename them before checking out.

Taken from [this guide](https://www.atlassian.com/git/tutorials/dotfiles).
