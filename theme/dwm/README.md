![minsk-dwm](https://github.com/jlpaca/minsk-theme/blob/suckless/theme/dwm/img/banner-dwm.png?raw=true)

> a theme in deep muted greens. for [dwm](https://dwm.suckless.org).

## Installation

In the `dwm-6.2` directory: 

```
patch -p1 < dwm-minsktheme-6.2.diff
```

Alternatively: `dwm-minsktheme-6.2.config.h` is a version of the config file
with additional changes including setting a preferred font, and enabling by
default keyboard volume control and Xinerama support. If those settings work
for you, you may also compile `dwm` with

```
make DWM_CONF=dwm-minsktheme-6.2.config.h install
```

See also the related documentation at [suckless.org](https://suckless.org/hacking).
