![# Anemone3DS](https://github.com/astronautlevel2/Anemone3DS/blob/master/meta/banner.png)

A Theme and Splashscreen Manager for the Nintendo 3DS, written in C.\
To-do list here: https://trello.com/b/F1YSa1VK

# Dependencies
 * devkitPro, which can be installed following the instructions [here](https://devkitpro.org/wiki/Getting_Started).
 * zlib, jansson, and libarchive, which can be retrieved from [devkitPro pacman](https://devkitpro.org/viewtopic.php?f=13&t=8702).
 * A recent build of [makerom](https://github.com/profi200/Project_CTR) and the latest release of [bannertool](https://github.com/Steveice10/bannertool). These must be added to your PATH.  
 A 64-bit Windows binary of makerom is available [here](https://hm892.s-ul.eu/U0Irkqih).
 * ~~[pp2d](https://github.com/BernardoGiordano/pp2d), which is included in the repo if you do a git clone --recursive.~~  
 Due to circumstances surrounding the privacy settings on the pp2d repo, the source files are now included directly within the repo.
 * Git needs to be on your PATH (this is usually only manual under Windows).

# Building
First of all, make sure devkitPro is properly installed and added to your PATH.  
After that, open the directory you want to clone the repo into, and execute  
`git clone https://github.com/astronautlevel2/Anemone3DS` (or any other cloning method).  
To install zlib, jansson and libarchive, begin by following the instructions found above ([here](https://devkitpro.org/viewtopic.php?f=13&t=8702)) on the devkitPro forums, and then install the dkP packages `3ds-zlib`, `3ds-jansson` and `3ds-libarchive`.  
After also adding [makerom](https://github.com/profi200/Project_CTR) and [bannertool](https://github.com/Steveice10/buildtools) to your PATH, just enter your directory and run `make`. All built files will be in `/out/`.

# License
This project is licensed under the GNU GPLv3. See LICENSE.md for details. Additional terms 7b and 7c apply to this project.

# Credits
The following people contributed to Anemone3DS in some way. Without these people, Anemone3DS wouldn't exist, or wouldn't be as good as it is: [CONTRIBUTORS.md](CONTRIBUTORS.md)

Most of the icons under `romfs` are from the site [icons8.com](https://icons8.com) and are licensed under the [CC-BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/3.0/)

Special thanks go to these people who, whilst not directly contributing, helped immensely:
 * [Rinnegatamante](https://github.com/Rinnegatamante), whose code served as reference on theme installation.
 * [SteveIce10](https://github.com/SteveIce10), whose QR code in FBI was essential.
 * [BernardoGiordano](https://github.com/BernardoGiordano) for making pp2d, and being super responsive to feature requests and just general help.
 * [yellows8](https://github.com/yellows8) for his home menu extdump tool, which was invaluable in debugging.
 * the folks on #dev of Nintendo Homebrew, who helped with unicode shenanigans (especially [Stary2001](https://github.com/Stary2001), [Fenrir](https://github.com/FenrirWolf), and DanielKO).
 * the maintainers for all used libraries, including but not limited to ctrulib, zlib, citro3d, pp2d, and quirc.
 * all the people who helped keep me going and motivated me to work. This includes, but is definitely not limited to:
 
   + The members of the [Nintendo Homebrew Discord](https://discord.gg/C29hYvh)
   + The members of the __Secret Shack Service Discord__   
   + The members of the [ThemePlaza Discord](https://discord.gg/2hUQwXz)
