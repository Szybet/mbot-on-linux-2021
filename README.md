# mbot-on-linux-2021
Simple guide to program the mBot on linux
## 1. Using the web browser
First, install the mlink

the newest are here: https://dl.makeblock.com/mblock5/linux/mLink-1.2.0-1.el7.x86_64.rpm
- .DEB: https://dl.makeblock.com/mblock5/linux/mLink-1.2.0-amd64.deb
- .RPM: https://dl.makeblock.com/mblock5/linux/mLink-1.2.0-1.el7.x86_64.rpm
- AUR: https://aur.archlinux.org/packages/mlink/ - Tested and its working

Then go to one of those websites:
- https://ide.mblock.cc - to program using blocks and cpp. Its not advertised anywhere, its possible that it will be shutted down, but for now it works
- https://ide.makeblock.com - to program using blocks and python

surprisingly, the bluetooth - usb stick that comes with the mBot works out of the box and its clever designed. Its detected by linux as a ch341-uart device, not a bluetooth card.

## 2. Using Arduino IDE ( or any other IDE, like platformio )
- First, install the library: https://github.com/Makeblock-official/Makeblock-Libraries
- Then set the Arduino uno as the board, and Parallel Programmer as the programmer.

Thats it!
