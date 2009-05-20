harden
======

harden is a small script that will turn a symbolic link (symlink) into
a "real" copy of the file, i.e. "hardening" it.  It defaults to creating
another hard link to the symlink destination, but can also copy it.
Symlinks that point to a directory cannot have multiple hard links created
to them, and will be recursively copied instead.

harden is licensed under the [WTFPL](http://sam.zoy.org/wtfpl/).

Enjoy,

- [Andre Pang](mailto:ozone@algorithm.com.au)

