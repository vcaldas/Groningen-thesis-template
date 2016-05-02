Using the template
------------------

This PhD thesis template was heavily based on the TU Delft dissertation template.
You can download the original template at:
https://intranet.tudelft.nl/services/communicatie/handleidingen/handleiding-huisstijl/downloads/

I used this template for my dissertation and will slowly write instructions on how to use. 
The same guidelines for the TU Delft teplate are valid and kept here as reference.

If you are interested in using the template, I will be happy to speed up the documentation.

Enjoy,
Victor

To compile, run: 

  pdflatex dissertation
  bibtex chapter-1/chapter-1
  pdflatex dissertation
  pdflatex dissertation

Installation on Windows
-----------------------

This dissertation template has been tested to work with the most recent version
of MiKTeX at the time of this writing (2.9). The following packages are required
on top of a basic MiKTeX installation to make full use of the template:

  caption, fancyhdr, filehook, footmisc, fourier, l3kernel, l3packages,
  lettrine, metalogo, mptopdf, ms, natbib, pgf, realscripts, tipa, titlesec,
  tocbibind, unicode-math, url, xcolor, xetex-def

Note that MiKTeX will generally automatically install these packages if they are
missing from your installation.

To install MikTex, just download it from here: http://miktex.org/download

I like to use TexStudio - a Latex Editor: http://www.texstudio.org/


Installation on Linux (Debian/Ubuntu)
-------------------------------------

Recent versions of Debian, and derived distributions such as Ubuntu, use the TeX
Live system. Install the following packages to make full use of the this
template:

  texlive, texlive-fonts-extra, texlive-math-extra, texlive-lang-dutch,
  texlive-lang-english, texlive-latex-extra, texlive-xetex

