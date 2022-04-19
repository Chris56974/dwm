# Chris's DWM build

Taken from [Luke Smith's DWM build](https://github.com/LukeSmithxyz/dwm)

> edit config.h
> install `libxft-bgra` to fix emoji color problem

```bash
sudo make install
```

You can view the shortcuts for it in the /usr/local/share/dwm/larbs.mom file

## Features

- Clickable statusbar via [dwmblocks](https://github.com/lukesmithxyz/dwmblocks).
- Reads xresources colors/variables (i.e. works with `pywal`, etc.).
- scratchpad: Accessible with mod+shift+enter.
- New layouts: bstack, fibonacci, deck, centered master and more. All bound to keys `super+(shift+)t/y/u/i`.
- True fullscreen (`super+f`) and prevents focus shifting.
- Windows can be made sticky (`super+s`).
- stacker: Move windows up the stack manually (`super-K/J`).
- shiftview: Cycle through tags (`super+g/;`).
- vanitygaps: Gaps allowed across all layouts.
- swallow patch: if a program run from a terminal would make it inoperable, it temporarily takes its place to save space.
