# arch-postinstall

# NIRUCON-ALPI: Arch Linux Post-Install

Welcome to the **NIRUCON-ALPI** post-installation script, tailored for Arch Linux users who want a streamlined setup focused on suckless software, noir theming, and tools for music recording and media production. This script is designed to automate the setup process (with Y/n questions) of a custom environment with essential software and configurations. It’s built around my own preferences but is free for anyone to use at their own risk.

Note: I am not particularly knowledgeable or skilled in bash scripting or programming, so this script and related scripts have been created to the best of my ability. There are certainly many things that could be improved, and I will likely discover them myself as well.

## Table of Contents

1. [Overview](#overview)
2. [Installation Steps](#installation-steps)
3. [Optional Configurations](#optional-configurations)
4. [Suckless Installation](#suckless-installation)
5. [Noir Theme and Icons](#noir-theme-and-icons)
6. [Contact](#contact)

## Overview

This script automates the installation and configuration of:

- Essential base programs and system optimizations
- A variety of suckless software (like dwm, dmenu, slock and st)
- Noir-themed aesthetics and icons
- Various applications for music production, media editing, development and more...

**Disclaimer:** This script is tailored for my specific setup and preferences. While it is free to use and modify, it is provided as-is, and I disclaim all responsibility for any issues that may arise. Proceed with caution and at your own risk.

## Installation Steps

1. **Base Programs Installation**
   - Installs `git`, `wget`, and the AUR helper `yay` (if not installed).
   - Essential system optimizations and updates.

2. **Essential Package Installation**
   - Installs core packages like `xorg` and some more of my needed applications and tools.
   - Adds additional applications from AUR.

3. **Optional Applications**
   - Provides options to install various categories of applications:
     - **Browser**
     - **Music Streaming**
     - **File sync / Nextcloud Client**
     - **DAW Apps**
     - **DAW Plugins**
     - **Web Development Apps**
     - **Image and Video Apps**
     - **Communication Apps**

4. **Custom Grub Theme**
   - Installs a custom GRUB theme to enhance the boot menu appearance.

5. **Suckless Software**
   - Installs and configures suckless software such as DWM, dmenu, and st.
   - Includes custom scripts for enhanced functionality.

6. **Noir Theme and Icons**
   - Installs noir themes and icons for a stylish, dark appearance.

## Suckless Installation

The script will set up various suckless software with my "noir theming", including:
- **dwm (Dynamic Window Manager)**
- **dmenu (Dynamic Menu)**
- **st (Simple Terminal)**
- **slock (Simple Lock)**

It also installs and configures additional scripts like nirubar-dwm and dotfiles for a customized experience.

nirubar - my status bar for dwm: https://github.com/nirucon/nirubar-dwm

## Noir Theme and Icons

You can optionally install:
- **Equilux Theme:** A dark GTK theme.
- **Papirus Dark Grey Icons:** A dark icon theme.
- **Rofi Theme:** A dark Rofi theme for enhanced aesthetics.

## Contact

For any questions or feedback, feel free to contact me at: [n@rudolfsson.net](mailto:n@rudolfsson.net)
