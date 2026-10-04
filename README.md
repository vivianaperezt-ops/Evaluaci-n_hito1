# Evaluación 1: Análisis Carga-Deflexión en Viga Simplemente Apoyada

## Descripción del Proyecto
Este repositorio contiene un flujo de trabajo reproducible para comparar datos experimentales de deflexión con la predicción analítica del modelo elástico lineal de Euler-Bernoulli en una viga simplemente apoyada con carga puntual central.

## Estructura del Repositorio
- `data/`: Datos de entrada originales intactos (`datos_viga.csv` y `parametros_viga.xlsx`).
- `analysis/`: Planilla de cálculo reproducible (`analisis_viga.xlsx`) con conversiones de unidades y fórmulas explícitas.
- `figures/`: Gráfico comparativo generado (`carga_deflexion.png`).
- `report/`: Documento técnico (`main.tex`, `referencias.bib`, `nota_tecnica.pdf`).
- `USO_IA.md`: Declaración formal del uso de inteligencia artificial.

## Instrucciones de Reproducción
1. Abrir `analysis/analisis_viga.xlsx` para examinar el cálculo del segundo momento de área I = 1.0667e-3 m^4, las deflexiones teóricas y las diferencias relativas.
2. La figura comparativa se genera a partir de las columnas de carga y deflexiones y se encuentra disponible en `figures/carga_deflexion.png`.
3. Para compilar el informe técnico, importar los archivos de `report/` en Overleaf o compilar `main.tex` con `pdflatex` y `bibtex`.