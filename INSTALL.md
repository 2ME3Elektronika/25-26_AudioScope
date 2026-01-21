# Installation Guide

## Prerequisites

- Raspberry Pi 4 with Raspberry Pi OS (32-bit or 64-bit)
- Internet connection for downloading dependencies
- SSH access or direct terminal access
- Hardware assembled according to HARDWARE.md
- SD card with atleast 8gb free space

## Start Of The Installation
## Step 1
### Installation of a OS in the SD card
To be able to start coding in python, firstly, it is needed to have a sd card with atleast 8gb of space to install inside the Raspbian OS.
(https://www.raspberrypi.com/software/operating-systems/)

To be able to put the OS in a recognizable way for the Raspberry we will use Raspberry Pi Imager.
(https://www.raspberrypi.com/software/)

To know how to do it you can follow the instructions of the following video.
(https://www.youtube.com/watch?v=wgJLSu5wAnY)

## Step 2
### Instalation of Python3 in Raspberry
Before starting to code, first we will need to have Python3 installed in the Raspberry. To do that we will need to use the following lines inside of the terminal.
-     sudo apt-get install -y git python3-dev python3-pillow cython3
