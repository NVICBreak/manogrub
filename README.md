# manogrub - A manosaba style GRUB theme

> This work is a fan-made derivative of the MagicGirl WitchTrials (魔法少女ノ魔女裁判).
> 
> I directly used and slightly modified the original in-game assets.If this infringes on your copyright, please contact me — I sincerely apologize!
> 
> The original series is owned by Re,AER.

## Information

**manogrub** was designed for the 1920x1080 resolution.

## Preview

<img src="/pics/example.png" width="50%"> 

(This preview picture is created in Photoshop because I can not take a screenshot in GRUB and it may differ slightly from the actual appearance)

## Installation Giude

1. Download & Unzip

2. Copy folder into grub themes directory `sudo cp -r manogrub /usr/share/grub/themes`

3. Edit grub file `sudo vim /etc/default/grub`

4. Add the theme to the bottom of the text file `GRUB_THEME="/usr/share/grub/themes/manogrub/theme.txt"`

5. Update grub `sudo grub-mkconfig -o /boot/grub/grub.cfg`

6. Reboot your computer

## Others...

This is my first time independently creating a GRUB theme.Please feel free to share any thoughts or advice if you notice something that could be improved!
