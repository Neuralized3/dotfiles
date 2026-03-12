# Arch Linux Rice

> **Note:** This repo contains configuration files that may reference or depend on third-party packages. I do not own any of them — full credit goes to their respective creators. All listed packages are free and open-source software (FOSS). If any of my personal details are found, please inform me immediately, I'll remove please.


## Install

```bash
sudo pacman -S yay wayland hyprland xorg-xwayland linux-zen

yay -S mpvpaper breeze-cursors cava wlogout plymouth zsh \
  ungoogled-chromium-bin waybar spotify-adblock spicetify kitty sddm \
  nautilus rofi neovim vscodium-bin obsidian pulseaudio pavucontrol \
  blueman wl-clipboard cliphist nwg-look neofetch btop
```

---

## Packages

| Package | Description |
| --- | --- |
| `wayland` | Display protocol |
| `hyprland` | Wayland compositor / window manager |
| `xorg-xwayland` | X11 compatibility layer for Wayland |
| `linux-zen` | Performance-tuned kernel |
| `zsh` | Shell |
| `kitty` | OpenGL terminal emulator |
| `mpvpaper` | Animated wallpaper via mpv |
| `waybar` | Status bar |
| `rofi` | App launcher |
| `wlogout` | Logout / shutdown / reboot / sleep menu |
| `cava` | Terminal audio visualiser |
| `plymouth` | Boot splash screen |
| `sddm` | Login manager |
| `nautilus` | File manager |
| `neovim` | TUI code editor |
| `vscodium-bin` | GUI code editor |
| `obsidian` | Note-taking app |
| `ungoogled-chromium-bin` | Chromium without Google services |
| `spotify-adblock` | Spotify with ads blocked |
| `spicetify` | Spotify theming |
| `pulseaudio` | Audio server |
| `pavucontrol` | GUI audio manager |
| `blueman` | Bluetooth manager |
| `wl-clipboard` + `cliphist` | Wayland clipboard + history |
| `nwg-look` | GTK theme config |
| `neofetch` | System info in terminal |
| `btop` | System monitor |
| `breeze-cursors` | Cursor theme |

---

## Install Separately

| Tool | Description |
| --- | --- |
| Powerlevel10k | Zsh prompt theme |
| GeistMono Nerd Font | Terminal font |
| SF Pro Display | System font for Chromium |
| NextDNS | DNS-level ad and tracker blocking |

---

## GTK Theme

| | |
| --- | --- |
| Theme | WhiteSur-Dark |
| Icons | BlackBig-Sur |

---

## System Tweaks

| Tweak | Purpose |
| --- | --- |
| `zram` | Compressed RAM swap |
| `cpugovernor` | CPU power mode management |

---

## Notes

**Plymouth** — Skip boot timeout in systemd config, use Nord theme from `plymouth-themes`, add `quiet splash` to kernel parameters.

**Spotify** — Install `spotify-adblock` first, then apply theme with `spicetify` using the Text color scheme.
