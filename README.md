<a href="https://grm34.github.io/archboot/">
  <img src="https://raw.githubusercontent.com/grm34/archboot/gh-pages/assets/images/logo.png">
</a>

[![version](https://img.shields.io/badge/version-v2.8.4-blue.svg)](https://github.com/grm34/archboot/releases) [![Build Status](https://travis-ci.org/grm34/archboot.svg?branch=master)](https://travis-ci.org/grm34/archboot) [![author](https://img.shields.io/badge/author-grm34-red.svg)](https://github.com/grm34) [![license](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/grm34/archboot/blob/master/LICENSE) [![telegram](https://img.shields.io/badge/Telegram-chat-red)](https://t.me/archboot) [![maintenance](https://img.shields.io/maintenance/yes/2020.svg)](https://github.com/grm34/archboot/pulse)

Arch Linux is a light and fast distribution whose concept is to remain as simple as possible. In the same purpose, this script performs minimalist installation, it only installs the required packages in order to give free choice to the user. Pretty simple, it just prompt for language, hostname, username, which disk to use, required partitions size and if you wish to install a desktop environment. According to the chosen one and in order to get complete support, additional packages may be required.

## Requirements

The only thing you need is one **USB bootable device** of [Arch Linux](https://mir.archlinux.fr/iso/latest)

* USB Boot instruction for [Windows](https://rufus.ie/) or [Linux](https://wiki.archlinux.org/index.php/USB_flash_installation_media)

## Usage

**1.** Reboot your computer, open Boot Selection Menu and boot on the USB device

**2.** On the install menu of Arch Linux, select Boot Arch Linux (x86_64)

**3.** For AZERTY keyboard run: `loqdkeys fr`

**4.** Download and follow the instructions `wget tiny.cc/archboot-dev; sh archboot-dev`

## Wiki

* [Installation step by step](https://github.com/grm34/archboot/wiki/Installation-step-by-step)
* [Desktop Environment](https://github.com/grm34/archboot/wiki/Desktop-Environment)
* [Display Manager](https://github.com/grm34/archboot/wiki/Display-Manager)
* [Language code](https://github.com/grm34/archboot/wiki/Language-code)
* [TimeZone code](https://github.com/grm34/archboot/wiki/TimeZone-code)
* [Custom Partitioning](https://github.com/grm34/archboot/wiki/Custom-Partitioning)
* [Custom Linux Kernel](https://github.com/grm34/archboot/wiki/Custom-Linux-Kernel)
* [List of installed Packages](https://github.com/grm34/archboot/wiki/List-of-installed-Packages)

## Logs

Take a look at **/var/log/archboot** for logs: `cat /var/log/archboot/archboot*.log`

## Screenshot

<a href="https://raw.githubusercontent.com/grm34/archboot/gh-pages/assets/images/screenshot.png">
  <img src="https://raw.githubusercontent.com/grm34/archboot/gh-pages/assets/images/screenshot.png">
</a>

## Official Documentation

* [Arch Linux Installation Guide](https://wiki.archlinux.org/index.php/Installation_guide) for the official documentation
* [VGA Drivers](https://wiki.archlinux.org/index.php/Xorg#Driver_installation) open source and proprietary drivers support
* [Bumblebee](https://wiki.archlinux.org/index.php/Bumblebee) available in case of Intel+nVidia controller
* [File System](https://wiki.archlinux.org/index.php/file_systems) (may be required if not included in DE)
* [Multimedia](https://wiki.archlinux.org/index.php/List_of_applications/Multimedia) (may be required if not included in DE)
* [Cups](https://wiki.archlinux.org/index.php/CUPS) (may be required if not included in DE)
* [Sane](https://wiki.archlinux.org/index.php/SANE) (may be required if not included in DE)
* [Samba](https://wiki.archlinux.org/index.php/Samba) (may be required if not included in DE)

[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/for-you.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/its-not-a-lie-if-you-believe-it.svg)](https://forthebadge.com)
