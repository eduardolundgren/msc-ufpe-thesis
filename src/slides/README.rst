CIN - Beamer Presentation Template
==================================

UFPE CIn version of LaTeX Beamer presentation template derived from Andreas Kloeckner's brown-beamer template:

http://mathema.tician.de/software/brown-beamer

Dependencies:
-------------
* latex-beamer class 3.0.7 (http://latex-beamer.sourceforge.net)
* texlive-latex 2008+ (http://www.tug.org/texlive/)
* automake (optional, used to run pdflatex commands)

Install:
--------
Install is simply downloading the code from github. Here we install cin-beamer to $HOME/cin-beamer::

    $ cd $HOME
    $ git clone http://github.com/jtriley/cin-beamer.git

Generating the presentation:
----------------------------
1. Customize cin-beamer/slides.tex to your liking::

    $ vim $HOME/cin-beamer/slides.tex

2. Then change to the cin-beamer directory and run make to generate a presentation PDF::

    $ cd $HOME/cin-beamer
    $ make

3. You can then view the resulting pdf, named slides.pdf, in the 'out' directory::

    $ xpdf $HOME/cin-beamer/out/slides.pdf

4. You can also use make to do this automatically with either xpdf, okular, or acroread::

    $ make view-xpdf
    $ make view-okular
    $ make view-acroread

5. The above "make view-*" commands will automatically build $HOME/cin-beamer/out/slides.pdf if necessary
