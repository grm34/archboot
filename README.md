## Arch Linux auto install

[![version](https://img.shields.io/badge/archboot-v2.7.8-blue.svg)](https://github.com/grm34/archboot/releases) [![Build Status](https://travis-ci.org/grm34/archboot.svg?branch=master)](https://travis-ci.org/grm34/archboot) [![author](https://img.shields.io/badge/author-grm34-red.svg)](https://github.com/grm34) [![license](https://img.shields.io/badge/license-Apache%202.0-yellowgreen.svg)](https://github.com/grm34/archboot/blob/master/LICENSE) [![Gitter](https://badges.gitter.im/grm34/archboot.svg)](https://gitter.im/grm34/archboot?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge) [![maintenance](https://img.shields.io/maintenance/yes/2018.svg)](https://github.com/grm34/archboot/pulse)

[Arch Linux](https://www.archlinux.org/) is a light and fast distribution whose concept is to remain as simple as possible. In the same purpose, this script performs minimalist installation, it only installs the required packages in order to give free choice to the user. Pretty simple, it just prompt for hostname, username, password, which disk to use, required partitions size, language, timezone and if you wish to install a desktop environment. According to the chosen one and in order to get complete support, additionals packages may be required ([File System](https://wiki.archlinux.org/index.php/file_systems) - [Multimedia](https://wiki.archlinux.org/index.php/List_of_applications/Multimedia) - [Cups](https://wiki.archlinux.org/index.php/CUPS) - [Sane](https://wiki.archlinux.org/index.php/SANE) - [Samba](https://wiki.archlinux.org/index.php/Samba) - [Improving Performance](https://wiki.archlinux.org/index.php/improving_performance)).

## Requirements
The only thing you need is one **USB bootable device** of [Arch Linux](http://mir.archlinux.fr/iso/latest) and one **HDD dedicated** for the installation.
* USB Boot instructions for [Windows](https://rufus.akeo.ie/?locale=fr_FR) or for [Linux](https://debian-facile.org/doc:install:usb-boot)

## Usage
**1.** Reboot your computer, open Boot Selection Menu and boot on the USB device

**2.** On the install menu of Arch Linux, select Boot Arch Linux (x86_64)

**3.** For AZERTY keyboard run: `loqdkeys fr`

**4.** Download and follow the instructions `wget tiny.cc/archboot; sh archboot`

## Wiki
* [Installation step by step](https://github.com/grm34/archboot/wiki/Installation-step-by-step)
* [Desktop Environment](https://github.com/grm34/archboot/wiki/Desktop-Environment)
* [Display Manager](https://github.com/grm34/archboot/wiki/Display-Manager)
* [Language code](https://github.com/grm34/archboot/wiki/Language-code)
* [TimeZone code](https://github.com/grm34/archboot/wiki/TimeZone-code)
* [List of installed Packages](https://github.com/grm34/archboot/wiki/List-of-installed-Packages)
* [VGA Drivers](https://wiki.archlinux.org/index.php/Xorg#Driver_installation) open source and proprietary support available
* [Bumblebee](https://wiki.archlinux.org/index.php/Bumblebee) support available in case of Intel+nVidia controller

## Logs
Take a look in **/var/log/archboot** for logs: `cat /var/log/archboot/archboot_*.log`

## Screenshot
<a href="https://grm34.github.io/archboot/">
  <img src="https://raw.githubusercontent.com/grm34/archboot/gh-pages/assets/images/screenshot.png">
</a>

## Official Documentation
Take a look at [Arch Linux Installation Guide](https://wiki.archlinux.org/index.php/Installation_guide) for the official documentation.

[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/for-you.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/its-not-a-lie-if-you-believe-it.svg)](https://forthebadge.com)
