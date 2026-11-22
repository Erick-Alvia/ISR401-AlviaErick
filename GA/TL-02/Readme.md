# GA-TL-02 FORM: entrevista estructurada y design thinking

Actividad formativa de Ingeniería de Requerimientos (ISR-401), UTEQ. PFC: Fabro-Arriendos.

## Contenido de esta carpeta

- `main.tex`: archivo principal (guion corregido, consentimiento, registro del ensayo, mapa de empatía, definición del problema, ajustes, declaración de IA).
- `references.bib`: referencias en estilo IEEE.
- `main.bbl`: bibliografía ya generada (permite compilar aunque no se ejecute `bibtex`).
- `figuras/mapa-empatia.jpeg`: figura del mapa de empatía.
- `MANIFIESTO.md`: nombre de archivo, fecha, duración y SHA-256 de las evidencias privadas.
- `main.pdf`: PDF compilado.

## Cómo compilar

Compilador: `pdflatex` con `bibtex` (TeX Live o MiKTeX). Desde esta carpeta (`GA/TL-02`):

```
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

El archivo principal es `main.tex` y el resultado es `main.pdf`.

## Dependencias

Paquetes de LaTeX: babel con soporte para español, lmodern, microtype, geometry, xcolor, array, tabularx, booktabs, longtable, graphicx, amssymb, fancyhdr, titlesec, enumitem, hyperref. Estilo bibliográfico `IEEEtran.bst`.

En Debian o Ubuntu: `sudo apt install texlive-latex-extra texlive-lang-spanish texlive-publishers texlive-bibtex-extra`. MiKTeX instala los paquetes que faltan al compilar.

## Datos personales

El audio del ensayo y el consentimiento firmado no están en este repositorio. Están en una carpeta institucional privada (@uteq.edu.ec) compartida con el docente. Aquí solo se registran en `MANIFIESTO.md`.
