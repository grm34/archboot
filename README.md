![](http://i.imgur.com/z4nv4Kj.png)

## Requirements

The only thing you need is an **USB bootable device** of ArchLinux, you can create it like this :

1. Download the latest archlinux iso : *http://mir.archlinux.fr/iso/latest*

2. Download rufus : *https://rufus.akeo.ie/downloads/*

3. Open rufus, select the USB Drive and the iso : *https://raw.githubusercontent.com/grm34/archboot/master/img/rufus.png*

## Install Archlinux

1. Reboot your computer, open Boot Selection Menu and select the USB bootable device.

2. Select **Boot Arch Linux (x86_64)** : *https://raw.githubusercontent.com/grm34/archboot/master/img/archlinux.png*

3. Then run this command and follow the instructions :

    `wget https://raw.githubusercontent.com/grm34/archboot/master/install_arch && sh install_arch`

## Desktop Environment

1. If you want to install GNOME desktop, login and run :

    `wget https://raw.githubusercontent.com/grm34/archboot/master/install_gnome && sh install_gnome`

2. Or if you want to install XFCE4 desktop, login and run :

    `wget https://raw.githubusercontent.com/grm34/archboot/master/install_xfce && sh install_xfce`

3. Or if you want to install LXDE desktop, login and run :

    `wget https://raw.githubusercontent.com/grm34/archboot/master/install_lxde && sh install_lxde`

## Notes

**install_arch** > ArchLinux base system with Grub.

**install_gnome** > GNOME desktop environment.

**install_xfce** > XFCE4 desktop environment.

**install_lxde** > LXDE desktop environment.

## Logs
Take a look in **/var/log/archboot/**
