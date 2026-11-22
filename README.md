Proyecto Fin de Curso · Entrega 1

Universidad Técnica Estatal de Quevedo (UTEQ) · Facultad de Ciencias de la Computación · Carrera de Software  
Ingeniería de Requerimientos (ISR-401) · 4.º nivel, paralelo B · Unidad 2 · SPA 2026–2027

**Proyecto:** SGMC - Sistema de gestión de Microcréditos  
**Organización:** Universidad Técnica Estatal de Quevedo
**Repositorio público:** `ISR401-SGMC` · https://github.com/TahinyMel/ISR401-SGMC
**Cierre:** domingo 22 de noviembre de 2026, 23:59

## Integrantes


| Integrante | Nombre y apellidos | Rol en el proyecto | Aportes verificables (archivos, secciones o artefactos) |
| --- | --- | --- | --- |
| 1 | CHAVARRIA CUENCA TAHINY MEL | [PENDIENTE] | [PENDIENTE] |
| 2 | RIVERA SUAREZ JONATHAN JAVIER | Modelado y partes interesadas | Diagrama de contexto y matriz poder–interés (modelos/, figuras/); secciones/partes_interesadas.tex y secciones/contexto.tex; cuestionario (instrumentos/Cuestionario/) |
| 3 | ROCHINA ROCHINA FREDDY DAVID | [PENDIENTE] | [PENDIENTE] |


## Índice de carpetas y archivos

| Ruta desde la raíz | Contenido requerido |
| --- | --- |
| `README.md` | Integrantes, índice e instrucciones de compilación de cada documento del repositorio. |
| `PFC/E1/main.tex` | Fuente LaTeX del documento E1, con 12 a 20 páginas de contenido. |
| `PFC/E1/referencias.bib` | Referencias BibTeX en estilo IEEE. |
| `PFC/E1/figuras/` | Imágenes exportadas de los modelos y capturas. |
| `PFC/E1/instrumentos/` | Tres instrumentos de elicitación. |
| `PFC/E1/modelos/` | Fuentes editables del diagrama de contexto y de la matriz poder–interés. |
| `PFC/E1/evidencias/` | Evidencias anonimizadas y `MANIFIESTO.md` de las evidencias privadas. |
| `PFC/E1/main.pdf` | PDF compilado del documento E1. |

## Compilación reproducible



   ### Compilar en Overleaf

1. Descarga el repositorio `TahinyMel/ISR401-SGMC` e importa el contenido de `PFC/E1/` al proyecto de Overleaf. Conserva `main.tex`, `referencias.bib` y la carpeta `figuras/` al mismo nivel.
2. Selecciona `main.tex` como documento principal y configura `pdfLaTeX` con TeX Live 2026.
3. Pulsa **Recompile** y descarga el PDF generado como `main.pdf`.

### Compilar desde un clon local

Con TeX Live 2026 instalado, ejecuta en este orden:

```sh
git clone https://github.com/TahinyMel/ISR401-SGMC.git
cd ISR401-SGMC/PFC/E1
pdflatex -halt-on-error main.tex
bibtex main
pdflatex -halt-on-error main.tex
pdflatex -halt-on-error main.tex
```

El PDF se genera en `PFC/E1/main.pdf`. BibTeX procesa la bibliografía y las dos últimas pasadas de pdfLaTeX resuelven las citas y las referencias cruzadas.





## Estructura del documento E1

| Contenido | Qué debe quedar documentado |
| --- | --- |
| Organización real | Identificar una organización de Quevedo o Los Ríos y el problema abordable con software, acordado con ella. Respaldarlo con la carta firmada por su responsable y el registro del primer contacto. |
| Visión y alcance | Incluir la declaración de visión, al menos tres objetivos de negocio medibles, lo incluido y excluido del alcance y las restricciones conocidas. |
| Partes interesadas | Identificar al menos ocho roles sin nombres personales. Registrar interés, influencia, disponibilidad y estrategia de participación por rol. Presentar la matriz poder–interés. |
| Contexto | Presentar el diagrama de contexto con el límite del sistema y la tabla de las ocho perspectivas del sílabo con hallazgos de la organización real. |
| Plan de elicitación | Indicar qué técnica se aplicará a cada parte interesada y justificarla según la fuente y el tipo de conocimiento. Incluir el cronograma de sesiones y vincular técnicas, instrumentos y objetivos. |
| Ética y datos | Incluir el modelo de consentimiento informado y el procedimiento de anonimización y custodia de evidencias. |
| Gestión del proyecto | Definir los roles del equipo, el cronograma hasta la semana 17, el plan de comunicación con la organización y el registro de riesgos específicos. |
| Referencias e IA | Citar al menos cinco referencias IEEE verificables (normas, libros o artículos indexados), incluidas al menos dos de los últimos cinco años. Verificar sus datos y citarlas donde se usan. Declarar expresamente el no uso de IA o, si se usó como apoyo, registrar herramienta, versión, propósito y cómo se verificó lo obtenido. |

## Instrumentos

Instrumentos de elicitación en el repositorio:

| Instrumento | Archivo |
| --- | --- |
| Guion de entrevista | [`PFC/E1/instrumentos/Entrevista/Preguntas/Preguntas_EntrevistaSemiestructurada.docx`](PFC/E1/instrumentos/Entrevista/Preguntas/Preguntas_EntrevistaSemiestructurada.docx) |
| Cuestionario | [`PFC/E1/instrumentos/Cuestionario/cuestionario_solicitantes.md`](PFC/E1/instrumentos/Cuestionario/cuestionario_solicitantes.md) |
| Guía de observación | [`PFC/E1/instrumentos/Guía de observación/Guia_observacion_entrevista_SGMC.docx`](PFC/E1/instrumentos/Gu%C3%ADa%20de%20observaci%C3%B3n/Guia_observacion_entrevista_SGMC.docx) |

## Modelos

Modelos en el repositorio:

| Modelo | Fuente editable | Figura exportada |
| --- | --- | --- |
| Diagrama de contexto | [`PFC/E1/modelos/diagrama_contexto.puml`](PFC/E1/modelos/diagrama_contexto.puml) | [`PFC/E1/figuras/diagrama_contexto.png`](PFC/E1/figuras/diagrama_contexto.png) |
| Matriz poder–interés | [`PFC/E1/modelos/matriz_poder_interes.puml`](PFC/E1/modelos/matriz_poder_interes.puml) | [`PFC/E1/figuras/matriz_poder_interes.png`](PFC/E1/figuras/matriz_poder_interes.png) |

## Manifiesto de evidencias

Registros de evidencias en el repositorio:

| Evidencia | Nombre de archivo | Fecha | Duración | Huella SHA-256 |
| --- | --- | --- | --- | --- |
| Carta de aceptación firmada | [PENDIENTE] | [PENDIENTE] | [PENDIENTE: duración o «No aplica»] | [PENDIENTE: huella del archivo] |
| Registro del primer contacto | [PENDIENTE] | [PENDIENTE] | [PENDIENTE: duración o «No aplica»] | [PENDIENTE: huella del archivo] |



