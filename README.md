#              vlmh

#  (VOID LINUX MAINTENANCE HELPER)


![alt text](https://github.com/voider755/vlmh/blob/main/vlmh-12-26crop.jpg?raw=true)

 Gives you a CLI menu with some common maintenance options inside a Void Linux system

This program may help you with doing some common system maintenance. It's pretty straightforward, just type the number of your option and whatever is (if it's) prompted, and let it do its thing. As of this version, it uses ```xbps``` and ```vkpurge```, so it will be useful only inside a Void Linux system (and I guess in some Void Linux derivative[s]).

INSTALLATION: Only thing apart from ```base-system``` you'll need installed is ```python3```. Download or ```git clone``` this repository. Move the full directory or (at least) the ```vlmh.py``` archive to a location of your preference if necessary, and run it with:

```$ python vlmh.py```

There's no need to make the archive executable, the Python interpreter should run it as it is.
You can of course add an ```alias``` to your ```$SHELL```. Say you use ```bash```, then in ```.bashrc```:

```alias vlmh='python3 /full_path_to_the_archive/vlmh.py'```

Then just type ```vlmh``` (or whatever alias you prefer to use), an it should run.

If you want to make it executable to get rid of the ```python3``` prefix, just use ```chmod u+x /path/to/almh.py``` or whatever, and it will run typing full path to the archive, or, inside the containing directory, with:

```./vlmh.py```

- vlmh (Void Linux Maintenance Helper) is (c) Voider 2020 // 
 Contact me: voider (at) disroot.org or as "invoider" at mastodon dot social // 
 Code first published at https://invoider.wordpress.com/2020/12/25/vlmh-void-linux-maintenance-helper/ . Now hosted at https://github.com/voider755/vlmh // 
 License: FreeBSD(-like) License. Use at your own risk // 
 Void Linux is Copyright 2020 VoidLinux contributors & Copyright 2008-2018 Juan RP and contributors // 
 Linux(R) is a registered trademark of Linus Torvalds // 
 This project is totally independent and in no way affiliated with Void Linux and/or Linux, but is indebted to all the FOSS projects that add up to that fine OS.
