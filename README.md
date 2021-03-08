# Elementary-OS-6-compile-script
This is .sh script that will compile Elementary OS 6 iso for you
This script works only on Ubuntu and Debian based distros! Tested on Elementary OS, Zorin OS 15, Linux Mint Debian Edition. Mac version wasn't tested, be aware

to run this sript do (terminal in the same directory as script):

sudo chmod +x compile_elementary.sh

./compile_elementary.sh



Elementary OS 6 iso will take somewhere beetwen 2.5gb.

iso should be in directory where is install script located. example:

Elementary-OS-compile-script/os/builds/(architecture name)/elementaryos-6.0-daily.(date).iso
    
script will install docker and docker.io.

![Elementary OS Logo](https://github.com/HackZy01/Elementary-OS-6-compile-script/blob/main/images/elementary_logo.png)

macOS alpha version requeirements:

    2010 or newer, with Intel’s hardware Memory Management Unit (MMU).
    at least OS X 10.10 El Capitane. (macOS High Sierra and higher are recommended)
    At least 4 GB of RAM.
    install docker from: https://www.docker.com/products/docker-desktop
