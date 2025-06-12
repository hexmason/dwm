# Hexmason's dwm build

## Features and applied patches

- [xrdb](https://dwm.suckless.org/patches/xrdb/): Allows dwm to read color variables from xrdb (.Xresources).
- [cursorwarp](https://dwm.suckless.org/patches/cursorwarp/): Waprs cursor when changing windows (<kbd>super+j/k</kbd>) and monitors (<kbd>super+,/.</kbd>).
- [pertag](https://dwm.suckless.org/patches/pertag/): Keeps layout, showbar and mfact per tag.
- [windowmap](https://dwm.suckless.org/patches/windowmap/): Makes the windows get mapped or unmapped in Xorg, so picom fade-in, fade-out and animations from picom works properly.
- [center](https://dwm.suckless.org/patches/center/): Adds (<kdb>iscentered</kdb>) rule in config.h to center the clients.
- [shiftview](https://dwm.suckless.org/patches/nextprev/): Cycle through tags (<kbd>super+a/s</kbd>).
- [vanitygaps](https://dwm.suckless.org/patches/vanitygaps/): Inner and outer gapps between clients.
- [barpadding](https://dwm.suckless.org/patches/barpadding/): Adds vertical and horizontal between the bar and the edge of the screen.

## Installation

```bash
git clone https://github.com/hexmason/dwm.git
cd dwm
sudo make install
```
