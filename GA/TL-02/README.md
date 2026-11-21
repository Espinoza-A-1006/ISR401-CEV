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

Las respuestas del ensayo servirán para elaborar el mapa de empatía, definir el problema y revisar el guion. Los resultados deben identificarse como información obtenida en una simulación académica.

### Contenido de este avance

El documento fuente incluye:

1. Portada y datos informativos.
2. Contexto y propósito del ensayo.
3. Contexto del proyecto.
4. Objetivo de la entrevista.
5. Modalidad y roles previstos.
6. Guion de entrevista estructurada:
   - Apertura y solicitud de consentimiento.
   - Trece preguntas distribuidas en cuatro bloques.
   - Cierre y comprobación de lo comprendido.

Este avance corresponde a la preparación del ensayo. No acredita que la entrevista haya sido realizada ni contiene resultados obtenidos de una grabación.

### Archivos

| Archivo | Descripción |
|---|---|
| `main.tex` | Archivo principal y fuente editable del documento. |
| `main.pdf` | Documento PDF; debe regenerarse después de modificar el archivo fuente. |
| `README.md` | Descripción de la actividad e instrucciones de compilación. |

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

Esta versión no utiliza imágenes externas ni un archivo `.bib`; por tanto, no requiere ejecutar BibTeX o Biber.

### Compilación desde la raíz del repositorio

Ejecutar los siguientes comandos en orden:

```powershell
cd GA/TL-02
pdflatex -interaction=nonstopmode -halt-on-error main.tex
pdflatex -interaction=nonstopmode -halt-on-error main.tex
```

Las dos ejecuciones deben finalizar correctamente. El resultado se genera como `main.pdf` dentro de `GA/TL-02/`.

Si se produce un error, debe corregirse antes de considerar actualizado el PDF: puede permanecer una versión anterior en la carpeta.

### Compilación desde la carpeta de la actividad

Si la terminal ya está situada en `GA/TL-02/`, ejecutar únicamente:

```powershell
pdflatex -interaction=nonstopmode -halt-on-error main.tex
pdflatex -interaction=nonstopmode -halt-on-error main.tex
```

### Visualización en Windows

Después de compilar correctamente:

```powershell
Invoke-Item ".\main.pdf"
```

Para consultar la ubicación y fecha de modificación del PDF:

```powershell
Get-Item ".\main.pdf" | Select-Object FullName, LastWriteTime
```

### Compilación en Overleaf

1. Crear un proyecto y cargar `main.tex`.
2. Seleccionar `main.tex` como documento principal.
3. Seleccionar **pdfLaTeX** como compilador.
4. Recompilar y revisar el documento.
5. Descargar el PDF actualizado y guardarlo como `main.pdf`.

### Comprobación del documento

Antes de subir una nueva versión:

- Guardar los cambios del archivo fuente.
- Comprobar que la compilación finaliza sin errores.
- Revisar portada, tablas, numeración y saltos de página.
- Confirmar que el nombre del proyecto es uniforme.
- Verificar que el PDF corresponde a la versión actual del archivo fuente.
- Registrar únicamente participantes, respuestas y actividades reales.

### Tratamiento de las evidencias

La grabación de audio requiere el consentimiento del participante. Los originales que permitan identificarlo se conservarán en un espacio privado con acceso restringido al equipo y al docente.

No deben publicarse en este repositorio:

- Grabaciones de voz.
- Consentimientos firmados.
- Cédulas, teléfonos u otros datos personales innecesarios.
- Credenciales o enlaces que permitan acceso público a los originales.

Cuando se realice el ensayo, su registro deberá indicar fecha, participantes, roles y duración real. El manifiesto de evidencias documentará el nombre del archivo, fecha, duración, hash SHA-256 y ubicación restringida para su revisión.

Los extractos utilizados en el informe público deben evitar datos personales innecesarios. Las citas textuales y las interpretaciones del equipo deben distinguirse claramente.

### Control de versiones

Los commits deben describir cambios reales y conservar los aportes de los demás integrantes.

Los archivos auxiliares de compilación, como `.aux`, `.log`, `.out` y `.toc`, no forman parte de los entregables y no necesitan añadirse al repositorio.

### Uso de inteligencia artificial

Para este avance se utilizó ChatGPT como apoyo para organizar el documento, revisar la redacción del contexto, desarrollar la apertura y el cierre y corregir la sintaxis de LaTeX.

Las respuestas de ejemplo generadas para practicar no constituyen evidencia de una entrevista. La síntesis, el mapa de empatía y los hallazgos deberán basarse en las respuestas efectivamente obtenidas durante el ensayo.

### Repositorio

https://github.com/Espinoza-A-1006/ISR401-CEV