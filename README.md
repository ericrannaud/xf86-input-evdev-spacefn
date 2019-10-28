This is modified from Ljosa's work: instead of emitting the MENU keycode
when Space is held, emit LVL3.

This fork provides an implementation of SpaceFn in xf86-input-evdev.

    "The SpaceFN layout: trying to end keyboard inflation"
    https://geekhack.org/index.php?topic=51069.0

The idea of SpaceFn is to let the space key work as both a regular
space and a modifier. For more information about the implementation
and how to build, install, and configure it, see
http://www.ljosa.com/~ljosa/software/spacefn-xorg/.

------------------------------------------------------------------------

xf86-input-evdev - Generic Linux input driver for the Xorg X server
-------------------------------------------------------------------

All questions regarding this software should be directed at the
Xorg mailing list:

  https://lists.x.org/mailman/listinfo/xorg

The master development code repository can be found at:

  https://gitlab.freedesktop.org/xorg/driver/xf86-input-evdev

Please submit bug reports and requests to merge patches there.

For patch submission instructions, see:

  https://www.x.org/wiki/Development/Documentation/SubmittingPatches

