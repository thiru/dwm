# Thiru's build of dwm

[dwm](https://dwm.suckless.org/) is a minimalist tiling window manager for Linux.

## FAQ

1. This isn't a fork because the [upstream repo](https://git.suckless.org/dwm) is not on Github.

1. The structure of this repo was originally based on [this guide](https://dwm.suckless.org/customisation/patches_in_git/). The changes I made are mostly around making it easier for Github users.

1. The **master** branch contains my current build of dwm with all the patches and customisations merged.

1. The **upstream** branch follows suckless' **master** branch.

1. Branches that start with **patch-** are based on ["official" patches](https://dwm.suckless.org/patches/) available as source on the suckless website.

## Patches

* [actualfullscreen](https://dwm.suckless.org/patches/actualfullscreen/)
  * `mod + shift + f`
* [autostart](https://dwm.suckless.org/patches/autostart/)
  * changed autostart scripts path from `~/.dwm` to `~/.config/dwm`
* [centeredmaster](https://dwm.suckless.org/patches/centeredmaster/)
* [fullgaps](https://dwm.suckless.org/patches/fullgaps/)
  * `mod + =` increase gap
  * `mod + -` decrease gap
  * `mod + shift + =` remove gaps
* [restartsig](https://dwm.suckless.org/patches/restartsig/)
  * `mod + ctrl + shift + q`
* [scratchpad](https://dwm.suckless.org/patches/scratchpad/)
  * `mod + s`
    * (default was `mod + tilde`)
  * changed terminal to `Alacritty`
* [sticky](https://dwm.suckless.org/patches/sticky/)
  * `mod + shift + s`
    * (default was `mod + s`)
