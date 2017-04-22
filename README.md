# my_st-git
> Forked from https://aur.archlinux.org/st-git.git

PKBUILD and Makefile have been modified to append the system users name to the
package name and executable allowing each user to install their own customized package.

This repo also includes my personal st configuration and patchset.

![](screenshot.png)

---

## Installation

Arch Linux:

```sh
makepkg && sudo pacman -U *.xz
```

---

## Usage example
```sh
startx /usr/bin/st_${USER}
```

---
