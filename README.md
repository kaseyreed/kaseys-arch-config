### Abandoned

Moved various bits out of the .config directory and into smaller repos. 
Checkout: https://github.com/kaseyreed/dotfiles

# Pacakges Installed at OS Install
* firefox
* lightdm
* lightdm-gtk-greeter
* neofetch
* yeh
* dunst


# Packages Installed After OS Install

## via makepkg
* yay 

## via pacman
* alacritty
* rofi
* git base-devel
* bashtop s-tui stress
* pywal (TODO: remove this in favor of feh)
* xorg-xrandr (to see monitor / resolutions)
* ttf-font-awesome
* picom (prettyish animations)
* openssh
* zsh zsh-completions
* flameshot (for screenshots)
* ranger (simple console file manager)
* libinput-gestures (for trackpad gestures)
* alsa-utilities

## via yay
* codium slack-desktop spotify
* polybar


# Ricing / Look and Feel
* Using https://github.com/adi1090x/polybar-themes.git
- specifically the material polybar
- 

https://github.com/siduck76/bspwm-dotfiles
* using for picom config

# Zsh + Zinit
* Zsh Installed via pacman
* Zinit installed via:

```zsh
```

# TODO:

- [x] Part 1: Much better sxhkdrc config (think macos inspiried... i hate that fucking win key)
- [x] System Notifications (dunt already installed.)
- [ ] conky
- [x] (removed) Lightdm Config (or maybe I just get rid of this entirely...)
- [ ] Grub Config and theming
- [ ] apply adapta theme to the rest of your apps (that you can...)
- [x] Setup zinit and zsh and terminal
- [ ] Drop down terminal? Might have an easier way to do this with bspwm
- [x] Setup git configuration for personal github
- [ ] Part 2: Even better sxhdrc.
- [x] trackpad setup
 
## General System Cleanup
- [ ] make install artifacts
- [ ] old themes, wallpapers we aren't going to use

## Things to Install
- [ ] IntellJ + Products
- [ ] Docker

## Bugs
* Firefox window opens terribly sometimes
* Every so often light dm fails to start, likley a race condition with the video card driver init.


## Docker

* Install in rootless mode (using sudo all over the place not great - especially when sharing stuff between mac and linux users)
* https://docs.docker.com/engine/security/rootless/
* You'll need to install rootless extras from yay `yay -S docker-rootless-extras`
* You will need to create the /etc/subuid and /etc/subgid files with your username and the right # values. 

### 8/30/2021 

![Kaseys Desktop v0](kaseys-desktop-v0.png)
