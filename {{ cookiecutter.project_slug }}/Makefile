.PHONY: all clean view

all: {{ cookiecutter.project_slug }}.pdf

{{ cookiecutter.project_slug }}.pdf : {{ cookiecutter.project_slug }}.md {{ cookiecutter.bib_file }}
	pandoc {{ cookiecutter.project_slug }}.md -o {{ cookiecutter.project_slug }}.pdf --bibliography={{ cookiecutter.bib_file }} --filter pandoc-citeproc --pdf-engine=xelatex -V CJKmainfont="Noto Serif CJK TC"


view: {{ cookiecutter.project_slug }}.pdf
	evince {{ cookiecutter.project_slug }}.pdf

clean:
	rm -f {{ cookiecutter.project_slug }}.pdf
