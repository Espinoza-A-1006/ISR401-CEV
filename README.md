# ISR401-CEV

Repositorio del grupo CEV para las actividades de Ingeniería de
Requerimientos (ISR-401) de la Universidad Técnica Estatal de Quevedo.

## GA-PRAC-01 · Comparación de modelos de proceso de requisitos

**Primer avance — C1.** Caracterización de los modelos en cascada,
iterativo e incremental, y ágil. Se describen sus fases o ciclos,
sus supuestos y las condiciones en las que conviene aplicarlos.

### Archivos

| Archivo | Contenido |
|---|---|
| `GA-PRAC-01/main.tex` | Informe del primer avance |
| `GA-PRAC-01/referencias.bib` | Bibliografía del informe |
| `GA-PRAC-01/main.pdf` | PDF compilado del primer avance |

### Compilación

El archivo principal es `main.tex`. Se requiere una distribución LaTeX
con `pdfLaTeX`, `Biber`, `biblatex` y el estilo `biblatex-ieee`.

Desde la raíz del repositorio, ejecuta:

```sh
cd GA-PRAC-01
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```

En Overleaf, selecciona `main.tex` como documento principal,
usa **pdfLaTeX** y pulsa **Recompilar**.

**Siguiente avance:** C2, matriz comparativa aplicada al escenario
o a los escenarios que confirme el docente.
