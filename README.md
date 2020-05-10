# st - simple terminal
Build of the simple terminal emulator for X.

### Requirements
In order to build st you need the Xlib header files.

### Installation
Edit config.mk to match your local setup (st is installed into the /usr/local namespace by default).
Afterwards enter the following command to build and install st (if necessary as root):
```sh
 # make clean install
```

### Patches
Scroll-back, translucency, dynamic sizing
