# i3wm-polybar-arc-dark

This is a leightweight window manager configuration using i3-gaps, i3-radius, and polybar.

![screenshot](https://github.com/fallow24/i3wm-polybar-arc-dark/blob/main/screenshot.png?raw=true)

## Get started

I configured this on a fresh Ubuntu 20.04.3 LTS x86_64 on Linux 5.13.0-27-generic.

However, the programms used such as ==polybar==, ==i3-radius==, ==i3-gaps==, ==compton==, ==lxappearance==, or ==arandr== are available in many other Distros, either from source or from the repositories.

```console
foo@bar:~$ sudo add-apt-repository ppa:regolith-linux/release
foo@bar:~$ sudo apt update && sudo apt install i3-gaps
foo@bar:~$ sudo apt install dkms libdrm-dev cmake cmake-curses-gui build-essential libboost-all-dev libuv1 libuv1-dev libcurl4 libcurlpp-dev libcurl4-openssl-dev libiw30 libpulse-dev libpulse0 libxcb-composite0-dev libasound2-dev libxcb-util0-dev libxcb-image0-dev pkg-config python3-sphinx python3-packaging libuv1-dev libcairo2-dev libxcb1-dev libxcb-util0-dev libxcb-randr0-dev libxcb-composite0-dev python3-xcbgen xcb-proto libxcb-image0-dev libxcb-ewmh-dev libxcb-icccm4-dev libjsoncpp-dev rofi pywal fonts-font-awesome compton compton-conf lxappearance fonts-jetbrains-mono libgtk-3-dev arc-theme arandr 
foo@bar:~$ git clone https://github.com/firecat53/networkmanager-dmenu.git && cd networkmanager-dmenu/ && sudo cp networkmanager_dmenu /usr/bin/
```

