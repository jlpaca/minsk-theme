![minsk-emacs](https://github.com/jlpaca/minsk-theme/blob/emacs/theme/emacs/img/banner-emacs.png?raw=true)

> a theme in deep muted greens. for [emacs](https://www.gnu.org/software/emacs/).

Support for various modes is yet far from exhaustive —
[feedback](https://github.com/jlpaca/minsk-theme/issues/new) and
[contributions](https://github.com/jlpaca/minsk-theme/compare) are
most welcome.

## Installation

#### From [MELPA](https://melpa.org)

Install the [package](https://melpa.org/#/minsk-theme):

```
M-x package-install RET minsk-theme RET
```

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
