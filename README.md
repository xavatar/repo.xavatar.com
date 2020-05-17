# repo.xavatar.com

INFORMATION: These were built against glibc 2.31

Repo: https://repo.xavatar.com

Wine Staging Option Compilation : https://github.com/Frogging-Family/wine-tkg-git/blob/master/wine-tkg-git/customization.cfg

Proton-TKG Option Compilation: https://github.com/Frogging-Family/wine-tkg-git/blob/master/proton-tkg/proton-tkg.cfg

## How install this repo (Arch Linux - Manjaro ) :

In one command : 
- echo -e "\n[repo.xavatar.com]\nSigLevel = Optional TrustAll\nServer = https://repo.xavatar.com" | sudo tee -a /etc/pacman.conf
- sudo pacman -Syu

## How install Proton Build :

- For regular Steam users, create a ~/.steam/root/compatibilitytools.d directory.
- For Flatpak Steam users, create a ~/.var/app/com.valvesoftware.Steam/data/Steam/compatibilitytools.d/ directory.

- For regular Steam users, extract the release tarball into ~/.steam/root/compatibilitytools.d/.
- For Flatpak Steam users, extract the release tarball into ~/.var/app/com.valvesoftware.Steam/data/Steam/compatibilitytools.d/.
- Restart Steam.
- Right click any game in Steam and click Properties.
- At the bottom of the General tab, Check Force the use of a specific Steam Play compatibility tool, then select the new Proton version.
- Launch the game.


