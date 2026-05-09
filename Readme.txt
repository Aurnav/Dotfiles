# Arch Linux + Hyprland Rice 🌲

A clean, high-performance "Glass" aesthetic rice optimized for Arch Linux on an RTX 3060 with a 164Hz display.

## Key Features
- **GPU Optimized**: Environment variables configured for NVIDIA RTX 3060 Laptop/Mobile.
- **High Refresh Rate**: Configured for 1920x1200 @ 164Hz.
- **Snappy Animations**: Custom "wind" beziers with a speed of 4 for near-instant response.
- **Glass HUD**: Real-time hardware monitoring via Conky.
- **Smart Gaps**: Automatically removes gaps/borders when only one window is open.

## Hardware Specifications
- **Display**: 1920x1200 @ 164Hz
- **GPU**: NVIDIA GeForce RTX 3060 Mobile
- **OS**: Arch Linux (KDE + Hyprland)

## Essential Dependencies
- `hyprland-nvidia-git` (or standard `hyprland`)
- `kitty` (Terminal)
- `waybar` (Status bar)
- `wofi` (Launcher)
- `nwg-dock-hyprland` (Dock)
- `conky` (System Monitor)
- `swww` or `hyprpaper` (Wallpaper)
- `JetBrainsMono Nerd Font`

## Installation
1. Copy the contents of `hyprland.conf` to `~/.config/hypr/`.
2. Copy `fastfetch/config.jsonc` to `~/.config/fastfetch/`.
3. Copy `conky.conf` to `~/.config/conky/`.
