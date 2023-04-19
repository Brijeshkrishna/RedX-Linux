# RedX-Linux

```
                        ▀████    ▐████▀
██████╗ ███████╗██████╗   ███▌   ████▀
██╔══██╗██╔════╝██╔══██╗   ███  ▐███
██████╔╝█████╗  ██║  ██║   ▀███▄███▀
██╔══██╗██╔══╝  ██║  ██║   ████▀██▄
██║  ██║███████╗██████╔╝  ▐███  ▀███
╚═╝  ╚═╝╚══════╝╚═════╝  ▄███     ███▄
                        ████       ███▄

```
RedX Linux is a Arch-based Linux distribution that is designed for both programmers and normal users alike. With a focus on performance, stability, and security, RedX Linux provides users with a robust platform that is ideal for a wide range of use cases.

# How to build ISO

To build , you need a arch based linux , `it won't work in other distro`


## Setup
### Add the arch mirror

```bash
echo 'Server = https://geo.mirror.pkgbuild.com/$repo/os/$arch' >> /etc/pacman.d/mirrorlist
```

### Update the repo
```bash
sudo pacman -Syuu
```

### Install archiso
```bash
sudo pacman -S archiso
```
### Clone the repo

```bash
git clone https://github.com/Brijeshkrishna/RedX-Linux.git
cd RedX-Linux

```

### Build ISO
```bash
sudo mkarchiso -v .
```
it take time to build iso , iso is located at `./out` 


## How to Install the RedX

### Install the ISO flash tool
```
Install the balenaEtcher
```
flash the iso to a pendrive. 
Reboot the computer , will booting press f12 or f11 (or other based on the your computer ) to go to UEFI boot then select the pendrive , and enjoy the linux

still now , there is no Disktop managers 

Try it out 🥰 
=======
### Try it out 🥰 
>>>>>>> 4e12accbf04e1ac68e822d8409bb605b1ecc3bf1
