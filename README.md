cornell-beamer
==============

A LaTeX Beamer template for presentations at Cornell University.

Setup
-----

Edit the <code>config/metainfo.tex</code> file to include
* your name,
* the title and subtitle of your presentation and 
* the presentation date.

Compiling the Source Code
-------------------------
Use `pdflatex` and `bibtex` to generate a presentation.
If you use [Texmaker](http://www.xm1math.net/texmaker/), you can include the following command to automatically compile the sources: 
<code>pdflatex -synctex=1 -interaction=nonstopmode %.tex | bibtex % | pdflatex -synctex=1 -interaction=nonstopmode %.tex 
| pdflatex -synctex=1 -interaction=nonstopmode %.tex</code>

If you prefer the command line you can comfortably run the <code>make</code> script.

Dependencies
-------------------------

* Your favourite and up-to-date LaTeX compiler. 
* Optional: GNU Make for the compile script.

Thanks to
-------------------------

* Marcel Grossmann, who initially created the PresTeX template at University of Bamberg. https://github.com/uniba-ktr/PresTeX
* Linus Dietz, who added the Makefile and this nice REAMDE. https://github.com/lynyus/VU_PresTeX
