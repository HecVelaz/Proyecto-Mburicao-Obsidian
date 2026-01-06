# Archivo `nivel.csv`

## Descripción
Contiene datos de niveles del arroyo Mburicao.

## Origen de los datos
- Fuente: Laboratorio de Mecánica y Energía  FIUNA
- Método de adquisición: -
- Período temporal: frecuencia 10 min
- Ubicación / contexto (si aplica): Arroyo Mburicaó , zona San Ignacio Loyolas School

## Formato del archivo
- Tipo: CSV
- Separador: (`,` )
## Columnas
- Fecha
- Nivel del agua Arroyo Mburicao
## Unidades
- Nivel del agua Arroyo Mburicao: (m) metros
## Calidad del dato
- Valores faltantes: 
- Ruido:
- Valores atípicos:
- Observaciones:
## Uso en el proyecto
- Notebooks que lo utilizan:
  - `notebooks/data_raw_info.ipynb`
	   Aquí se realiza una revisión de la cantidad de datos , el tipo , si existen nulos. Cambio de nombre de columnas. El guardado final se guarda en interim como nivel.csv
## Relación con otros datos
- Relación con `aisp.csv`
- Relación con `sil.csv`
- Relación con `snd.csv`
## Observaciones finales
- No existen valores nulos pero si vacios faltantes entre las fechas 
  (10 de mayo 2022) hasta (6 aosto 2022)