# saint14@toaster dotfiles

> *UNAUTHORIZED ACCESS WILL BE ELIMINATED X_x*

## Stack
| Component | Tool |
|-----------|------|
| OS | Kali Linux Rolling |
| Desktop | KDE Plasma (Wayland) |
| Bar | Waybar |
| Terminal | Kitty + Tmux |
| Shell | ZSH + Oh My Zsh + Powerlevel10k |
| Launcher | Rofi |
| Widgets | EWW + Conky |
| Font | JetBrains Mono Nerd Font |
| Icons | Papirus Dark |
| Cursor | Bibata Modern Ice |
| Visualizer | Cavalier (Flatpak) |
| VPN | ProtonVPN (OpenVPN) |

## Features
- [ 4R53N4L ] Custom EWW launcher panel with zoom effect
- Network Monitor with live device scanner and scrolling marquee
- VPN Widget with ProtonVPN status and connect/disconnect buttons
- Weather Widget via OpenWeatherMap
- Now Playing Spotify integration
- Sysbar with firewall, connections, SSH fails, volume, BT
- Cavalier audio visualizer
- Custom R E D A C T E D SDDM login screen
- KDE Lockscreen with glitch clock effect
- Conky HUD with redacted glitch effect

## Dependencies
sudo apt install -y eww conky waybar kitty tmux zsh rofi blueman nm-connection-editor ufw playerctl pavucontrol arp-scan

## Flatpak
flatpak install flathub org.nickvision.cavalier

## Installation
1. Clone: git clone https://github.com/saint14/dotfiles ~/dotfiles
2. Copy EWW: cp ~/dotfiles/eww.* ~/.config/eww/
3. Copy Waybar: cp ~/dotfiles/config.jsonc ~/dotfiles/style.css ~/.config/waybar/
4. Copy Kitty: cp ~/dotfiles/kitty.conf ~/.config/kitty/
5. Copy Conky: cp ~/dotfiles/conky.conf ~/
6. Launch: eww daemon && eww open launcher

## Notes
- Update your device IP in wifi scanner scripts
- VPN requires ProtonVPN OpenVPN config files
- Cavalier position needs manual adjustment (Wayland limitation)
