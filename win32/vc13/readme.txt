this file: [Scribus root]/win32/vc13/readme.txt

This directory holds files relating to building Scribus with  Microsoft 
Visual Studio 13 Express ("vc13").  As of March, 2016, the main 
development for Windows for Scribus is performed by Jean Ghali on 
Visual Studio 11 ("vc11").

Files in this directory are to allow one to use the vc11 directory with
vc13.

Vc13 has a different compiler than vc11 so sometimes files that compile
under vc11 do not under vc13.  Usually these incompatabilities are due
to minor changes in the standards.  For example: "min" and "max" functions
now require the header file algorithm.h in vc13 and some of the projects
in the libraries do not account for this change.

