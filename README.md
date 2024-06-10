# Package Installation Instructions

instructions for installing a list of packages using the `pacman` package manager on Arch Linux or Arch-based distributions.

## Prerequisites

- Arch Linux or Arch-based distribution (e.g., Manjaro)
- Administrative privileges (`sudo`)

## Installation

### 1. Update package databases

Before installing new packages, it's recommended to update your package databases:

```bash
sudo pacman -Syu && sudo pacman -S brightnessctl fastfetch foot hypridle hyprlock hyprpaper imv lf mpv neovim ttf-jetbrains-mono-nerd waybar
```
### 2. ly window manager

```bash
nvim /etc/ly/config.ini
```
### 3. SwayLock
```
paru -S swaylock-effects
```
