# Awesome Wayland

A curated list of [Wayland](https://gitlab.freedesktop.org/wayland/wayland) code and resources.

If you want to contribute, please read [this](CONTRIBUTING.md).

## Table of contents

  - [Brightness Control](#brightness-control)
  - [Clipboard Managers](#clipboard-managers)
  - [Compositors](#compositors)
  - [Display Configuration](#display-configuration)
  - [Launchers](#launchers)
  - [Libraries]($libraries)
  - [Notifications](#notifications)
  - [Screen Locking](#screen-locking)
  - [Screencasting](#screencasting)
  - [Screenshots](#screenshots)
  - [Status Bars](#status-bars)
  - [Terminal Emulators](#terminal-emulators)
  - [Wallpaper](#wallpaper)
  - [License](#license)

## Brightness Control

No Wayland-specific requirements, so you can use your xorg solution of choice to control screen brightness, like [brightnessctl](https://github.com/Hummer12007/brightnessctl), [brillo](https://gitlab.com/cameronnemo/brillo), [light](https://github.com/haikarainen/light), or just directly manipulate `/sys/class/backlight`.

## Clipboard Managers

* [wl-clipboard](https://github.com/bugaevc/wl-clipboard) - Command-line copy/paste utilities for Wayland
* [clipman](https://github.com/yory8/clipman) - A simple clipboard manager for Wayland

## Compositors

* [Sway](https://github.com/swaywm/sway) - i3-compatible Wayland compositor
* [Wayfire](https://github.com/WayfireWM/wayfire) - 3D wayland compositor
* [Weston](https://gitlab.freedesktop.org/wayland/weston/) - Reference compositor for Wayland

## Display Configuration

* [Kanshi](https://github.com/emersion/kanshi) - Dynamic display configuration

## Launchers

* [Wofi](https://hg.sr.ht/~scoopta/wofi) - a launcher/menu program for wlroots based wayland compositors such as sway

## Libraries

* [wlroots](https://github.com/swaywm/wlroots) - Pluggable, composable, unopinionated modules for building a Wayland compositor

## Notifications

* [Mako](https://github.com/emersion/mako) - A lightweight Wayland notification daemon

## Screen Locking

* [swayidle](https://github.com/swaywm/swayidle) - Idle management daemon for Wayland
* [swaylock](https://github.com/swaywm/swaylock) - Screen locker for Wayland
* [swaylock-blur](https://github.com/cjbassi/swaylock-blur) - A small Rust program that runs swaylock and sets the image to a blurred screenshot of the desktop

## Screencasting

* [wf-recorder](https://github.com/ammen99/wf-recorder) - a utility program for screen recording of `wlroots`-based compositors (more specifically, those that support `wlr-screencopy-v1` and `xdg-output`)

## Screenshots

* [Grim](https://github.com/emersion/grim) - Grab images from a Wayland compositor
* [Slurp](https://github.com/emersion/slurp) - Select a region in a Wayland compositor

## Status Bars

* [i3status-rust](https://github.com/greshake/i3status-rust) - Very resource-friendly and feature-rich replacement for i3status, written in pure Rust
* [rootbar](https://hg.sr.ht/~scoopta/rootbar) - Root Bar is a bar for wlroots based wayland compositors such as sway
* [waybar](https://github.com/Alexays/Waybar) - Highly customizable Wayland bar for Sway and Wlroots based compositors

## Terminal Emulators

* [Alacritty](https://github.com/alacritty/alacritty) - A cross-platform, GPU-accelerated terminal emulator
* [Kitty](https://github.com/kovidgoyal/kitty) - A cross-platform, fast, feature-full, GPU-based terminal emulator
* [Termite](https://github.com/thestinger/termite) - A keyboard-centric VTE-based terminal, aimed at use within a window manager with tiling and/or tabbing support

## Wallpaper

* [swaybg](https://github.com/swaywm/swaybg) - a wallpaper utility for Wayland compositors

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)