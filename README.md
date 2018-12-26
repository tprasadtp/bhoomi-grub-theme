# Bhoomi Grub2 Theme

This theme is based on [Vimix](https://github.com/vinceliuice/grub2-themes/tree/master/grub-theme-vimix) Grub2 theme.

[![https://github.com/tprasadtp/bhoomi-grub-theme](https://img.shields.io/github/license/tprasadtp/bhoomi-grub-theme.svg?style=for-the-badge)](![https://github.com/tprasadtp/bhoomi-grub-theme)

## Installation

To install this,
1. Download the [Zip file](https://github.com/tprasadtp/bhoomi-grub-theme/archive/master.zip).
2. Unpack it to your working directory.
3. Copy **ONLY** the contents of folder `bhoomi` to `/boot/grub/themes/bhoomi`
    ```console
        sudo mkdir -p /boot/grub/themes/bhoomi
        sudo cp ./bhoomi-grub-theme/bhoomi /boot/grub/themes/bhoomi/
    ```
4. Open default Grub config as `root`
    ```console
        sudo nano /etc/default/grub
    ```
5. Change (or add if not already present) the following lines & save the file.
    ```console
        # Theme Modifications for file /etc/default/grub
        GRUB_THEME="/boot/grub/themes/bhoomi/theme.txt"
        GRUB_BACKGROUND="/boot/grub/themes/bhoomi/background.jpg"
    ```
6. Re-generate Grub config. `sudo update-grub` or `sudo grub-mkconfig -o /boot/grub/grub.cfg` the output should show, theme and background are found, if not check your config and files.
7. Reboot!

## Problems?

[Open an issue.](https://github.com/tprasadtp/bhoomi-grub-theme/issues/new)

## Changes from the original

Removed Install scripts, Changed fonts to Ubuntu Regular and changed background. 
Please do not upload this to Gnome-Looks website without changing at-least name of the theme.

## Why Bhoomi?

[ಭೂಮಿ](https://kn.wikipedia.org/wiki/%E0%B2%AD%E0%B3%82%E0%B2%AE%E0%B2%BF) in [Kannada/ಕನ್ನಡ](https://en.wikipedia.org/wiki/Kannada) means "Earth", you know [the pale blue dot](https://en.wikipedia.org/wiki/Pale_Blue_Dot) we live on. 

[![Analytics](https://ga-beacon.prasadt.com/UA-101760811-3/github/prasadt?pixel&useReferer)](https://prasadt.com/google-analytics-beacon)
