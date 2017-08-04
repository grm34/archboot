![](http://i.imgur.com/z4nv4Kj.png)

**Install ArchLinux the way i like [FR]**

## Requirements

The only thing you need is an USB bootable device of ArchLinux, you can create it like this :

1. Download the latest archlinux iso : *http://mir.archlinux.fr/iso/latest*

2. Download rufus : *https://rufus.akeo.ie/downloads/*

3. Open rufus, select the USB Drive and the iso : *https://rufus.akeo.ie/pics/rufus_fr.png*

## Usage

1. Reboot your computer, open Boot Menu and select the USB bootable device.

2. Select *Boot Arch Linux (x86_64)* : *https://raw.githubusercontent.com/grm34/archboot/master/img/archlinux.png*

3. Then run :

`wget https://raw.githubusercontent.com/grm34/archboot/master/install_arch && sh install_arch`

4. After reboot, for full desktop environment, login and run :

`wget https://raw.githubusercontent.com/grm34/archboot/master/install_desktop && sh install_desktop`

## Notes

**install_arch** install ArchLinux base system with Grub.

**install_desktop** install GNOME desktop environment.

## Logs
Take a look in **/var/log/archboot/**
