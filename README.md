# NIRUCON-ALPI: Arch Linux Post Install Script

## Overview
**NIRUCON-ALPI** is an Arch Linux post-installation script tailored for a Suckless DWM setup, noir theming and music/content creation applications etc. This script is designed and maintained by Nicklas Rudolfsson and can be freely used and modified.

## Features
- **Suckless DWM setup**: Installs and configures DWM, dmenu, st, and slock.
- **Noir theming**: Custom themes for GTK, icons, and Rofi.
- **Music and content creation** (optional): Installs DAW apps and plugins.
- **Additional optional packages and software**: Includes installation of various essential packages and optional software.

## Installation
To run the script, ensure you have an active internet connection and execute the following command:

```bash
curl -O https://raw.githubusercontent.com/nirucon/nirucon-alpi/main/nirucon-alpi
chmod +x nirucon-alpi
./nirucon-alpi
```

## Script Breakdown
### Functions
- **check_internet_connection**: Verifies internet connectivity.
- **display_welcome**: Shows a welcome message.
- **confirm_proceed**: Prompts for user confirmation to proceed.
- **install_if_needed**: Installs a package if it's not already installed.
- **install_yay**: Installs the AUR helper `yay`.
- **optimize_pacman_conf**: Configures `pacman.conf` for optimal performance.
- **install_packages**: Installs essential packages using `pacman` and `yay`.
- **install_timeshift_if_btrfs**: Installs `timeshift-autosnap` if `btrfs` filesystem is detected.
- **install_optional**: Installs optional packages based on user choice.
- **install_suckless**: Installs nirucon-suckless-arch and related configurations, scripts and dot-files.
- **install_grub_theme**: Installs a custom GRUB theme.
- **install_themes_icons**: Installs GTK themes, icon themes and Rofi custom themes.

### Main Function
Executes the script by calling the necessary functions in sequence to perform the post-installation tasks.

## Customization
You can customize the script to fit your specific needs by modifying the functions and package lists. Ensure to read through the script and adjust the configurations and package selections accordingly.

## GitHub Repositories Used
The script utilizes various repositories from my [nirucon github repos](https://github.com/nirucon):

- [nirucon-alpi](https://github.com/nirucon/nirucon-alpi)
- [nirucon-suckless-arch](https://github.com/nirucon/nirucon-suckless-arch)
- [nirubar-dwm](https://github.com/nirucon/nirubar-dwm)
- [dunstrc](https://github.com/nirucon/dunstrc)
- [nirucon-dmenu](https://github.com/nirucon/nirucon-dmenu)
- [sverigesradio-dmenu](https://github.com/nirucon/sverigesradio-dmenu)
- [srpod-dmenu](https://github.com/nirucon/srpod-dmenu)
- [srplay-dmenu](https://github.com/nirucon/srplay-dmenu)
- [dwmexit-dmenu](https://github.com/nirucon/dwmexit-dmenu)
- [havamal](https://github.com/nirucon/havamal)
- [wifi-dmenu](https://github.com/nirucon/wifi-dmenu)
- [arch-optimizer-dmenu](https://github.com/nirucon/arch-optimizer-dmenu)
- [nirucon-death-grubtheme](https://github.com/nirucon/nirucon-death-grubtheme)
- [nirucon-rofi](https://github.com/nirucon/nirucon-rofi)

## License

Feel free to use and modify, donate if you want :) https://www.paypal.com/paypalme/nicklasrudolfsson
