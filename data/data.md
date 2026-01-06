<!-- Nota principal de la carpeta data -->

# Carpeta `data`

## Propósito
Esta carpeta contiene **los datos base del proyecto**.
Todo el procesamiento, análisis y visualización parte de los archivos
almacenados aquí.
### Subcarpetas
- [[raw]]
- [[processed]]
- [[interim]]
- [[external]]
## Origen de los datos

- Fuente: (describir brevemente de dónde salen los datos)
- Método de obtención: (manual / descarga / sensor / exportación)
- Fecha o período: (si aplica)

## Estructura interna

- `raw/`
  Contiene los datos originales del proyecto en formato CSV.
  Cada archivo representa una variable o medición distinta, diferentes estaciones.

- `processed/`
  Contiene los datos procesados y limpios a partir de `raw/`.

- `external/`
  Datos de fuentes externas utilizados como complemento.


> Nota: **no modificar los datos en `raw/`**.  

## Formato de los archivos
- Tipo de archivo: (CSV / XLSX )
- Separador decimal / columnas relevantes
- Codificación (si aplica)

## Cómo se usan estos datos
- Notebooks que los consumen:
  - `notebooks/<nombre>.ipynb`
- Scripts relacionados:
  - `scr/<script>.py`

## Validaciones básicas
- Qué verificar antes de usar los datos:
  - valores faltantes
  - unidades
  - rangos esperados
  - separadores decimales , comas , puntos .

## Observaciones
- Supuestos importantes
- Limitaciones conocidas