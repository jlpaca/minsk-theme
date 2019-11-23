![minsk](https://github.com/jlpaca/minsk-theme/blob/master/img/banner.png?raw=true)

> a theme in deep muted greens. for [emacs](https://www.gnu.org/software/emacs/).

**Minsk** is a low-ish-contrast theme on a restricted palette,
intended for generic everyday use.  It tries to be almost-monochrome,
and most of the time prefers highlighting by font style over by
colour, though it isn't excessively strict about wiggling a little in
hue-space.

Support for various modes far from exhaustive —
[feedback](https://github.com/jlpaca/minsk-theme/issues/new) and
[contributions](https://github.com/jlpaca/minsk-theme/compare) would
be most welcome.


## Screenshot

![screenshot](https://github.com/jlpaca/minsk-theme/blob/master/img/screenshot.png?raw=true)

## Installation

#### With `package.el`
```
M-x package-install-file minsk-theme.el
M-x customize-themes
```

#### Manual
place `minsk-theme.el` in `~/.emacs.d/themes/` and add the following to `init.el`:

```
(add-to-list 'custom-theme-load-path "~/.emacs.d/themes")
(load-theme 'minsk t)
```
