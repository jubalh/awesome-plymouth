# Plymouth

Awesome resources for [Plymouth](https://www.freedesktop.org/wiki/Software/Plymouth/) (graphical boot animation).

## Language
* [Introduction to the Plymouth scripting language](https://www.freedesktop.org/wiki/Software/Plymouth/Scripts/)
* [Guide to creating custom Plymouth themes Pt1](http://brej.org/blog/?p=158)
* [Guide to creating custom Plymouth themes Pt2](http://brej.org/blog/?p=174)
* [Guide to creating custom Plymouth themes Pt3](http://brej.org/blog/?p=197)
* [Guide to creating custom Plymouth themes Pt4](http://brej.org/blog/?p=238)

## Usage

### Installing a theme
Put the folder containing your theme in `/usr/share/plymouth/themes/`.

### Previewing a theme

List all installed themes:
```
plymouth-set-default-theme -l
```

Set a theme:
```
plymouth-set-default-theme themename
```

Display the currently set theme for 5 units:

```
plymouthd
plymouth --show-splash ; for ((I=0; I<5; I++)); do sudo plymouth --update=test$I ; sleep 1; done; plymouth quit
```

### Setting a theme

Call it with `-R` to rebuild initrd:

```
plymouth-set-default-theme -R themename
```

## Themes
* [Arch-Wireframe-Plymouth-Theme](https://github.com/dreamsmasher/Arch-Wireframe-Plymouth-Theme)
* [anonymous](https://github.com/offensive-hub/plymouth-anonymous)
* [arch-beat](https://github.com/nenad/arch-beat)
* [breeze-plymouth](https://github.com/KDE/breeze-plymouth)
* [geko-plymouth-theme](https://gitlab.com/z-ray-entertainment/geko-plymouth-theme)
* [iss-sunrise](https://github.com/shwaybotx/iss-sunrise)
* [macbuntu](https://github.com/rizwansoaib/macbuntu)
* [nsa-plymouth](https://github.com/skd1993/nsa-plymouth)
* [piramide](https://github.com/darkshram/piramide)
* [pisi-color](https://github.com/prdsmehmetstc/pisi-color)
* [plymouth-bgrt](https://github.com/darac/plymouth-bgrt)
* [PlymouthTheme-Cat](https://github.com/krishnan793/PlymouthTheme-Cat)
* [plymouth-theme-anarchistos](https://github.com/AnarchistOS/plymouth-theme-anarchistos)
* [plymouth-theme-aperture](https://github.com/irth/plymouth-theme-aperture)
* [plymouth-theme-bgrt-mi](https://github.com/openmindead/plymouth-theme-bgrt-mi)
* [plymouth-theme-hamara](https://tracker.debian.org/pkg/plymouth-theme-hamara)
* [plymouth-theme-opensuse-beat](https://github.com/jubalh/plymouth-theme-opensuse-beat)
* [plymouth-theme-scp](https://github.com/TechCiel/plymouth-theme-scp)
* [plymouth-theme-simple-image/](https://github.com/barskern/plymouth-theme-simple-image)
* [rpi3plymouth](https://github.com/naens/rpi3plymouth)
* [ubntu darwin](https://github.com/ashutoshgngwr/ubuntu-darwin)
* [watch-dogs](https://github.com/1BB3/watch-dogs)

## Theme collections
* [adi1090x plymouth-themes](https://github.com/adi1090x/plymouth-themes)
* [hrishabh23 plymouth-themes](https://github.com/hrishabh23/plymouth-themes)
* [gnome-look.org](https://www.gnome-look.org/browse/cat/108/order/latest/)
