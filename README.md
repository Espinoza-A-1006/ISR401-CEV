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
| [GA-PRAC-01/main.tex](GA-PRAC-01/main.tex) | Archivo principal del informe en LaTeX. |
| [GA-PRAC-01/referencias.bib](GA-PRAC-01/referencias.bib) | Fuentes citadas en el informe. |
| [GA-PRAC-01/main.pdf](GA-PRAC-01/main.pdf) | Informe compilado. |

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

## GA-TL-02 · Entrevista estructurada y design thinking

Actividad formativa aplicada al **Sistema para la identificación
temprana de dificultades académicas mediante el análisis de
indicadores de rendimiento estudiantil**.

El avance incluye el contexto y propósito del ensayo, el objetivo
de la entrevista, los roles previstos y un guion de trece preguntas
organizadas en cuatro bloques, con apertura y cierre.

El ensayo se plantea como una simulación académica entre compañeros.
Los resultados se incorporarán después de realizar la entrevista.

### Archivos de la actividad

| Archivo | Contenido |
|---|---|
| [GA/TL-02/README.md](GA/TL-02/README.md) | Descripción de la actividad e instrucciones de compilación. |
| [GA/TL-02/main.tex](GA/TL-02/main.tex) | Archivo principal del documento en LaTeX. |
| [GA/TL-02/main.pdf](GA/TL-02/main.pdf) | PDF de la actividad; debe actualizarse al modificar el archivo fuente. |

### Compilación

- **Archivo principal:** `GA/TL-02/main.tex`.
- **Compilador:** pdfLaTeX.
- **Dependencias:** una distribución LaTeX con los paquetes
  `inputenc`, `fontenc`, `babel` con soporte para español,
  `geometry`, `lmodern`, `xcolor` con la opción `table`,
  `array`, `tabularx`, `enumitem`, `fancyhdr` e `hyperref`.
- **Bibliografía externa:** esta versión no requiere BibTeX ni Biber.

Desde la raíz del repositorio, ejecuta estos comandos en orden:

```sh
cd GA/TL-02
pdflatex -interaction=nonstopmode -halt-on-error main.tex
pdflatex -interaction=nonstopmode -halt-on-error main.tex
```

Si la terminal está en otra carpeta de actividad, vuelve primero
a la raíz del repositorio antes de ejecutar el bloque anterior.

El PDF se genera como `GA/TL-02/main.pdf`. Ambas ejecuciones deben
finalizar correctamente; si la compilación falla, puede permanecer
un PDF anterior.

En Overleaf, carga `main.tex`, selecciónalo como documento principal
y utiliza **pdfLaTeX** como compilador.

### Evidencias y privacidad

La grabación del ensayo y los consentimientos se conservarán en
un espacio privado con acceso restringido al equipo y al docente.
No se publicarán audios, firmas ni datos personales innecesarios
en el repositorio.

La síntesis de respuestas, el mapa de empatía y los hallazgos
deben corresponder a la entrevista efectivamente realizada.

Las instrucciones específicas de esta actividad están en
[GA/TL-02/README.md](GA/TL-02/README.md).