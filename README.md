# Reporte del máster en Economía Aplicada

Plantilla de trabajo de asignatura en Quarto, con formato APA y colores de la Universidad de Alicante.

## Archivos

- `index.qmd`: contenido del reporte (portada, secciones y referencias).
- `_quarto.yml`: configuración del formato PDF (LaTeX, XeLaTeX, márgenes, colores).
- `references.bib`: bibliografía en formato BibTeX.
- `apa.csl`: estilo de citas APA.

## Requisitos

1. [Quarto](https://quarto.org/docs/get-started/) (versión 1.4 o superior).
2. Una distribución de LaTeX con XeLaTeX. Quarto puede instalar paquetes faltantes automáticamente.

## Cómo generar el PDF

**Desde RStudio:** abre `index.qmd` y pulsa **Render**.

**Desde VSCode:** instala la extensión de Quarto, abre `index.qmd` y pulsa el botón de previsualización, o ejecuta en la terminal:

```bash
quarto render index.qmd
```

El PDF se genera en la carpeta `_output/`.

## Cómo editar

- Escribe el contenido debajo de cada encabezado `#`.
- Añade fuentes en `references.bib` y cítalas con `[@clave]`.
- Para figuras, usa bloques de código con `#| label: fig-nombre` y `#| fig-cap: "Descripción"`.
