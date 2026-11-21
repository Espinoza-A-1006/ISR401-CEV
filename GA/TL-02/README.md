# GA-TL-02 — FORM
## Taller de entrevista estructurada y design thinking aplicados al PFC

### Datos de la actividad

- **Universidad:** Universidad Técnica Estatal de Quevedo.
- **Carrera:** Software.
- **Asignatura:** Ingeniería de Requerimientos — ISR-401.
- **Nivel y paralelo:** Cuarto nivel, paralelo A.
- **Docente:** Gleiston Cicerón Guerrero Ulloa, PhD.
- **Unidad:** Unidad 2. Elicitación y Análisis de Requisitos.
- **Equipo:** CEV.
- **Período:** 2026–2027 SPA.
- **Fecha límite:** 21 de noviembre de 2026, 23:59.

### Integrantes del equipo

- Contreras Chavez Kevin German.
- Espinoza Pivaque Angelo Maximiliano.
- Vaca Romero David Octavio.

La pertenencia al equipo no implica que todos hayan realizado las mismas actividades. La participación efectiva debe registrarse en el informe y corresponder con las evidencias del ensayo y el historial de contribuciones.

### Proyecto de referencia

**Sistema para la identificación temprana de dificultades académicas mediante el análisis de indicadores de rendimiento estudiantil.**

El ensayo se concentra en las tutorías como una forma de acompañamiento ante las dificultades académicas. Explora cómo un estudiante solicita y coordina las sesiones y cómo recupera lo trabajado para continuar su aprendizaje.

### Propósito

Practicar una entrevista estructurada mediante un juego de roles entre compañeros y evaluar la claridad y utilidad de las preguntas.

Las respuestas obtenidas en el ensayo sirven para elaborar el mapa de empatía, definir el problema y proponer ajustes al guion, identificándose expresamente como información obtenida en una simulación académica.

### Contenido del documento

El documento fuente (`main.tex`) y el informe compilado (`main.pdf`) incluyen:

1. Portada y datos informativos.
2. Contexto y propósito del ensayo:
   - Contexto del proyecto (con referencias académicas en formato IEEE).
   - Objetivo de la entrevista.
   - Modalidad y rol del participante.
3. Guion de entrevista estructurada y respuestas de apoyo (`P01`):
   - Apertura y solicitud de consentimiento.
   - Trece preguntas distribuidas en cuatro bloques temáticos (Solicitud y coordinación; Confirmación e información previa; Desarrollo y seguimiento; Dificultades y cierre).
   - Cierre y comprobación de lo comprendido.
4. Registro del ensayo y consentimiento:
   - Fecha, modalidad y participantes (20 de noviembre de 2026, 20:00, Zoom, 9 minutos y 24 segundos).
   - Consentimiento informado y resguardo de datos (LOPDP y carpeta institucional `@uteq.edu.ec` compartida con `gguerrero@uteq.edu.ec`).
   - Identificación de la grabación (`GA-TL-02_P01_audio.m4a`, evidencia `AUD-01`, hash SHA-256) y manifiesto de evidencias.
   - Alcance del registro.
5. Síntesis de respuestas y alcance de los resultados.
6. Mapa de empatía (*¿Qué dice?*, *¿Qué piensa?*, *¿Qué hace?* y *¿Qué siente?*).
7. Definición del problema (usuario, necesidad, hallazgo, enunciado del problema y pregunta *¿Cómo podríamos...?*).
8. Revisión y ajustes del guion (claridad durante el ensayo, mejoras identificadas en la revisión posterior y aplicación de ajustes).
9. Declaración de uso de inteligencia artificial y referencias bibliográficas en formato IEEE.

### Archivos

| Archivo | Descripción |
|---|---|
| `main.tex` | Archivo principal y fuente editable del documento en LaTeX. |
| `main.pdf` | Documento PDF compilado correspondiente a la versión actual de `main.tex`. |
| `README.md` | Descripción de la actividad, contenido e instrucciones de compilación. |

### Requisitos de compilación

- Distribución LaTeX: MiKTeX o TeX Live.
- Compilador: **pdfLaTeX**.
- Archivo principal: **`main.tex`**.
- Codificación del archivo: **UTF-8**.
- Clase: `article`.

Paquetes utilizados:

- `inputenc`
- `fontenc`
- `babel`, con soporte para español
- `geometry`
- `lmodern`
- `xcolor`, con la opción `table`
- `array`
- `tabularx`
- `enumitem`
- `fancyhdr`
- `hyperref`

Esta versión no utiliza imágenes externas ni un archivo `.bib`; las referencias se gestionan directamente mediante `\begin{thebibliography}` en formato IEEE y no requieren ejecutar BibTeX o Biber.

### Compilación desde la raíz del repositorio

Ejecutar los siguientes comandos en orden:

```powershell
cd GA/TL-02
pdflatex -interaction=nonstopmode -halt-on-error main.tex
pdflatex -interaction=nonstopmode -halt-on-error main.tex
