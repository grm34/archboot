![](http://i.imgur.com/z4nv4Kj.png)

**Install ArchLinux the way i like [FR]**

## Requirements

The only thing you need is an USB bootable device of ArchLinux, you can create it like this :

1. Download the latest archlinux iso : *http://mir.archlinux.fr/iso/latest*

2. Download rufus : *https://rufus.akeo.ie/downloads/*

3. Open rufus and select the archlinux iso like here : *https://rufus.akeo.ie/?locale=fr_FR*

## Usage

**1. Boot your computer on the USB bootable device and run :**

`wget https://raw.githubusercontent.com/grm34/archboot/master/install_arch && sh install_arch`

**2. After reboot, for full desktop environment (GNOME), login and run :**

`wget https://raw.githubusercontent.com/grm34/archboot/master/install_desktop && sh install_desktop`

## Notes

**install_arch** install ArchLinux base system with Grub.

**install_desktop** install GNOME desktop environment.

## Logs
Take a look in **/var/log/archboot/**
