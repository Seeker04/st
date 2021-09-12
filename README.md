# st

Fork of st with some patches applied and personal modifications.

## Applied patches

* [scrollback](https://st.suckless.org/patches/scrollback/): scrollback support for terminal output
* [scrollback-mouse-altscreen](https://st.suckless.org/patches/scrollback/): scrollback with mouse wheel only

## Personal modifications



## Personal config (only in config.h)

### Keymaps

* Shift + Alt + Numpad Add: zoom in
* Shift + Alt + Numpad Sub: zoom out
* Shift + Alt + Numpad Div: zoom reset
* Shift + Alt + k: scroll up
* Shift + Alt + j: scroll down

### Colors

* Bg: 108 - dark gray (slightly less contrast)
* Fg: 235 - light blue (works well with both gruvbox and "Void Linux-like" schemes)

### Other

* Font, depending on the value of NEED\_ZOOMABLE\_FONT (0 by default):
  * 0: dina-7:regular (bitmap font, doesn't scale well)
  * 1: Liberation Mono:pixelsize=12:antialias=true:autohint=true (default from upstream)
* Borderpixel: 1px

