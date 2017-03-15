# Archlinux U Instalacion

Instala y configura archlinux has never been easier!

You can try it first with a `virtualbox`

## Prerequisitos

- A working internet connection
- Logged in as 'root'

## How to get it
### With git
- Incrementar cowspace partición: `mount -o remount,size=2G /run/archiso/cowspace`
- Instalar Paquete desde repositorio git: `pacman -Sy git`
- get the script: `git clone git://github.com/jutamara90/archos`

### Without git
- get the script: ` wget https://github.com/jutamara90/archos/tarball/master -O - | tar xz`
    - an alternate URL (for less typing) is ` wget http://bit.ly/NoUPC6 -O - | tar xz`
    - super short `wget ow.ly/wnFgh -O aui.zip`

## How to use
- FIFO [sistema base]: `cd <dir> && ./1-fifo`
- LILO [El resto]: `cd <dir> && ./2-lilo`

## 1-FIFO SCRIPT
- Configurar Teclado
- Seleccionar editor
- Configurar Lista de Replicas Automaticamente
- Crear particion
- Formatear Dispositivos
- Instalar Sistema Base
- Configurar fstab
- Configurar hostname
- Configurar timezone
- Configurar hardware clock
- Configurar locale (IDIOMA)
- Configurar mkinitcpio
- Instalar/Configurar bootloader
- Configurar mirrorlist
- Configurar contraseña root

## 2-LILO SCRIPT
- Copia de todos los archivos Modificados
- Instalar repositorios adicionales
- Crear y configurar nuevo usuario
- Instalar y configurar sudo
- Habilitar automaticamente servicios en systemd
- Instalar an AUR Helper [yaourt, packer, pacaur]
- Instalar base system
- Instalar systemd
- Instalar Preload
- Instalar Zram
- Instalar Xorg
- Instalar GPU Drivers
- Instalar CUPS
- Instalar Firmware Adicionales wireless/bluetooth
- Ensuring access to GIT through a firewall
- Instalar DE o WM [Cinnamon, Enlightenment, FluxBox, GNOME, i3, KDE, LXDE, OpenBox, XFCE]
- Instalar herramientas Desarrollo [Vim, Emacs, Eclipse...]
- Instalar Aplicaciones Office [LibreOffice, GNOME-Office, Latex...]
- Instalar Herramientas Sistema [Wine, Virtualbox, Grsync, Htop]
- Instalar Aplicaciones Graficas [Inkscape, Gimp, Blender, MComix]
- Instalar Aplicaciones Internet [Firefox, Google-Chrome, Jdownloader...]
- Instalar Aplicaciones Multimedia [Rhythmbox, Clementine, Codecs...]
- Instalar Juegos [HoN, World of Padman, Wesnoth...]
- Instalar Fonts [Liberation, MS-Fonts, Google-webfonts...]
- Instalar y configurar servidores Web
- Mucho Mas...
 :)
