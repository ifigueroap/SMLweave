SMLweave
========

A filter for literate programming in Standard ML (SML), based on
noweb. It uses smlnjtrans to generate target files with the evaluation
of arbitrary SML programs.

Installation
------------

You must have the following commands in your executable path:

* smlnjtrans, available [here](http://alleystoughton.us/smlnjtrans).
* noweave, part of the Noweb literate programming tool, available at
  [here](http://www.cs.tufts.edu/~nr/noweb/).
* gawk, the GNU awk implementation. I'm using this because I could not
  find how to capture groups in a regular expression using OSX's
  default awk program.

Additionally, you must set the NOWEB_LIB environment variable to the
location of the markup and mnt executables from noweb. In the Brew
installation of noweb in OS X, NOWEB_LIB =
/usr/local/Cellar/noweb/2.11b/lib.

After the requisites are met, simply copy the smltrans, smlweave and
smlnotangle scripts into any location you want, for instance
/usr/local/bin.

Usage
----------------------------------

TO DO

Integration with latexmk
-

TO DO 
