# dwl - dwm for wayland
my personal fork of [`dwl`](https://codeberg.org/dwl/dwl)

## dependencies 
- libinput
- wayland
- wlroots (compiled with the libinput backend & X11 support)
- xkbcommon
- wayland-protocols (compile-time only)
- pkg-config (compile-time only)
- libxcb
- libxcb-wm (normally comes with libxcb)
- Xwayland (runtime only)

## installation
to install `dwl` paste the following snippet into a terminal
```sh
git clone https://github.com/sck1ss/dwl
cd dwl
sudo make install clean
```

## removal
to remove dwl, `cd` into the directory you first cloned this repo into and then paste the following command into a terminal.
```sh
sudo make uninstall
cd ..
rm -rf dwl
```

## keybindings
<kbd>super + e</kbd> | `e-z.sh`

<kbd>super + p</kbd> | `rofi`

<kbd>super + t</kbd> | `dwl`:`t`

<kbd>super + m</kbd> | `dwl`:`m`

<kbd>super + f</kbd> | `dwl`:`f`

<kbd>audioraise</kbd> | `audio`:`+5`

<kbd>audiolower</kbd> | `audio`:`-5`

<kbd>audiomute</kbd> | `audio`:`t`

<kbd>super + shift + c</kbd> | `win`:`c`

<kbd>super + {0-4}</kbd> | `dwl`:`t-{0-4}`

<kbd>super + shift + {0-4}</kbd> | `dwl`:`s-{0-4}`

>[!NOTE]
  this fork follows the suckless philosophy of `elitism` which means it isn't meant for beginners.
