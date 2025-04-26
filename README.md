# My dotfiles

This directory contains the dotfiles for my system.

## Requirements

Ensure you have the following installed on your system

### Git


### Stow
```
brew install stow
```

## Installation

YouTube reference: [link](https://www.youtube.com/watch?v=y6XCebnB9gs&t=220s)

First, check out the dotfiles repo in your `$HOME` directory using git.

```
git clone https://github.com/anthonygharvey/dotfiles.git
cd dotfiles
```

then use GNU stow to create symlinks

```
stow .`
```
