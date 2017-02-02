# LaTeX-Two-Column-One-Page-Resume
One page two column resume template using XeTeX typesetting engine https://en.wikipedia.org/wiki/XeTeX . This program allows you to take a .tex file, compile it, and produce a pdf.  The .tex file contains the content as text and related commands to format it accordingly. Original source for template was https://github.com/deedy/Deedy-Resume . From deedy source changed '.xtx' file extension to '.tex'. Verified to compile with XeLaTeX on Linux.

##Instructions

###Install XeLaTeX on Linux

Using terminal:

$ apt-get install texlive	% this package gives most tex packages needed ~550Mb

$ apt-get install texlive-xetex

### How Produce pdf from .tex File

Navigate to directory with .tex file that contains your resume information

$ xelatex -filename.tex-

In the directory the pdf will be found