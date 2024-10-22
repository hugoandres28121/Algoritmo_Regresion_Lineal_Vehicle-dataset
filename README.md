# Modelo de Regresión Lineal para Predicción de Precios de Vehículos

Este repositorio contiene un Jupyter Notebook que implementa un modelo de regresión lineal para predecir los precios de los vehículos usando un conjunto de datos con diferentes características de los vehículos. El análisis incluye preprocesamiento de datos, ingeniería de características y entrenamiento del modelo para proporcionar predicciones precisas.

## Descripción del Proyecto

El objetivo de este proyecto es construir un modelo de aprendizaje automático utilizando regresión lineal para estimar los precios de los vehículos en función de varias características, como:

- Marca y modelo del vehículo
- Tipo de transmisión
- Tamaño del motor
- Kilometraje
- Año de fabricación
- Tipo de combustible

## Contenido

- **Cars.ipynb**: El Jupyter Notebook que contiene todos los pasos para el preprocesamiento de datos, la construcción del modelo y su evaluación.
- **Dataset**: Conjunto de datos de vehículos con diferentes características para predecir los precios.

## Pasos en el Notebook

1. **Carga de Datos**: Importar el conjunto de datos de vehículos y mostrar información básica sobre los datos.
2. **Preprocesamiento de Datos**: Manejo de valores faltantes, codificación de variables categóricas y división del conjunto de datos en entrenamiento y prueba.
3. **Ingeniería de Características**: Convertir las características categóricas (por ejemplo, marca, modelo) en valores numéricos usando One-Hot Encoding.
4. **Entrenamiento del Modelo**: Entrenar un modelo de regresión lineal en los datos procesados.
5. **Evaluación**: Evaluar el modelo utilizando métricas como el error cuadrático medio (MSE) y el R-cuadrado.

## Requisitos

Para ejecutar el notebook, se requieren las siguientes bibliotecas de Python:

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`

Puedes instalarlas utilizando:

```bash
pip install pandas numpy scikit-learn matplotlib

