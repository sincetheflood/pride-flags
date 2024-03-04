Pride Flags
===========

A mildly opinionated (as in I am picking and choosing which flags I want to use) collection of handwritten pride flags available in the public domain.

All flags are available as both SVGs and PNGs inside the `flags/` directory and are split up by gender and orientation.  Templates to ease the creation of new flags are available inside the `templates/` directory.

The PNG flags are created by converting the SVG files to PNGs using the [librsvg](https://gitlab.gnome.org/GNOME/librsvg) command `rsvg-convert "${FLAG_NAME}.svg" -o "${FLAG_NAME}.png` and then compressed using the [oxipng](https://github.com/shssoichiro/oxipng) command `oxipng -o max -Z -a --strip all "${FLAG_NAME}.png"`.
