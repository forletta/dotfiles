# My Dotfiles
---

## Setup
After authenticating `git` and `gh`:

```sh 
# clone the repo
gh repo clone dotfiles .dotfiles

cd .dotfiles

# initialize submodules
git submodule update --init

# stow dotfiles
stow --adopt .
```
