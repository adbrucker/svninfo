# svninfo

Version 0.7.4, 23 March 2010

## Description
This package is used to extract the revision and file information provided
by the subversion revision control system.

## Installation
To install: unpack and
```
    make
```
or execute the commands manually:
```
    latex svninfo.ins     // creates the file of this package
    latex svninfo.dtx     // create the package documentation
```

The following files are created by 'latex svninfo.ins'
```
	svninfo.cfg
	svninfo.sty
	svninfo.perl
	svninfo.init
```

then copy the files
```
    svninfo.sty
    svninfo.cfg
```
to a place where LaTeX can find it, e.g.,
```
    $HOME/tex/inputs
```
and set the environment variable
```
    TEXINPUTS=$HOME/tex/inputs//:$TEXINPUTS
```

## License

This program can be redistributed and/or modified under the terms of the LaTeX
Project Public License Distributed from CTAN archives in directory 
macros/latex/base/lppl.txt; either version 1.3c of the License, or (at your
opinion) any later version.

You are allowed to distribute this file under the condition that it is
distributed together with all the following files:
```
   svninfo.ins
   svninfo.dtx
   Makefile
   README
```
If you receive only some of these files from someone, complain!
