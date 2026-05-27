# artix-ports
Artix Linux software ported from Arch Linux

To enable this repository on Artix Linux, add the following section to `/etc/pacman.conf`:
```
[artix-ports]  
SigLevel = PackageOptional
Server = https://github.com/SuperSonic65535/artix-ports/raw/refs/heads/main/
```
Then, run "`sudo pacman -Sy`" to sync the database.
