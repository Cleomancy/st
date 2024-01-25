# Luke Smith's ST

![ST logo](st.svg)

## Rice:
I use DWM with slstatus, st is my terminal and dmenu is my god.
Somehow [Luke Smith's current repo](https://github.com/LukeSmithxyz/st/) for st displays weirdly on my pc when I zoom.
So I use an older build of his I found on my PC from 2019. I fixed 1 shortcut, that's it. The rest just works.

## Prerequisites:
I use arch btw,
```
pacman -Sy base-devel xorg-server xorg-xinit libxinerama libxft feh unclutter ttf-font-awesome ttf-hack
```
You can already guess my dotfiles.

## Install:
```
cd st/
sudo make clean install
```

## Credits:

- [st](https://st.suckless.org/) obviously
- and [Luke Smith](https://lukesmith.xyz/donate/) himself for doing 99% of the work
