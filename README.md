![](http://i.imgur.com/z4nv4Kj.png)

## Requirements

The only thing you need is an **USB bootable device** of ArchLinux, if you are
on windows you can create it like this :

1. Download the latest archlinux iso : *http://mir.archlinux.fr/iso/latest*

2. Download rufus : *https://rufus.akeo.ie/downloads/*

3. Open rufus, select the USB Drive and the iso : *https://raw.githubusercontent.com/grm34/archboot/master/img/rufus.png*

## Usage

1. Reboot your computer, open Boot Selection Menu and select the USB bootable device.

2. Select **Boot Arch Linux (x86_64)** : *https://raw.githubusercontent.com/grm34/archboot/master/img/archlinux.png*

3. Then run this command and follow the instructions :

    `wget https://raw.githubusercontent.com/grm34/archboot/master/archboot && sh archboot`

## Desktop Environment

You can choose during the installation if you want to install a desktop environment.
For now only this ones are availables: Gnome, Xfce4, Lxde (coming soon for KDE)

## Logs
Take a look in **/var/log/archboot/**
