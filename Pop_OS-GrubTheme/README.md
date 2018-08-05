____________________________________________________________________________

Pop_OS theme for Grub2.


Supported languages: Chinese (simplified), English, French, German, Norwegian, Portuguese, Russian, Ukrainian.


I originally made this theme with the fonts that Pop_OS uses, but they didnt look good when I converted them to pf2.. If anyone wants to try them, they are located in the folder 'Pop_OS-GrubTheme-Extras' along with the theme.txt's to match them.

____________________________________________________________________________

Install:

Copy this folder to /boot/grub/themes >
(use 'sudo mkdir /boot/grub/themes' if you dont have 'themes' folder)

Add the following to /etc/default/grub >
(use 'sudo gedit /etc/default/grub')
GRUB_THEME="/boot/grub/themes/Pop_OS-GrubTheme/theme.txt"


Update your grub.cfg >
(use 'sudo update-grub')

If you did everything rite, you will see-
Generating grub configuration file ...
Found theme: /boot/grub/themes/Pop_OS-GrubTheme/theme.txt

Done

____________________________________________________________________________

Created by p0wder (https://github.com/PowderLinux)


Credits:

Andrei Shevchuk (https://github.com/shvchk)
I used his 'Poly-Light' grub theme as a template to make this theme.
(MIT License)

Luis Felipe Sánchez (https://github.com/lfelipe1501)
I used the icons from his 'Atomic-Theme' in this theme.

____________________________________________________________________________
