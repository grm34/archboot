![](https://raw.githubusercontent.com/grm34/archboot/master/img/archboot.png)

## Archboot [![Build Status](https://travis-ci.org/grm34/archboot.svg?branch=master)](https://travis-ci.org/grm34/archboot)

[![Join the chat at https://gitter.im/grm34/archboot](https://badges.gitter.im/grm34/archboot.svg)](https://gitter.im/grm34/archboot?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

This script perform an automatic install of Archlinux.
Pretty simple, it only ask you for hostname, username,
password, which disk to use, required partitions sizes
and if you wish or not to install desktop environment.
KDE | Gnome | Xfce4 | Lxde are available.

## Requirements

The only thing you need is one **USB bootable device** of [ArchLinux](http://mir.archlinux.fr/iso/latest) and one **HDD dedicated** for the installation (see USB Boot instructions for [Windows](https://rufus.akeo.ie/?locale=fr_FR) or for [Linux](https://debian-facile.org/doc:install:usb-boot)).

## Usage

**1.** Reboot your computer, open Boot Selection Menu and boot on the USB bootable device.

**2.** Select **Boot Arch Linux (x86_64)** ([screenshot](https://raw.githubusercontent.com/grm34/archboot/master/img/archlinux.png))

**3.** Set AZERTY keyboard by running this command: `loqdkeys fr`

**4.** Download Archboot and follow the instructions:

`wget https://itsssl.com/archboot; sh archboot`

## Logs
Take a look in **/var/log/archboot/**

## Screenshot [xfce4]

![](https://raw.githubusercontent.com/grm34/archboot/master/img/screenshot.png)
