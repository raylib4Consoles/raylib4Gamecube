# Install for Gamecube
- Install last devkitpro follow steps from https://github.com/extremscorner/pacman-packages#readme
- clone this repository and execute if you are in Unix like environtment including wsl2:
```
./gamecubebuild.sh
```

# Samples
- in each sample use make to build
```
% cd samples
% ls
shapes
% cd shapes
% ls
logo_raylib_anim
% cd logo_raylib_anim
% ls
Makefile  source  
% make
raylib.c
linking ... logo_raylib_anim.elf
output ... logo_raylib_anim.dol
```
- I have a picoboot with memorycard with sd in port 0 and a gecko usb in port 1 for logs. Also an ethernet compatible device to upload to sd from host. You can execute dol from swiss in your gamecube or use Dolphin emulator.


Enjoy!!!!

