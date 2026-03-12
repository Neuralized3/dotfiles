# Arch Linux Rice Setup

  

## Installation

  

```bash

sudo pacman -S yay

  

yay -S mpvpaper breeze-cursors cava wlogout plymouth linux-zen zsh \

ungoogled-chromium-bin waybar spotify-adblock spicetify kitty sddm \

nautilus rofi neovim vscodium-bin obsidian pulseaudio pavucontrol \

blueman wl-clipboard cliphist nwg-look neofetch wayland hyprland \

xorg-xwayland btop

```

  

## Packages

  

| Package | Description |

|---|---|

| `wayland` | Display protocol |

| `hyprland` | Wayland compositor / window manager |

| `xorg-xwayland` | X11 compatibility layer for Wayland |

| `linux-zen` | Performance-tuned kernel |

| `zsh` | Shell |

| `kitty` | OpenGL terminal emulator — themed with Powerlevel10k |

| `mpvpaper` | Animated wallpaper engine via mpv |

| `waybar` | Status bar / dock |

| `rofi` | App launcher |

| `wlogout` | Logout / shutdown / reboot / sleep menu |

| `cava` | Terminal audio visualiser |

| `plymouth` | Boot splash screen |

| `sddm` | GUI login manager |

| `nautilus` | GUI file manager |

| `neovim` | TUI code editor |

| `vscodium-bin` | GUI code editor |

| `obsidian` | Note-taking app with visual graphs |

| `ungoogled-chromium-bin` | Pre-compiled Chromium without Google services |

| `spotify-adblock` | Spotify with ads blocked |

| `spicetify` | Spotify terminal aesthetic theming |

| `pulseaudio` | Audio server |

| `pavucontrol` | GUI audio manager |

| `blueman` | Bluetooth manager |

| `wl-clipboard` + `cliphist` | Wayland clipboard + clipboard history |

| `nwg-look` | GTK theme configuration GUI |

| `neofetch` | Displays terminal colours and system info |

| `btop` | System monitor |

| `breeze-cursors` | Cursor theme |

  

---

  

## Install Separately

  

| Tool | Description |

|---|---|

| Powerlevel10k | Zsh prompt theme — makes kitty look great |

| GeistMono Nerd Font | Font for kitty terminal |

| SF Pro Display + SF Pro Display Monospace | System font for Chromium |

| NextDNS | DNS-level ad and tracker blocking |

  

---

  

## GTK Theme

  

| | |

|---|---|

| **Theme** | WhiteSur-Dark |

| **Icons** | BlackBig-Sur |

  

---

  

## System Tweaks

  

| Tweak | Purpose |

|---|---|

| `zram` | Compressed RAM swap for efficient memory usage |

| `cpugovernor` | CPU power mode management |

  

---

  

## Notes

  

**Plymouth** — Skip boot timeout in systemmd config, use Nord theme from `plymouth-themes`, add `quiet splash` to kernel parameters.

**Spotify** — Install `spotify-adblock` first, then theme using `spicetify` with the Text color scheme.sddm
