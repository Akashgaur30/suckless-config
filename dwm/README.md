## build of dwm

## FAQ

> What are the bindings?

## Patches and features

- Clickable statusbar with my build of [dwmblocks](https://github.com/prakash2033/dwmblocks).
- Reads xresources colors/variables (i.e. works with `pywal`, etc.).
- scratchpad: Accessible with mod+shift+enter.
- New layouts: bstack, fibonacci, deck, centered master and more. All bound to keys `super+(shift+)t/y/u/i`.
- True fullscreen (`super+f`) and prevents focus shifting.
- Windows can be made sticky (`super+s`).
- stacker: Move windows up the stack manually (`super-K/J`).
- shiftview: Cycle through tags (`super+g/;`).
- vanitygaps: Gaps allowed across all layouts.
- swallow patch: if a program run from a terminal would make it inoperable, it temporarily takes its place to save space.
- <strike>hide vacant tags : This patch prevents dwm from drawing tags with no clients (i.e. vacant) on the bar.</strike> [Removed]
- restartsig: dwm can now be restarted via MOD+Backspace(Renew dwm) or by kill -HUP dwmpid
- systray: A simple system tray implementation. Multi-monitor is also supported. The tray follows the selected monitor.

## Patch Files
- dwm-6.2-urg-border.diff
- dwm-actualfullscreen-20191112-cb3f58a.diff
- dwm-scratchpad-6.2.diff
- dwm-statuscmd-20210405-67d76bd.diff
- dwm-sticky-6.1.diff
- dwm-swallow-20201211-61bb8b2.diff
- dwm-systray-20210418-67d76bd.diff
- dwm-xrdb-6.2.diff

## Installation for newbs
```
git clone https://github.com/prakash2033/dwm
cd dwm
sudo make install
```
