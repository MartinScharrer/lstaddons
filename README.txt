LaTeX bundle 'lstaddons'
~~~~~~~~~~~~~~~~~~~~~~~~
Copyright (c) 2011-2024 by Martin Scharrer <martin.scharrer@web.de>
CTAN: http://www.ctan.org/pkg/lstaddons
Code repository: https://github.com/MartinScharrer/lstaddons/

This bundle contains a small collections of add-on packages for
the 'listings' package.
These packages patch internal macros to provide additional features
to 'listings'.

The add-ons are so far:


lstlinebgrd
~~~~~~~~~~~
Provides 'linebackground' options for 'lstlisting' which
can be used to color the background of each line of the listing.
The use of conditionals which depend on the line number is supported,
which allows zebra-effects etc.

This package was originally written in response to the question
"Creating a zebra effect using listings"
(http://tex.stackexchange.com/q/18969/2975).


lstautogobble
~~~~~~~~~~~~~
Provides an 'autogobble=true|false' option for 'listing' which will set the
standard 'gobble' option to the indention of the first line. This allows
people to indent their listings code in the source file without having to 
use a suitable value for 'gobble' themselves.

This package was originally written in response to the question
"How to automatically skip leading white spaces in listings"
(http://tex.stackexchange.com/q/19953/2975)


INSTALLATION
============
Run 'tex lstaddons.ins' to extract all package files.
Compile all .dtx files with pdflatex to produce the package manuals.
Copy the files to the following subdirectories of your TEXMF tree:

  *.sty         => tex/latex/lstaddons/
  *.dtx *.ins   => source/latex/lstaddons/
  *.pdf README  => doc/latex/lstaddons/

Finally update your TeX file list by running 'texhash' or similar tool.

