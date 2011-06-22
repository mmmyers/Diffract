Diffract
========

Diffract is a simple, free GUI diff/merge tool for MacOS X (and eventually
others!).

I originally started this project because I noticed a distinct lack of good,
free GUI diff/merge tools for Mac OS X.  The ones I could find were either
not very useful, or a bit expensive.  There are some ported over from Linux,
but they tend to be a pain to get working, and don't look so great either.
So I decided to help remedy this problem.

Among other things, the tool should support both side-by-side and unified 
views, 3-way merges, in-line editing for merges, syntax highlighting, and
custom font/color schemes.

The project is being developed primarily for MacOS X, but the intention is to
make the base code as platform-independent as possible.  This way, I can bridge
in platform-specific GUI libraries, and make a nice-looking, native GUI version
for the three major platforms.  This is also a good excuse to learn a number of
different GUI libraries for different platforms.  However, if I can't quite 
accomplish this, it's going to stay a MacOS X exclusive.

Diffract is licensed under the [GPL], and written in C++.

[GPL]: http://www.gnu.org/licenses/gpl.html
