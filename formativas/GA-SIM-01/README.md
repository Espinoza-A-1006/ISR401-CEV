# GA-SIM-01 — Simulación de priorización y negociación entre roles

Asignatura: Ingeniería de Requerimientos (ISR-401).
Caso: Inscripciones universitarias.

## Estado del documento

Estructura inicial con títulos y tablas vacías.
Los resultados se incorporarán después de realizar la actividad.

## Archivos

- `main.tex`: archivo principal del informe.
- `main.pdf`: PDF generado a partir de `main.tex`.
- `referencias.bib`: archivo reservado para las referencias; todavía no está conectado al documento.
- `README.md`: instrucciones de compilación.

## Compilador y dependencias

Compilador: pdfLaTeX.

Para compilación local se necesita MiKTeX o TeX Live con los paquetes:

`inputenc`, `fontenc`, `babel` con soporte para español,
`geometry`, `lmodern`, `xcolor`, `colortbl`, `array`,
`tabularx`, `longtable`, `fancyhdr` e `hyperref`.

La versión actual no requiere ejecutar BibTeX ni Biber.

## Compilación local

Desde la raíz del repositorio, ejecutar en este orden:

```powershell
cd "formativas/GA-SIM-01"
pdflatex -interaction=nonstopmode -halt-on-error main.tex
pdflatex -interaction=nonstopmode -halt-on-error main.tex
```

El resultado se genera en `formativas/GA-SIM-01/main.pdf`.

Si la compilación informa un error, debe corregirse antes de
considerar actualizado el PDF.

## Compilación en Overleaf

1. Crear un proyecto vacío.
2. Subir `main.tex`.
3. Seleccionar `main.tex` como documento principal.
4. Seleccionar pdfLaTeX como compilador.
5. Pulsar Recompilar.
6. Descargar el PDF y guardarlo como
   `formativas/GA-SIM-01/main.pdf`.

El archivo `main.tex` del repositorio debe coincidir con el utilizado
en Overleaf.

## Actualización de estas instrucciones

Cuando se incorpore el procesamiento de la bibliografía, se actualizarán
las dependencias y el orden de compilación.