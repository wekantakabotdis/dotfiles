# My dotfiles

This directory contains the dotfiles for my system

## Requirements

Ensure you have the following installed on your system

### Git

```
sudo apt install git
```

### Stow

```
sudo apt install stow
```

## Installation

First, check out the dotfiles repo in your $HOME directory using git

```
cd ~
git clone --recurse-submodules https://github.com/wekantakabotdis/dotfiles.git
cd dotfiles
```

then use GNU stow to create symlinks

```
stow .
```
