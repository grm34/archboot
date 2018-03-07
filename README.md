<a href="https://grm34.github.io/archboot/">
  <img src="https://raw.githubusercontent.com/grm34/archboot/master/img/archboot.png" width="640">
</a>

[![version](https://img.shields.io/badge/archboot-v2.7.4-blue.svg)](https://github.com/grm34/archboot/releases) [![Build Status](https://travis-ci.org/grm34/archboot.svg?branch=master)](https://travis-ci.org/grm34/archboot) [![Gitter](https://badges.gitter.im/grm34/archboot.svg)](https://gitter.im/grm34/archboot?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge) [![author](https://img.shields.io/badge/author-grm34-red.svg)](https://github.com/grm34) [![license](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/grm34/archboot/blob/master/LICENSE)

[Arch Linux](https://www.archlinux.org/) is a light and fast distribution whose concept is to remain as simple as possible. In the same purpose, this script performs minimalist installation. It only installs the required packages in order to give free choice to the user. Pretty simple, it just prompt for hostname, username, password, which disk to use, required partitions size, language, timezone and if you wish to install a desktop environment. According to the chosen one and in order to get complete support, additionals packages may be required ([File System](https://wiki.archlinux.org/index.php/file_systems) - [Multimedia](https://wiki.archlinux.org/index.php/List_of_applications/Multimedia) - [Cups](https://wiki.archlinux.org/index.php/CUPS) - [Improving Performance](https://wiki.archlinux.org/index.php/improving_performance)).

## Requirements

The only thing you need is one **USB bootable device** of [Arch Linux](http://mir.archlinux.fr/iso/latest) and one **HDD dedicated** for the installation (see USB Boot instructions for [Windows](https://rufus.akeo.ie/?locale=fr_FR) or for [Linux](https://debian-facile.org/doc:install:usb-boot)).

## Usage

**1.** Reboot your computer, open Boot Selection Menu and boot on the USB bootable device.

**2.** On the install menu of ArchLinux, select [Boot Arch Linux (x86_64)](https://raw.githubusercontent.com/grm34/archboot/master/img/archlinux.png).

**3.** For AZERTY keyboard run: `loqdkeys fr`

**4.** Download archboot and follow the instructions: `wget tiny.cc/archboot; sh archboot`

## Notes

Available desktop environment: [KDE](https://wiki.archlinux.org/index.php/KDE) - [GNOME](https://wiki.archlinux.org/index.php/GNOME) - [Deepin](https://wiki.archlinux.org/index.php/Deepin_Desktop_Environment) - [Xfce](https://wiki.archlinux.org/index.php/xfce) - [LXDE](https://wiki.archlinux.org/index.php/LXDE)

Ability to enable [AUR](https://wiki.archlinux.org/index.php/Arch_User_Repository) and/or [Multilib](https://wiki.archlinux.org/index.php/multilib) support is also available.

## Logs

Take a look in **/var/log/archboot** for logs of the installation.

`cat /var/log/archboot/archboot_*.log`

## Screenshot

[![OS](https://img.shields.io/badge/Archlinux-Deepin-blue.svg)](https://raw.githubusercontent.com/grm34/archboot/master/img/screenshot.png)
![](https://raw.githubusercontent.com/grm34/archboot/master/img/screenshot.png)

## Official Documentation

Take a look at [Arch Linux Installation Guide](https://wiki.archlinux.org/index.php/Installation_guide) to view the official documentation.

## Improvement

Do not be afraid to open issue to purpose some improvements suck as new desktop environment ([Cinnamon](https://wiki.archlinux.org/index.php/cinnamon#Starting_Cinnamon), [Budgie](https://wiki.archlinux.org/index.php/Budgie_Desktop), [Enlightenment](https://wiki.archlinux.org/index.php/Enlightenment), [MATE](https://wiki.archlinux.org/index.php/MATE), [LXQt](https://wiki.archlinux.org/index.php/LXQt) will be implemented soon) or to fork and pull request better code quality.
