#              vlmh

#  (VOID LINUX MAINTENANCE HELPER)




 vlmh (Void Linux Maintenance Helper) is (c) Voider 2020

 Contact me: voider (at) disroot.org or as "invoider" at mastodon dot social

 Code first published at https://invoider.wordpress.com/2020/12/25/vlmh-void-linux-maintenance-helper/ . Now hosted at https://github.com/voider755/vlmh

 License: FreeBSD(-like) License. Use at your own risk

 Void Linux is Copyright 2020 VoidLinux contributors & Copyright 2008-2018 Juan RP and contributors

 Linux(R) is a registered trademark of Linus Torvalds

 This project is totally independent and in no way affiliated with Void Linux and/or Linux

 Gives you a menu with some common maintenance options inside a *stock* Void Linux system


This program may help you with doing some common system maintenance. It's pretty straightforward, just type the number of your option and whatever is (if it's) prompted, and let it do its thing. As of this version, it uses xbps and vkpurge, so it will be useful only inside a Void Linux system (and I guess in some Void Linux derivative[s]).


DISCLAIMER: This is an alpha release. I'm no coder, just trying to learn some Python and did this as a learning experience. I'm releasing this because a) it seems to work, and I think someone may find it useful, and more important b) because someone may check the code, point where it's wrong, and help me improve it. In any case, you better check the code before using this and USE AT YOUR OWN RISK.


INSTALLATION: I don't think there's really a need to install it. You just need Python (it works with the current version inside Void official repositories) and, of course, a Void Linux (or maybe a derivative) installed. If it's outside of $PATH, just open your terminal emulator, navigate to the directory where the archive is contained, and type:


$ python3 vlmh.py


There's no need to make the archive executable, the Python interpreter should run it as it is.


You can of course add an alias to your $SHELL, say you use bash, then in .bashrc:


alias vlmh='python3 /full_path_to_the_archive/vlmh.py'


Then just type vlmh (or whatever alias you prefer to use), an it should run.
