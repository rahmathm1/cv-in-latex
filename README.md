## LaTeX Resume

These directories present a CV template made with LaTeX.

## Installing LaTeX

On Ubuntu

    sudo apt-get install texlive texlive-xetex

On Mac

    wget -c http://mirror.ctan.org/systems/mac/mactex/mactex-basic.pkg.zip

You can install additional packages also

    wget -c http://mirror.ctan.org/systems/mac/mactex/mactex-additions.mpkg.zip

For complete TeX distribution (1.8GB)

    wget -c http://mirror.ctan.org/systems/mac/mactex/MacTeX.mpkg.zip

## Compiling

Just go to `cv-rahmathullah-latex/` and run

    make

## Windows

    Install MikeTex from https://miktex.org/. Make sure its added to the evn variables.

    Use `pdflatex cv-rahmathullah-m.en.tex` to generate pdf file from tex file.
