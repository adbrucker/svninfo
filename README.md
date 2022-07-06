# svninfo

Version 0.7.4, 23 March 2010

## Description

This package is used to extract the revision and file information provided
by the [Subversion](http://subversion.apache.org/) revision control system.

To maintain different versions of a document or to keep track on the development of one,
the document is kept under a revision control system like SCCS, CVS, or Subversion.
This LaTeX package assumes you are using the Subversion system. To present the version
information of a document, one needs to extract it from some kind of text inserted by
the revision control system. Subversion offers therefore the `Id` keyword, which is
expanded by the Subversion update command and contains a lot of useful information.
This information is made available through this package. The information obtained
from the expanded string are:

* The filename,
* the revision number,
* the date and time of the last Subversion co command, and
* name of the user who has done this action.

For each of these items a macro is defined. When updating a file, the Subversion
keywords should be contained in the updated source. Further, one has to set the
Subversion property for keyword expansion of that file, e.g.

```LaTeX
svn propset svn:keywords "Id" svninfo.dtx
```

## Installation

To install: unpack and

```shell
    make
```

or execute the commands manually:

```shell
    latex svninfo.ins     // creates the file of this package
    latex svninfo.dtx     // create the package documentation
```

The following files are created by 'latex svninfo.ins'

```shell
 svninfo.cfg
 svninfo.sty
 svninfo.perl
 svninfo.init
```

then copy the files

```shell
    svninfo.sty
    svninfo.cfg
```

to a place where LaTeX can find it, e.g.,

```shell
    $HOME/tex/inputs
```

and set the environment variable

```shell
    TEXINPUTS=$HOME/tex/inputs//:$TEXINPUTS
```

## License

This program can be redistributed and/or modified under the terms of the LaTeX
Project Public License Distributed from CTAN archives in directory
macros/latex/base/lppl.txt; either version 1.3c of the License, or (at your
opinion) any later version.

You are allowed to distribute this file under the condition that it is
distributed together with all the following files:

```shell
   svninfo.ins
   svninfo.dtx
   Makefile
   README
```

If you receive only some of these files from someone, complain!

SPDX-License-Identifier: LPPL-1.3c+

## Master Repository

The master git repository for this project is hosted by the [Software
Assurance & Security Research Team](https://logicalhacking.com) at
<https://git.logicalhacking.com/adbrucker/svninfo>.
