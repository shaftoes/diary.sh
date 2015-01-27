# diary.sh

diary.sh is a fork of Diary-f which is a fork of the diary program written by
Jamie Briggs. The program's homepage was http://sourceforge.net/projects/diary/
and http://gitub.com/earshinov/diary-f/

diary.sh is a console-based diary that leverages the capabilities of
the Unix toolbox, using date, grep, less and a host of others -- as well as
your favorite text editor -- to produce a suprisingly capable tool.

The repository is actually named `.sh` because I tend to name all my
repositories with the relevant extension for the language it is just a small
tool. The executeable is still `diary`, though.

diary.sh is _not_ compatible with prior versions of the diary application.

See diary(1) for a more complete description and a bunch of examples.

## Requirements:

diary.sh (or `diary`) is a shell script that uses a number of common programs.
These include:

   bash, xprop, grep, egrep, cut, sed, cat, chmod, date, cp,
   rm, sort, tail, ls, xargs, and less.

   With my patches it also uses git and gpg.

Diary-f allowed locale's date format in command line arguments representing
dates.  However, to be able to use this feature you had to install a helper
strptime utility. This utility was written in C by `earshinov`
(https://github.com/earshinov/strptime) but I, personally, never used it.
So, this feature will be removed in future, as I won't maintain a fork of the
`strptime` utility.

## Installation:

`diary.sh` is work in progress. You shouldn't install or use it by now.
Installation instructions will be added as soon as it is ready.

## Usage:

See diary(1).

## Reporting bugs:

Please use [the github issue tracker](http://github.com/matthiasbeyer/diary.sh/)

## Acknowledgements

Thanks to Jamie Briggs and Eugene Arshinov for writing this awesome tool!
