# Dotfiles install (https://github.com/binnewbs/arch-hyprland.git)

## Required Programs:

    - hyprland 
    - wayland 
    - xorg-xwayland 
    - mesa libinput 
    - libdrm 
    - libxkbcommon 
    - wayland-protocols 
    - zsh 
    - git 
    - swww 
    - waybar 
    - rofi 
    - networkmanager


## Delete old config

    rm -rf ~/.config


## Activate new config

    sudo cp -r ~/arch-hyprland/.config ~/
    sudo cp -r ~/arch-hyprland/wallpapers ./
    sudo cp ~/arch-hyprland/.zshrc ./


## Reboot

    sudo reboot

## Fix Bugs and Configure

- Comment out Line 7 in `~/.config/hypr/configs/Useranimations.conf`: `bezier = been2, 0,.94,.5,.99`
- Edit `~/.config/hypr/configs/input.conf`
    - Set KB-Layout to CH
    - Uncomment whole section `gestures {}`
- Edit `hyprland.conf`
    - Set monitor settings to: `monitor=,preferred,auto,1.3333334`


