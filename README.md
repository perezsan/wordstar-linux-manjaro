# wordstar-linux-manjaro-isotools
Wordstar Linux manjaro-tools repo

git clone manjaro-isotools, then duplicate an i3 dir that's in the community folder. 
Lastly, overwrite new folder with this project, and everything should work.

So this new hodge podge should be in ~/iso-tools/community/wordstar

Add whatever-the-fuck to desktop-overlay dir

Make sure you have ran **pamac install manjaro-tools**, then copy
over /etc/manjaro-tools/manjaro-tools.conf to **~/.config/manjaro-tools/**

Edit ~/.config/manjaro-tools/manjaro-tools.conf judiciously ... my only change is the kernel, which is **linux54** as o 3/18/2020.

now run **buildiso -p wordstar**

I know--a shitty hack.
I'll fix later perhaps, but I just wanted to keep the scripts separate from this release. (And all these files are slightly outdated--will ned to upload latest soon.)

A full, working distro can be downloaded from here: [Wordstar Linux 19.02 Manjaro](https://healingrant.com/heaviside/wordstar-linux/)
