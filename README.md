# Tutorial de R Markdown para informes reproducibles

Este repositorio acompaña al artículo 
*"Un tutorial de R Markdown como herramienta para la investigación transparente y reproducible"* 
y contiene el ejemplo práctico completo descrito en la sección **"Ejemplo didáctico
paso a paso"**. Su propósito es que el lector pueda consultar los archivos
reales del flujo de trabajo (crear `.Rmd` → editar → *Knit*) y comparar las
salidas renderizadas en los tres formatos.

## Contenido del repositorio

```
tutorial_rmarkdown/
├── tutorial_rmarkdown.Rmd      # Archivo fuente del ejemplo didáctico
├── output/                     # Informes renderizados
│   ├── tutorial_rmarkdown.html
│   ├── tutorial_rmarkdown.pdf
│   └── tutorial_rmarkdown.docx
├── figures/                    # Figuras 3 y 4
└── tutorial_rmarkdown.Rproj    # Proyecto de RStudio
```

## Requisitos

- R (versión 4.5.1 o superior)
- RStudio Desktop
- Los siguientes paquetes de R:

```r
install.packages(c("rmarkdown", "knitr", "tinytex"))
tinytex::install_tinytex()   # Solo la primera vez, para exportar a PDF
```

## Cómo reproducir el ejemplo

1. Descargue este repositorio.
2. Abra el archivo `tutorial_rmarkdown.Rproj` en RStudio.
3. Abra `tutorial_rmarkdown.Rmd`.
4. Haga clic en **Knit** para generar el informe en HTML. Para PDF o Word,
   use la flecha desplegable junto al botón *Knit* y elija el formato deseado.

Los informes ya renderizados están disponibles en la carpeta `output/`.

## Cita

Este material acompaña a un artículo actualmente en revisión. La
referencia completa se añadirá una vez que el artículo sea publicado.

## Licencia

Este trabajo se distribuye bajo la licencia
[Creative Commons Atribución 4.0 Internacional (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.es).

