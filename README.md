# Hyprland-Scripts
My Hyprland Scripts
Base: Cachy-OS

Hyprland Script used: https://github.com/prasanthrangan/hyprdots

Tools Used:

AUR helper: yay, paru
sudo pacman -S yay-bin paru

Apps: brave-bin, an-anime-game-launcher-bin, nautilus, nautilus-admin, gnome-software
1) paru -S brave-bin nautilus nautilus-admin gnome-software 
2) yay -S an-anime-game-launcher-bin

Gaming Packages used : Cachy OS meta packages.
sudo pacman -S cachyos-gaming-meta

Utilities : Hyprlock, Hyprshade, Hypridle.

rEFind thenes: https://github.com/martinmilani/rEFInd-theme-collection
// Matrix Theme is cool though

Wallpapers from wallpaperflare.com

Terminal Used: Kitty(font size = 16)

Also, some flatpak packages are used:
Boxes, Warehouse, Flatseal, Mission Center(Can use Resources as well).

Spotify Customization from Spicetify
From this guy on github:https://github.com/boudywho/spicetify-arch-installation-guide 
// I have noticed that if you use Arch, the AUR packages will open *slightly faster than flatpak. (*obervation)

//As of now, I am still in a confused state to completely switch to Linux. Its fun but complatibility issues are still there, especially for NVIDIA. I hope it will be solved.

// I have made some minor changes to keybindings, these are somewhat similar to windows. 
** I had fun using hyprland. 

Waybar scaling problem: If you want to change the size of waybar, do not change it in the style.css from the waybar directory. This will be temporary and will return to the original state after any change in orientation or closing it.
1) Instead, go to .config/waybar/modules/ and use nano style.css. Here, change the minimum height( I used 20px)
    **Note: Idk why but changing the font sixe variable here messes the waybar. 


Basic Tips that I learnt by experimenting:
0) nano command is used to edit the files in the .config folder or any file extension through terminal.
1) No need to click buttons to turn off, just use reboot for restart and poweroff for shutdown in terminal.
2) to go root, type sudo -i
3) you can use touch to create any file in any dierctory in the terminal.
4) Also, you can use cp /path to copy /path to paste in terminal(copy). Same goes for mv(move)
5) To create a folder, use mkdir -p name in the directory you want to create a folder in terminal.
6) To remove, you can use rm file name. rm -rf deletes all the files in the directory.
7) If you want to create,edit in the directories of root, you need to put sudo before the command in order to perform the task or else the file will be read-only.
8) The AUR helpers:
a) -S is used to install the packages.
b) -R is used to remove the packages without the data.
c)-Rcns is used to completely remove data.
9)When you are downloading anything, just amke sure to review the packages. If they are trusted, then press Q to accept changes.
10) In kitty terminal, Ctrl+Shift+C is used to copy and Ctrl+Shift+V for paste.
