# PiezoOS
An Operating System made from scratch!
PiezoOS currently is coded in x86 Assembly, It has a built in kernel, bootloader, FAT12 file system which can read and write and everything (almost) is made-from-scratch
# Testing/Installation
First off you need these packages installed:
```
make nasm qemu-system bochs bochsbios vgabios
```
Secondly, To compile and create the .img file run this:
```
make
```
Once it's done, go to the build file and run
```
qemu-system-i386 main_floppy.img
```
# Docs
For the docs, please read the Documentation file or visit my Tor/I2P site
inspired by nanobyte

