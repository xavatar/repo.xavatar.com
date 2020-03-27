# repo.xavatar.com

Repo : https://repo.xavatar.com

Patch Wine Staging : https://github.com/Tk-Glitch/PKGBUILDS/blob/master/wine-tkg-git/customization.cfg

Patch Proton : https://github.com/Tk-Glitch/PKGBUILDS/blob/master/proton-tkg/proton-tkg.cfg

## Build available (Arch Linux - Manjaro ) :

 - wine-tkg-staging-fsync-vkd3d-git-5.4.r12.ge5da84dc-256-x86_64.pkg.tar.xz
 
 - vulkan-icd-loader-git-1.2.135.r4.gcc481ef27-1-x86_64.pkg.tar.xz
 - vulkan-headers-tkg-git-1.2.136.r0.g0e78ffd-1-any.pkg.tar.xz
 - lib32-vulkan-icd-loader-git-1.2.135.r4.gcc481ef27-1-x86_64.pkg.tar.xz
 
 - vkd3d-tkg-git-1.1.r689.ga59f198-1-x86_64.pkg.tar.xz
 - lib32-vkd3d-tkg-git-1.1.r689.ga59f198-1-x86_64.pkg.tar.xz
 
 - mesa-tkg-git-20.1.0_devel.121583.1351ee03352-1-x86_64.pkg.tar.xz
 - lib32-mesa-tkg-git-20.1.0_devel.121583.1351ee03352-1-x86_64.pkg.tar.xz
 
 - spirv-tools-tkg-git-2020.2.r1.gfd773eb5-1-x86_64.pkg.tar.xz
 - lib32-spirv-tools-tkg-git-2020.2.r1.gfd773eb5-1-x86_64.pkg.tar.xz
 
 - faudio-tkg-git-20.03.r11.g311eed5-1-x86_64.pkg.tar.xz
 - lib32-faudio-tkg-git-20.03.r11.g311eed5-1-x86_64.pkg.tar.xz
 
 - mingw-w64-binutils-2.34-1-x86_64.pkg.tar.xz
 - mingw-w64-crt-7.0.0-1-any.pkg.tar.xz
 - mingw-w64-headers-7.0.0-1-any.pkg.tar.xz
 - mingw-w64-winpthreads-7.0.0-1-any.pkg.tar.xz
 - mingw-w64-gcc-9.3.0-1-x86_64.pkg.tar.xz
 

## How install this repo (Arch Linux - Manjaro ) :

In one command : 
- echo -e "\n[repo.xavatar.com]\nSigLevel = Optional TrustAll\nServer = https://repo.xavatar.com" | sudo tee -a /etc/pacman.conf
- sudo pacman -Syu
