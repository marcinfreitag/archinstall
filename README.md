# archinstall
Automated deployment of my archlinux setup with dwm

The installation script and dotfiles are managed using [chezmoi](https://www.chezmoi.io/).

## Getting started

Check out the [Quick Start](https://www.chezmoi.io/quick-start/) page.

### Install chezmoi and the dotfiles on any new machine

With a single line of code (public):

```sh
sudo pacman -Sy --noconfirm chezmoi && chezmoi init https://github.com/marcinfreitag/archinstall.git && chezmoi apply
```

### Update

On any machine, you can pull and apply the latest changes from your repo with:

```sh
chezmoi update -v
```

