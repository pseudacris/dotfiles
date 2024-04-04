# My d-d-d-dotfiles

This directory contains my dotfiles for my system

## Requiremints

Ensure you have the following installed on your system

### Git

```
pacman -S git
```

### Stow
```
pacman -S stow
```

## Installation

First, download the dotfiles repo in your $HOME directory using git

```
git clone git@github.com:pseudacris/dotfiles.git
cd dotfiles
```

Then use GNU Stow to create symlinks

```
stow .
```

Finally, you can check that a symlink works

```
cd ~
ls -lah [PATH TO FILE]
```

Link to tutorial video:
https://www.youtube.com/watch?v=y6XCebnB9gs


