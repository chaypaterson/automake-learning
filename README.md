Test C project for learning automake
====================================

This project contains a C program, C library, and C header. There is a
Makefile.am and a configure.ac needed to set up the GNU Autotools packaging
system.

The Makefile.am is non-recursive.

Steps:

* Run `autoreconf --install` to generate a `configure` script.
* `mkdir build && cd build`
* `../configure`
* `make && make dist`

This will result in a tarball that contains the project.

Dependencies:
* GNU Autotools
