# sox

This is an unofficial fork (well, more a distribution) of [sox], which I'm maintaining mainly for any patches and build
system changes needed to make libsox work with [URY playd].

## Changes

- Visual Studio 2013 project for building libsox as a shared library;
- Quick-fixed upstream bug with `sox_seek` failing to change the internal position;

## Bugs

Report bugs _here_ if, and only if, they pertain to changes made on this fork.
Else, report them [upstream][sox].

## Legal

See `LICENSE.LGPL` and `LICENSE.GPL`.

[sox]: http://sourceforge.net/p/sox/
[URY playd]: https://github.com/UniversityRadioYork/ury-playd
