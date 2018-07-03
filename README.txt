				  LOGO Library
		       Rudá Moura <ruda.moura@gmail.com>


INTRODUCTION

LOGO Library is a PostScript library to describe graphics with
commands derived from the LOGO language, more specifically,
you can use this library to draw with a subset of the “turtle” LOGO commands.

LOGO Library is in Public Domain.


FILES

The LOGO Library is all included in ‘LOGOLib.ps’ file. All other
PostScript files (*.ps) are examples that maybe teach you 
something about the library.


USAGE

PostScript (PS) is largely available in many platforms and printers.

On macOS, the Preview Application is able to convert the PostScript file
to the PDF format. On the command line, use ‘pstopdf’ to convert to PDF.

On Linux and Windows is recommended to install GhostScript and GhostView.
GhostScript is the PostScript interpreter and GhostView is the viewer application.

Now this is how you use the library (LOGOLib.ps):

Create a PostScript file and include the LOGO Library content. Use the LOGO-like commands to draw and finally use ‘showpage’ when it is done.

Here is how to draw a Square with size 50 points in the middle of the page.

%%% Copy the LOGO Library here! %%%

50 forward
90 right
50 forward
90 right
50 forward
90 right
50 forward
90 right

showpage


REFERENCES

* GhostScript and GhostView. https://www.ghostscript.com/
* PostScript Tutorial by Paul Bourke. http://paulbourke.net/dataformats/postscript/
* Logo Foundation: Logo Programming. http://el.media.mit.edu/logo-foundation/what_is_logo/logo_programming.html
* Berkeley Logo User Manual. https://people.eecs.berkeley.edu/~bh/usermanual


Last updated: July 3, 2018
