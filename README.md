# hawc-3hwx-analysis
Análisis exploratorio del catálogo 3HWC del HAWC Observatory realizado como parte de preparación para una asistencia de investigación.

# Datos
Catálogo 3HWC disponible publicamente por el HAWC Observatory:
https://data.hawc-observatory.org/datasets/3hwc-survey/3HWC_combined.yml

El catálogo contiene 65 fuentes de rayos gamma detectadas en 1523 días de observación, con posiciones en RA/Dec, test statistic (TS) y mediciones de flujo.

# Contenido
3HWC_analysis.ipynb  -jupyter notebook con el análisis de:

-Mapa del cielo de las 65 fuentes gamma con posicion (RA/Dec) y significancia (TS)
-Histograma de distibución de TS en escala logarítmica
-Estadística descriptiva del catálogo de TS: fuente mas significativa, TS promedio y distribución de fuentes por significancia

# Requisitos
Python>=3.10,
numpy,
matplotlib,
pyyaml,
pandas.

## Autor
Raúl - Facultad de Ciencias,unam
