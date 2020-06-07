# Thiru's build of dwm

[dwm](https://dwm.suckless.org/) is a minimalist tiling window manager for Linux.

## FAQ

1. This isn't a fork because the upstream repo is not on Github.

1. The structure of this repo was originally based on [this guide from Suckless](https://dwm.suckless.org/customisation/patches_in_git/). I've since made some changes.

1. The **master** branch contains my current build of dwm with all the patches and customisations merged.

1. The **upstream** branch follows Suckless' **master** branch.

1. Branches that start with **patch-** are "official" patches [available on Suckless](https://dwm.suckless.org/patches/).

## Patches

* [autostart](https://dwm.suckless.org/patches/autostart/)
  * changed autostart scripts path from `~/.dwm` to `~/.config/dwm`
* [restartsig](https://dwm.suckless.org/patches/restartsig/)
  * default binding is `mod + ctrl + shift + q`
* [scratchpad](https://dwm.suckless.org/patches/scratchpad/)
  * changed terminal to `Alacritty`
  * changed binding to `mod + s`
