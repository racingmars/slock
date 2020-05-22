slock - simple screen locker
============================
simple screen locker utility for X.

Matthew's slock Customizations
------------------------------

This repository contains the build of slock that I use on my desktop. My configuration is in config.h; the config.h.def file is maintained as the defaults as modified by each patch. The following patches from https://tools.suckless.org/slock/patches/ are installed:

 * control clear (Don't trigger red screen on control character input.)

The remainder of this readme is the original slock readme.

Requirements
------------
In order to build slock you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (slock is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install slock
(if necessary as root):

    make clean install


Running slock
-------------
Simply invoke the 'slock' command. To get out of it, enter your password.
