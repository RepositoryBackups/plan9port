> Imported from https://code.google.com/archive/p/plan9port on 17/08/2016.
> 
> **website** folder contains local copy of the project website - https://swtch.com/plan9port/
> 
> Further Info-
> 
> 1. https://swtch.com/plan9port/
> 1. https://code.google.com/archive/p/plan9port/
> 
> Original URL which lead me to this repository-
> - http://code.swtch.com/plan9port/src/0e6ae8ed3276/src/lib9/sendfd.c
> - https://code.swtch.com/plan9port/src/0e6ae8ed3276/src/lib9/sendfd.c
> 
> The original REAMDE follows <br />
--- 

This is a port of many Plan 9 libraries and programs to Unix.
 
* Installation

To install, run ./INSTALL.  It builds mk and then uses mk to
run the rest of the installation.  

For more details, see install(1), at install.txt in this directory
and at http://swtch.com/plan9port/man/man1/install.html.

* Documentation

See http://swtch.com/plan9port/man/ for more documentation.
(Documentation is also in this tree, but you need to run
a successful install first.  After that, "9 man 1 intro".)

Intro(1) contains a list of man pages that describe new features
or differences from Plan 9.

* Helping out

If you'd like to help out, great!  The TODO file contains a small list.

If you port this code to other architectures, please share your changes
so others can benefit.

Please use diff -u or CVS (see below) to prepare patches.

* CVS

You can use CVS to keep your local copy up-to-date as we make 
changes and fix bugs.  See the cvs(1) man page here ("9 man cvs")
for details on using cvs.

* Contact

Russ Cox <rsc@swtch.com>
