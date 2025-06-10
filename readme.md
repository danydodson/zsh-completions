# ZSH Completions

Provides zsh completions for selected OSX commands. This repository's main
purpose is to create quality auto completions, e.g. conditional flag aware
presentation and selection of choices, as well as up-to-date and
feature-complete auto completions.

# Installation

```bash
# clone
git clone git://github.com/danydodson/zsh-completions zsh-completions

# ~.zshrc
source ${DOTFILES}/plugins/zsh-completions/zsh-completions.plugin.zsh
autoload -Uz compinit
compinit -d ~/.zcompdump
```
