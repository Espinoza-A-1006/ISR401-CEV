# ISR401-CEV

Repositorio del grupo CEV para las actividades de Ingeniería de
Requerimientos (ISR-401) de la Universidad Técnica Estatal de Quevedo.

## GA-PRAC-01 · Comparación de modelos de proceso de requisitos

El informe caracteriza los modelos en cascada, iterativo e incremental,
y ágil. El segundo avance incluye las matrices comparativas, las
recomendaciones y los riesgos de dos escenarios: la extractora de aceite
de palma y la aplicación de pedidos de comida típica. También incluye
los actores y el marco de ingeniería de requisitos aplicados a la extractora.

### Archivos del informe

| Archivo | Contenido |
|---|---|
| [`GA-PRAC-01/main.tex`](GA-PRAC-01/main.tex) | Archivo principal del informe en LaTeX. |
| [`GA-PRAC-01/referencias.bib`](GA-PRAC-01/referencias.bib) | Fuentes citadas en el informe. |
| [`GA-PRAC-01/main.pdf`](GA-PRAC-01/main.pdf) | Informe compilado. |

### Compilación

- **Archivo principal:** `GA-PRAC-01/main.tex`.
- **Compilador:** pdfLaTeX.
- **Dependencias:** una distribución LaTeX con Biber y los paquetes
  `babel` con soporte para español, `lmodern`, `geometry`, `array`,
  `tabularx`, `xltabular`, `fancyhdr`, `xcolor`, `hyperref`, `biblatex`
  y el estilo `biblatex-ieee`.
- **Bibliografía:** `referencias.bib` debe estar en la misma carpeta
  que `main.tex`.

Desde la raíz del repositorio, ejecuta estos comandos en orden:

```sh
cd GA-PRAC-01
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```

El PDF se genera como `GA-PRAC-01/main.pdf`.

En Overleaf, selecciona `main.tex` como documento principal y
**pdfLaTeX** como compilador. Pulsa **Recompilar** y comprueba que
aparezcan las dos fuentes en la sección **Referencias**.
