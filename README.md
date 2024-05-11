# ChineseMarkdown
Cookiecutter template for Markdown Chinese article with references

This works on Linux.

---

## Install

Requires the following:
- cookiecutter Python package
- pandoc
- pandoc-citeproc
- xelatex
- Chinese font (in this case, "Noto Serif CJK TC")
- PDF reader

See the Makefile for details on how the Markdown file is compiled.

## Use

1. On the command line, run `cookiecutter gh:agentlans/ChineseMarkdown`
2. Answer the questions.
3. Have your Markdown file in the newly-made directory.
4. Then in that directory, run `make` to compile the Markdown file
5. Use `make view` to see the produced PDF file.

## Author, Licence

By Alan Tseng 2024

Creative Commons Zero v1.0 Universal
