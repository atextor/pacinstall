Slackware users probably know [Checkinstall](http://asic-linux.com.mx/~izto/checkinstall/):
When installing software from source archives, you call checkinstall instead of make install,
which automatically creates a packgage and installs it, so that you can easily
deinstall it later. pacinstall is the same thing for Arch Linux, you can install software
from sources the quick way without needing to write a PKGFILE.

A binary package will be created and installed, no PKGFILE will be generated.

You need installwatch, which can be installed by the following command:

	pacman -Sy installwatch
