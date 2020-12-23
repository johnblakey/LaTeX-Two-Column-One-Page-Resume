# LaTeX-Two-Column-One-Page-Resume
One page two column resume template using XeTeX typesetting engine https://en.wikipedia.org/wiki/XeTeX, which allows you to take a .tex file, compile it, and produce a pdf.  The .tex file contains the content as text and related commands to format it accordingly.

The original source for template was https://github.com/deedy/Deedy-Resume .

## Instructions

### Install XeTeX on Debian

####Terminal Commands

$ apt install texlive

$ apt install texlive-xetex

### Produce pdf from .tex File

Navigate to directory with .tex file that contains your resume information

$ xelatex <filename.tex>

Outputs pdf in the same directory