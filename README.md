# st

Fork of st with some patches applied and personal modifications.

## Applied patches

* [scrollback](https://st.suckless.org/patches/scrollback/): scrollback support for terminal output
* [scrollback-mouse-altscreen](https://st.suckless.org/patches/scrollback/): scrollback with mouse wheel only
* [alpha](https://st.suckless.org/patches/alpha/): allows changing background opacity
* [alpha-focus-highlight](https://st.suckless.org/patches/alpha_focus_highlight/): distinct opacity for focused and unfocused windows
* [anysize](https://st.suckless.org/patches/anysize/): eliminate surrounding window gaps by using up excess space

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

* Font:
  * Default: dina-7:regular (bitmap font, doesn't scale well, good for coding)
  * For a zoomable font run with -f 'Liberation Mono:pixelsize=12:antialias=true:autohint=true'<br>(default from upstream, good for presentations)
* Borderpixel: 1px
* Focused/unfocused instances:
  * Bg color is the same: 235
  * 0% opacity for focused
  * 10% opacity for unfocused
  * Note: these are just some baseline values, good values for these heavily rely on a lot of things:<br>fg color, wallpaper in use, dircolors,...

