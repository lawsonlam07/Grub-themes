# Umbralite Grub Theme
This is my royal-inspired grub theme! The color palette is gold, black and white.

## Preview
<img width="1918" height="1049" alt="image" src="https://github.com/user-attachments/assets/1f1c615b-22ff-4596-a928-162e531cde02" />

## Installation
1. Download the latest `umbralite.zip` from _releases_.
2. Extract the folder into your Grub themes folder (usually `/boot/grub/themes/`).
3. Edit `/etc/default/grub` and set `GRUB_THEME=/boot/grub/themes/umbralite/theme.txt` (or wherever you installed the theme).
4. Remake the config file using `grub-mkconfig -o /boot/grub/grub.cfg` (again, or wherever your config file should be).
5. Reboot and enjoy!

## Additional Info
You can manually edit and create `--class` flags for each menu option to display its corresponding icon and fallbacks. If you set `--class [name]`, then Grub will load `[name].png` as the icon for that option.

As for the names of the options, these can also be edited safely. E.g. "Windows Boot Manager (on /dev/nvme0n1p1)" -> "Windows 11".

## Credits
This is a fork of [Xenlism's Grub Themes](https://github.com/xenlism/Grub-themes), which is in turn a fork of [Vinceliuce's Grub Themes](https://github.com/vinceliuice/grub2-themes).

The fonts used here are:
- Soniano Sans for the menu options.
- Camingo Code for the loading bar.
- Terminux for the terminal.

The background is from [Magnific](https://www.magnific.com/free-vector/realistic-golden-frame_21504267.htm).
