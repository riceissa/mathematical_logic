# Introduction

This is a project to convert Detlovs and Podnieks's notes on mathematical logic to LaTeX.
The notes are available here: http://www.ltn.lv/~podnieks/mlog/ml.htm

The original notes are protected under a Creative Commons Attribution-NonCommercial-ShareAlike 1.0 Generic (CC BY-NC-SA 1.0) license, so that is the license we will use.

# Download

Currently there are no PDFs available.

# Compile

The file `make.tex` is the main file, and all of the other files are simply sources from there using LaTeX's `\input{...}` command.
So to compile, just use the following:
    pdflatex make.tex
(More than one compile may be necessary to get the references right.
An alternative is to use `latexmk make.tex`.)