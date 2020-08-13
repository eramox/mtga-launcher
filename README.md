
![GitHub Logo](data/magic_logo.jpg)

<p align="center"><i>"Magic The Gathering is a collectible and digital collectible card game created by Richard Garfield. Released in 1993 by Wizards of the Coast.</i>"
</p>


**Download: [mtga-appimage](https://github.com/linux-ott/mtga-appimage/releases/tag/mtga-appimage)**

No wine installation required

## Dependencies

### Arch
```
sudo pacman -S wget
```

### Debian/Ubuntu/elementaryOS
```
sudo apt install wget
```

## Install Magic

To install, run ``install_magic.sh`` and do not change the folder-paths on Windows

```
./install_magic.sh
```

Installation directory ```$HOME/.local/apps/magic```

## Run Magic

```
cd $HOME/.local/apps/magic
./Wine-4.21-x86_64.AppImage run magic-bottle
```

## Update

```
cd $HOME/.local/apps/magic
./update.sh
```

**Download: [mtga-version](https://mtgarena.downloads.wizards.com/Live/Windows32/version)**

## Winetricks

```
cd $HOME/.local/apps/magic
./Wine-4.21-x86_64.AppImage --winetricks magic-bottle
```

## Sources
**[Wine32-AppImage](https://github.com/sudo-give-me-coffee/wine32-deploy)**

**[MTGA-Installer](https://mtgarena.downloads.wizards.com/Live/Windows32/versions/3009.800581/MTGAInstaller_0.1.3009.800581.msi)**