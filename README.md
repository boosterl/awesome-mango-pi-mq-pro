# Awesome MangoPi MQ-Pro

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

The [MangoPi MQ-Pro](https://mangopi.cc/mangopi_mqpro) is an SBC in a Raspberry Pi Zero form-factor, equiped with an [Allwiner D1](https://linux-sunxi.org/D1) RISC-V CPU.

This list is a collection of tools, projects, images and resources conforming to the [Awesome Manifesto](https://github.com/sindresorhus/awesome/blob/master/awesome.md)

## Contents

- [OS Images](#os-images)
- [Tools](#tools)
- [Resources](#resources)

## OS Images

- [Arch Linux](https://github.com/sehraf/riscv-arch-image-builder) - Lightweight and flexible Linux distribution that tries to Keep It Simple.
- [Armbian](https://www.armbian.com/mangopi-mq-pro/)
- [Debian](https://github.com/tmolteno/d1_build) - Debian with patched mainline kernel
- [Deepin](https://github.com/deepin-community/deepin-riscv-board/releases) - Deepin v23 for Allwinner D1 systems
- [Fedora RISC-V](https://popolon.org/depots/RISC-V/D1/ovsienko/)
- [FreeBSD D1](https://github.com/freebsd-d1/freebsd-d1) - FreeBSD for Allwinner D1 systems
- [Gentoo](https://github.com/Rabenda/riscv-calculate/releases)
- [Nerves](https://github.com/nerves-project/nerves_system_mangopi_mq_pro)
- [NixOS](https://github.com/chuangzhu/nixos-sun20iw1p1)
- [openSUSE](https://github.com/boosterl/opensuse-d1) - openSUSE Tumbleweed for Allwinner D1 systems
- [postmarketOS](https://wiki.postmarketos.org/wiki/MangoPi_MQ-Pro_(mangopi-mq-pro)) - The distribution for mobile devices, now on the MangoPi MQ-Pro
- [RVBoards Debian](https://popolon.org/depots/RISC-V/D1/ovsienko/) - Debian distribution build by [RVBoards](https://rvboards.org/) originally for the [Allwinner Nezha](https://linux-sunxi.org/Allwinner_Nezha). The 6.1 version needs the OpenixCard tool to write the image to an SD card, see [Tools](#tools).
- [Tina Linux](https://mangopi.cc/d1) - The first OS image specifically for the MangoPi MQ-Pro, distributed by MangoPi. The OpenixCard tool is needed to write the image to an SD card, see [Tools](#tools).
- [Ubuntu](https://cdimage.ubuntu.com/releases/23.04/release/ubuntu-23.04-preinstalled-server-riscv64+nezha.img.xz) - Ubuntu image, compatible with the MangoPi MQ Pro
- [xv6-d1](https://github.com/michaelengel/xv6-d1) Port of MIT's xv6 OS to the Nezha RISC-V board with Allwinner D1 SoC. 

## Tools

- [OpenixCard](https://github.com/YuzukiTsuru/OpenixCard) - Open Source clone of the proprietary [Windows only "PhoenixCard" tool](https://dl.sipeed.com/shareURL/LICHEE/D1/Lichee_RV/tool), for writing img files needing this flash tool.

## Resources

### Articles

- [Exploring non-Linux Based Operating Systems on Allwinner D1](https://worldbeyondlinux.be/posts/exploring-non-linux-oses-on-d1/) - Article about running FreeBSD and xv6 on the MangoPi MQ-Pro
- [GPIO on the MangoPi MQ-Pro](https://worldbeyondlinux.be/posts/gpio-on-the-mango-pi/) - Article about accessing GPIO pins on the MangoPi MQ-Pro
- [How to Use a Raspberry Pi Instead of a USB Console Cable](https://worldbeyondlinux.be/posts/how-to-use-a-pi-instead-of-a-usb-console-cable/) - Article about using a Raspberry Pi as serial console for the MangoPi MQ-Pro
- [MangoPi MQ Pro – Is it better than the Pi Zero?](https://bret.dk/mangopi-mq-pro-released/) - Comparison between the MangoPi MQ-Pro and the Raspberry Pi Zero.
- [MangoPi MQ Pro - Benchmarks and review](https://bret.dk/mangopi-mq-pro-benchmarks-review/) - Benchmakrs of the MangoPi MQ-Pro.
- [MangoPi MQ Pro - Raspberry Pi Zero vs MangoPi MQ-Pro benchmarks](https://bret.dk/raspberry-pi-zero-vs-mangopi-mq-pro-benchmarks/) - Benchmark comparison of the Raspberry Pi Zero and MangoPi MQ-Pro.
- [Mango Pi MQ Pro D1 Ubuntu (P)review](https://jamesachambers.com/mangopi-mq-pro-d1-ubuntu-preview/) - Review of Ubuntu preview image on the MangoPi MQ-Pro
- [Running x86_64 Software on RISC-V Using Box64](https://worldbeyondlinux.be/posts/running-x86-64-software-on-riscv-using-box64/) - Article about running x86_64 software on RISC-V, specifically a MangoPi MQ-Pro using [Box64](https://github.com/ptitSeb/box64/)
- [Setting up Bluetooth on the MangoPi MQ-Pro, and testing it out with a Bluetooth access point](https://worldbeyondlinux.be/posts/bluetooth-on-the-mango-pi/) - Article about enabling Bluetooth support on the MangoPi MQ-Pro and using it as a Bluetooth access point.

### Wiki Pages

- [MangoPi MQ-Pro-page on linux-sunxi.org](https://linux-sunxi.org/MangoPi_MQ-Pro) - Wiki page covering specs, revisions, GPIO-layout etc.
