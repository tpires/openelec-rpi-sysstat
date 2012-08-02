openelec-rpi-sysstat
====================

SYSSTAT utilities as add-on for OpenELEC Raspberry Pi.

1) Clone this project to where you want to.
2) Copy sysstat directory to OpenELEC.tv/packages/sysutils (or other)
3) At OpenELEC.tv directory do:
    $ PROJECT=RPi ARCH=arm ./scripts/create_addon sysstat
4) This will create an add-on on OpenELEC.tv/target/addons
5) Copy it to Download network share
6) Install it from XBMC Add-ons -> Install from zip

That's all folks.