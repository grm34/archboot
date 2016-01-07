![](http://i.imgur.com/z4nv4Kj.png)

**Install ArchLinux the way i like! [FR]**

## Usage :

**1. Boot from ArchLinux iso [ *http://mir.archlinux.fr/iso/latest* ] & run:**

`wget https://drones-technologies.com/arch/install_arch && sh install_arch`

**2. After reboot, for full desktop environment (XFCE/LXDM), login & run:**

`wget https://drones-technologies.com/arch/install_xfce && sh install_xfce`

**N'JOY !**

## XFCE Desktop Environment

**VGA Driver**

`xf86-video-* [ATI/INTEL/NVIDIA/VESA] arandr`

**Desktop Environment**

`ntp htop hardinfo xfce4 xfce4-goodies lxdm lxdm-themes
xorg-server xorg-xinit xorg-server-utils grub2-theme-archlinux`

**File System**

`gamin gvfs gvfs-mtp gvfs-nfs gvfs-afc gparted ntfs-3g
dosfstools exfat-utils file-roller ifuse usbmuxd fuseiso gcdemu rar`

**Fonts**

`artwiz-fonts font-bh-ttf font-bitstream-speedo
ttf-bitstream-vera ttf-liberation ttf-freefont ttf-dejavu
gsfonts sdl_ttf ttf-cheapskate ttf-arphic-uming ttf-baekmuk
ttf-inconsolata ttf-ms-fonts xorg-fonts-type1`

**Multimedia**

`pulseaudio pulseaudio-alsa gstreamer0.10-good pavucontrol
gecko-mediaplayer vlc guvcview gtk-recordmydesktop gtkpod mediainfo`

**Printer - Scanner**

`cups cups-pdf ghostscript gutenprint sane simple-scan`

**Desktop Tools**

`galculator ffmpegthumbnailer xscreensaver fbreader
epdfview masterpdfeditor pinta gimp libreoffice libreoffice-fr`

**Network**

`network-manager-applet networkmanager-openvpn wireless_tools`

**Bluetooth** (if detected)

`bluez bluez-utils gnome-bluetooth`

**Web Navigator**

`firefox firefox-i18n-fr flashplugin jre8-openjdk icedtea-web jdk`

**Network Tools**

`teamviewer10 skype transmission-gtk google-earth`

**Games**

`playonlinux gnome-chess gnuchess`

**G33k Tools**

`sshfs sublime-text-dev filezilla hexchat giteye
virtualbox virtualbox-guest-iso virtualbox-ext-oracle`

**Login screen**

![](http://i.imgur.com/VocvAKK.png)

## Notes

**install_arch** install ArchLinux base system with grub2, you are not
forced to used **install_xfce** which install full desktop environment.
