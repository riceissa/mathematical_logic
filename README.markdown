# Introduction

This is a project to convert Detlovs and Podnieks's notes on mathematical logic to LaTeX (with some modifications).
The original notes are available here: http://www.ltn.lv/~podnieks/mlog/ml.htm

# Licensing

The original notes are protected under a Creative Commons Attribution-NonCommercial-ShareAlike 1.0 Generic (CC BY-NC-SA 1.0) license, so that is the license we will use:

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/1.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-nc-sa/1.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/1.0/">Creative Commons Attribution-NonCommercial-ShareAlike 1.0 Generic License</a>.

# Download

Currently there are no PDFs available.

# Compile

The file `make.tex` is the main file, and all of the other files are simply sourced from there using LaTeX's `\input{...}` command.
So to compile, just use the following:

    pdflatex make.tex

(More than one compile may be necessary to get the references right.
An alternative is to use `latexmk make.tex`.)
