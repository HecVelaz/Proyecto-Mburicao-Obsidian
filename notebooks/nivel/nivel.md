
[[peaks]]

## Propósito
Contiene 2 scripts , aquí se encuentran los scripts que plotean y procesan los datos de nivel 

## Notebooks incluidos

### 1. Notebook de pre procesamiento 
- Archivo: `nivel_preprocessing.ipynb`
- Función:
  - Se carga el conjunto de datos nivel.csv de interim [[data/interim/nivel.csv|nivel]]
  - Se **normaliza la dimensión temporal** del dataset nivel y lo deja listo para análisis temporal.
- Salida:
  - DataFrame normalizado.
  - Salida `nivel_processed.csv` [[nivel_processed.csv]]
### 2. Notebook de ploteo
- Archivo: `aisp_processed_plot.ipynb`
- Función:
  - Gráfico usando matplotlib 
  - Se utiliza el conjunto de datos [[nivel_processed.csv]] ubicado en la carpeta processed y se carga además el conjunto de datos [[peak_detection_info.csv]]
- Salida:
  - Gráfico del nivel del arroyo superpuesto con los picos encontrados 