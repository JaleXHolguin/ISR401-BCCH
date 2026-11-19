# Compilación

- **Compilador:** pdfLaTeX y BibTeX.
- **Archivo principal:** `EXP-1/main.tex`.
- **Dependencias:** Beamer, Babel (español), TeX Gyre Heros, csquotes, biblatex y biblatex-ieee.

Desde la raíz del repositorio:

```sh
cd EXP-1
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```
