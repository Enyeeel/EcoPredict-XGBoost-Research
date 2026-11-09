# EcoPredict — Experimentos de investigación

Este repositorio contiene dos notebooks para el análisis de estimaciones de residuos sólidos domiciliarios en la provincia de Lima.

## Contenido

- `EcoPredict_Experimentos_Principales.ipynb`: entrenamiento y comparación de algoritmos, evaluación temporal, ablación, SHAP y errores por distrito.
- `EcoPredict_Validacion_MINAM_2024.ipynb`: reconstrucción con la fórmula administrativa del MINAM y evaluación de 2024 con variables históricas.
- `dataset3_proporcion.csv`: archivo de datos procesados requerido para ambos notebooks (agregar tras verificar condiciones de redistribución).

## Ejecución

1. Utilizar Python y las dependencias indicadas en `requirements.txt`. Las versiones exactas del entorno original de cada experimento se documentan en el manuscrito y deben verificarse al reproducirlo.
2. Colocar `dataset3_proporcion.csv` en el directorio de ejecución de los notebooks. En Google Colab también puede utilizarse Google Drive, modificando la ruta indicada.
3. Ejecutar las celdas de cada notebook en orden. El segundo notebook guarda las métricas en `EcoPredict_validacion_adicional/`.

## Alcance

Los experimentos principales utilizan variables contemporáneas y evalúan una estimación retrospectiva. La prueba histórica de 2024 excluye población y GPC de ese año, pero no establece un pronóstico operativo hasta verificar la disponibilidad de los datos anteriores.

## Datos y derechos

El archivo CSV procede de información administrativa procesada. Confirmar los permisos de redistribución y citar la fuente oficial antes de hacerlo público. La licencia del código debe acordarse entre los autores; no asumir que cubre automáticamente el dataset.
