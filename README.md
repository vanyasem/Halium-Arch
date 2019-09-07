# Halium-Arch

## About
This project aims to make Arch GNU/Linux compatible with [Halium](http://halium.org).

It currently only supports `aarch64` phones, but support for `armv7` and `x86` is planned. You can find an experimental rootfs [here](https://halium.mynameisivan.ru/arch/ArchLinuxArm-rootfs-aarch64-caf-20180619.tar.bz2).

### Progress
_Clickable icons:_

- 🌍 - Available in the repository
- ✅ - Available in the AUR
- 😜 - Git version is available in the AUR
- ⛔️ - Unresolved issues
- 🆗 - Resolved issues

**Utility:**
- [ ] `rootfs-builder` [⛔️](https://github.com/mickybart/rootfs-builder/pull/1)
- [x] `simg-tools` [submodule](https://aur.archlinux.org/packages/simg-tools/) | [🆗](https://aur.archlinux.org/pkgbase/simg-tools/?comments=all)

**Halium packages:**
- [x] `hybris-usb` [submodule](https://aur.archlinux.org/packages/hybris-usb/) | [⛔️](https://aur.archlinux.org/pkgbase/hybris-usb/?comments=all) [⛔️](https://aur.archlinux.org/pkgbase/hybris-usb/?comments=all)
- [x] `hybris-android-headers-7` [🌍](https://github.com/vanyasem/Halium-Arch/tree/master/hybris-android-headers-7)
- [x] `libhybris` [submodule](https://aur.archlinux.org/packages/libhybris-git/)
- [x] `lxc-android` [🌍](https://github.com/vanyasem/Halium-Arch/tree/master/lxc-android-git) | [⛔️](https://github.com/Halium/lxc-android/issues/13) [⛔️](https://github.com/Halium/lxc-android/pull/15)

**Xorg packages:**
- [x] `xf86-video-hwcomposer` [🌍](https://github.com/vanyasem/Halium-Arch/tree/master/xf86-video-hwcomposer-git)
- [x] `drihybris` [🌍](https://github.com/vanyasem/Halium-Arch/tree/master/drihybris-git)
- [x] `glamor-hybris` [🌍](https://github.com/vanyasem/Halium-Arch/tree/master/glamor-hybris-git)
- [x] `libhybris-xorg` [🌍](https://github.com/vanyasem/Halium-Arch/tree/master/libhybris-xorg-git)
