Pride Flags
===========

A mildly opinionated collection of handwritten pride flag images available in the public domain.

All flags are available as both SVGs and PNGs inside the `flags/` directory and are split up by gender and orientation. Templates to ease the creation of new flags are available inside the `templates/` directory.

PNG varients are created by converting the SVG files to PNGs using [librsvg](https://gitlab.gnome.org/GNOME/librsvg) and are then compressed using [oxipng](https://github.com/shssoichiro/oxipng):

```sh
rsvg-convert "${FLAG_NAME}.svg" --output "${FLAG_NAME}.png"
oxipng --opt max --zopfli --strip all --alpha "${FLAG_NAME}.png"
```

You are welcome to request flags by creating an [issue](https://github.com/sincetheflood/pride-flags/issues), though I make no promises about adding them. Pull requests are not currently accepted.
