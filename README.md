# Predicción del precio de las acciones de Netflix

## Industria o Rubro
Data BI - Exploracion, Preparación de Datos y Machine Learnig

## Descripción
Este proyecto tiene como objetivo predecir el precio de las acciones de Netflix mediante modelos de Machine Learning. Se inició con la carga de un archivo CSV descargado desde Kaggle, seguido por la exploración y limpieza del dataset, abordando valores nulos y seleccionando las columnas relevantes para el análisis. Tras preparar los datos, se separaron para entrenamiento y prueba. Se aplicaron dos modelos, Regresión Lineal y Árbol de Decisión, y se eligió el más adecuado en función de métricas estadísticas. Finalmente, se compararon los valores reales de prueba con los valores predichos para evaluar la efectividad del modelo.

## Colaboradores
- **Nicolás Chaves** - [LinkedIn](https://www.linkedin.com/in/chaves-nicolas) - Rol: Analista de Datos
- **Cristian Albornoz** - [LinkedIn](https://www.linkedin.com/in/cristianalbornozdev) - Rol: Team Leader

## Tecnologías
- Deepnote (Notebook)
- Librerías: Pandas, Numpy, Scikit-Learn, Matplotlib

## Observaciones
El archivo CSV (`NFLX.csv`) y el Notebook pueden ser descargados para uso local. Para ejecutar el Notebook, es necesario ajustar la ruta del archivo CSV en el código. Reemplaza la línea:

```python
path_file = '/work/NFLX.csv'
```
por la ruta donde esté alojado el archivo NFLX.csv en tu sistema.
