# Package Installation Instructions

instructions for installing a list of packages using the `pacman` package manager on Arch Linux or Arch-based distributions.

## Prerequisites

- Arch Linux or Arch-based distribution (e.g., Manjaro)
- Administrative privileges (`sudo`)

## Installation

## 1. Update package databases
Before installing new packages, it's recommended to update your package databases:

```bash
sudo pacman -Syu && sudo pacman -S brightnessctl fastfetch foot hyprpaper imv lf mpv neovim ttf-jetbrains-mono-nerd waybar bleachbit htop
```
## 2. ly Display manager
- A Terminal Window Manager

```bash
nvim /etc/ly/config.ini
```

## 3. Install Aur Helper, e.g., PARU
```bash
git clone https://aur.archlinux.org/paru-git.git &&
cd paru-git &&
makepkg -si
```

## 4. SwayLock
```
paru -S swaylock-effects
```

## 5. Packages that i Dont Use
- like delete vim cause we already install neovim

See Installed Packages
```bash
sudo pacman -Qt
```

Remove Packages With its Dependencies
```bash
sudo pacman -Rncsu vim
```

## 6. Kde Connect
- To connect with Android
```bash
sudo pacman -S kdeconnect dolphin sshfs
```
