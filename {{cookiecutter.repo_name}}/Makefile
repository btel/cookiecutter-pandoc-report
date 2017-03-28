all: {{cookiecutter.filename}}.pdf

{{cookiecutter.filename}}.pdf : {{cookiecutter.filename}}.md
	pandoc -t latex $< -o $@ --bibliography bibliography.bib --csl apa.csl --filter pandoc/pandoc-svg.py
