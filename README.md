# I3wm
- Core programs
	- i3-gaps - a fork of i3wm with more features, including gaps
	- i3status - generates status bar to use with i3bar
	- dmenu - for searching applications
	- i3exit - exit-script for i3
	- i3blocks - Define blocks for your i3bar status line (make new scripts executable: chmod)
		- sysstat - display CPU usage
- Screen
	- Xorg-xrandr - used for managing monitors
	- Xorg-xbacklight - used for managing screen brightness
	- Arandr - provides a simple visual front end for XRandR
	- Compton - compositor manager that may fix tearing issues
	- Feh - image viewer for setting background images
	- Redshift - adjusts the color temperature of your screen
	- [Dunst] - notification manager
- Audio:
	- Playerctl - media player controller
	- Read more about setting multimedia buttons: https://faq.i3wm.org/question/3747/enabling-multimedia-keys.1.html and this one https://www.reddit.com/r/i3wm/comments/5gnw5y/start_pause_music_with_the_same_key_combination/
	- And changing default sound output (e.g. from monitor to laptop):
https://askubuntu.com/questions/690711/change-sound-output-from-command-line
	- [Volumeicon] - volume control for your system tray
- Screen lock
	- Xautolock - an automatic X screen-locker/screen-saver
- Network manager
	- Network-manager-applet
https://faq.i3wm.org/question/2/how-can-i-use-networkmanager-with-i3.1.html
- Fonts
	- ttf-symbola - for symbols and emoji (restart after installation)
	- For manual instalation (Fontawesome - add `<i></i>` after icon if malformed icons) read this: https://wiki.archlinux.org/index.php/fonts#Manual_installation
-Drivers
	- touchpad: https://wiki.archlinux.org/index.php/Libinput#Common_options

# Arch/Manjaro
- Yaourt
	- In order to install packages from AUR these packages need to be installed: binutils, make, [gcc], pkg-config, fakeroot. Read more: http://manjaro.site/fix-makepkg-error-arch-linux-cannot-find-strip-binary-required-object-file-stripping/
	- In case PGP signatures are needed: https://superuser.com/questions/1210758/error-one-or-more-pgp-signatures-could-not-be-verified-arch-linux
	- Chromium - browser
	- Evolution - mail manager
	- Evolution-ews - MS Exchange integration through Exchange Web Services: https://www.eduhk.hk/ocio/content/faq-configure-evolution-access-office-365
	- Fish - Smart and user friendly shell intended mostly for interactive use
	- Fisher - plugin manager
	- Vim - a highly configurable text editor
- Optional programs
	- Htop - Interactive process viewer
	- Ranger - a simple, vim-like file manager
	- Xclip - Command line interface to the X11 clipboard
	- archey3 - Output a logo and various system information

# Guides:
- How to enable spell check: go to Manjaro Settings Manager -> Language Packages and choose a spell checker: hunspell
- Configuration example with scripts - https://github.com/walshc/i3






