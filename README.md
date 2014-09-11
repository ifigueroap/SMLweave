SMLweave
========

A filter for literate programming in Standard ML (SML), based on
noweb. It uses smlnjtrans to generate target files with the evaluation
of arbitrary SML programs.

* Installation

You must have the following commands in your executable path:

* smlnjtrans, available at http://alleystoughton.us/smlnjtrans/
* noweave, part of the Noweb literate programming tool, available at
  http://www.cs.tufts.edu/~nr/noweb/

Additionally, you must set the NOWEB_LIB environment variable to the
location of the markup and mnt executables from noweb. In the Brew
installation of noweb in OS X, NOWEB_LIB =
/usr/local/Cellar/noweb/2.11b/lib.

After the requisites are met, simply copy the smltrans, smlweave and
smlnotangle scripts into any location you want, for instance /usr/local/bin. 

