# Conky theme
This сonky theme automatically determines the distribution name, version, and displays them along with the logo. If the distribution is not known, the Tux is displayed.
Recognizable distributions: Debian, Linux Mint, Ubuntu, Fedora, Arch Linux.

This theme has been tested on:
- Debian 9.9
- Experimental Ubuntu 19.10
- Elementary OS 5.0 Juno 
- Fedora 30 (need "yum install redhat-lsb")

This theme has been created using source code:
- Jesse Avalos https://www.deviantart.com/speedracker/art/Side-thin-conky-Made-for-Conky-Manager-513212857

Used fonts:
- NanumGothic Bold
- clock2017R_v0.2_161128

![screen](https://github.com/RamasyaR/rt_conky/blob/master/screenshot/screenshot.jpg)

### Installation and run:
```sh
$ git clone https://github.com/RamasyaR/rt_conky.git
$ cp -r ./rt_conky/fonts/* ~/.local/share/fonts
$ fc-cache -f -v
$ cp -R ./rt_conky/ ~/.conky/
$ conky -c ~/.conky/rt_conky/conkyconfig 
```
