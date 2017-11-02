![](http://i.imgur.com/z4nv4Kj.png)

## Requirements

The only thing you need is one **USB bootable device** of ArchLinux and one **HDD dedicated** for the installation.

- USB Boot Instructions for [Windows](https://rufus.akeo.ie/?locale=fr_FR)

- USB Boot Instructions for [Linux](https://debian-facile.org/doc:install:usb-boot)

## Usage

**1.** Reboot your computer, open Boot Selection Menu and select the USB bootable device.

**2.** Select **Boot Arch Linux (x86_64)** ([screenshot](https://raw.githubusercontent.com/grm34/archboot/master/img/archlinux.png))

**3.** Set AZERTY keyboard by running this command:

`loqdkeys fr`

**4.** Download Archboot and follow the instructions:

`wget https://raw.githubusercontent.com/grm34/archboot/master/archboot && sh archboot`

## Desktop Environment

During the installation, you can choose if you want or not to install a desktop environment.
For now only this ones are availables: **KDE**, **Gnome**, **Xfce4**, **Lxde**)

## Logs
Take a look in **/var/log/archboot/**
