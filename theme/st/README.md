![minsk-st](https://github.com/jlpaca/minsk-theme/blob/img/banner-st.png?raw=true)

> a theme in deep muted greens. for [st](https://st.suckless.org).

## Installation

In the `st-0.8.2` directory: 

```
patch -p1 < st-minsktheme-0.8.2.diff
```

`st-minsktheme-0.8.2.config.h` is a version of the config file
which also sets a preferred font, removes borders, and enables scrollback by
default. If those settings work for you, you may alternatively compile `st` with

```
make ST_CONF=st-minsktheme-0.8.2.config.h install
```

See also the related documentation at [suckless.org](https://suckless.org/hacking).
