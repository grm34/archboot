![](https://raw.githubusercontent.com/grm34/archboot/master/img/archboot.png)

## Description

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

## Desktop Environment

During the installation, you can choose if you want or not to install a desktop environment.
For now only this ones are availables: **KDE**, **Gnome**, **Xfce4**, **Lxde**)

## Logs
Take a look in **/var/log/archboot/**

## XFCE4 Screenshot

![](https://raw.githubusercontent.com/grm34/archboot/master/img/screenshot.png)
