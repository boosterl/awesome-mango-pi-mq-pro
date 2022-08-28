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
- [Armbian](https://forum.armbian.com/topic/21465-armbian-image-and-build-support-for-risc-v/)
- [Debian](https://github.com/tmolteno/d1_build) - Debian with patched mainline kernel
- [Fedora RISC-V](https://popolon.org/depots/RISC-V/D1/ovsienko/)
- [Gentoo](https://github.com/Rabenda/riscv-calculate/releases)
- [NixOS](https://github.com/chuangzhu/nixos-sun20iw1p1)
- [RVBoards Debian](https://popolon.org/depots/RISC-V/D1/ovsienko/) - Debian distribution build by [RVBoards](https://rvboards.org/) originally for the [Allwinner Nezha](https://linux-sunxi.org/Allwinner_Nezha). The 6.1 version needs the OpenixCard tool to write the image to an SD card, see [Tools](#tools).
- [Tina Linux](https://mangopi.cc/d1) - The first OS image specifically for the MangoPi MQ-Pro, distributed by MangoPi. The OpenixCard tool is needed to write the image to an SD card, see [Tools](#tools).
- [Ubuntu](http://cdimage.ubuntu.com/ubuntu-server/jammy/daily-preinstalled/current/jammy-preinstalled-server-riscv64+nezha.img.xz) - Ubuntu image, compatible with the MangoPi MQ Pro

## Tools

- [OpenixCard](https://github.com/YuzukiTsuru/OpenixCard) - Open Source clone of the proprietary [Windows only "PhoenixCard" tool](https://dl.sipeed.com/shareURL/LICHEE/D1/Lichee_RV/tool), for writing img files needing this flash tool.

## Resources

### Articles

- [How to Use a Raspberry Pi Instead of a USB Console Cable](https://worldbeyondlinux.be/posts/how-to-use-a-pi-instead-of-a-usb-console-cable/) - Article about using a Raspberry Pi as serial console for the MangoPi MQ-Pro
- [MangoPi MQ Pro – Is it better than the Pi Zero?](https://bret.dk/mangopi-mq-pro-released/) - Comparison between the MangoPi MQ-Pro and the Raspberry Pi Zero.
- [MangoPi MQ Pro - Benchmarks and review](https://bret.dk/mangopi-mq-pro-benchmarks-review/) - Benchmakrs of the MangoPi MQ-Pro.
- [MangoPi MQ Pro - Raspberry Pi Zero vs MangoPi MQ-Pro benchmarks](https://bret.dk/raspberry-pi-zero-vs-mangopi-mq-pro-benchmarks/) - Benchmark comparison of the Raspberry Pi Zero and MangoPi MQ-Pro.
