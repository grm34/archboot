![](http://i.imgur.com/z4nv4Kj.png)

## Requirements

The only thing you need is an **USB bootable device** of ArchLinux and a HDD dedicated for the installation.

- Instructions for Windows: *https://rufus.akeo.ie/*

- Instruction for Linux : *https://wiki.archlinux.fr/Cr%C3%A9er_une_clef_USB_avec_l%27ISO_Arch_Linux*

## Usage

1. Reboot your computer, open Boot Selection Menu and select the USB bootable device.

2. Select **Boot Arch Linux (x86_64)** : *https://raw.githubusercontent.com/grm34/archboot/master/img/archlinux.png*

3. Set AZERTY keyboard by running this command :

    `loqdkeys fr`

4. Download Archboot and follow the instructions :

    `wget https://raw.githubusercontent.com/grm34/archboot/master/archboot && sh archboot`

## Desktop Environment

During the installation, you can choose if you want or not to install a desktop environment.
For now only this ones are availables: Gnome, Xfce4, Lxde (coming soon for KDE)

## Logs
Take a look in **/var/log/archboot/**
