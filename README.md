# Predicción de Precios de Propiedades

Este proyecto fue desarrollado de forma individual en el marco de la **Maestría en Explotación de Datos y Descubrimiento del Conocimiento- FCEN, UBA.**, como parte de la materia **Data Mining**.

## Objetivo
El objetivo del proyecto fue entender cómo variables urbanas y geoespaciales influyen en el valor de una propiedad, y construir modelos predictivos aplicables a contextos reales del negocio inmobiliario. Para ello, se trabajó con un conjunto de datos de gran escala, lo que exigió un proceso riguroso de análisis exploratorio, limpieza y preprocesamiento antes de entrenar y evaluar distintos modelos supervisados.

El trabajo consistió en participar de una **competencia simulada en Kaggle** organizada por la cátedra, cuyo objetivo era predecir el precio de propiedades a partir de un dataset realista.  
Se evaluó la capacidad de modelado, pero principalmente el manejo del **preprocesamiento y la calidad de los datos**.  
La métrica utilizada fue **RMSE (Root Mean Squared Error)**.

## Dataset

El dataset fue provisto por la cátedra y está basado en publicaciones reales de propiedades de **Properati**, incluyendo variables como precio, ubicación, superficie, ambientes y otros atributos.  
No se incluye el dataset en este repositorio por ser parte del entorno de evaluación.

## Notebook

El desarrollo completo se encuentra en el notebook de Google Colab:

- `DataMining.ipynb`

## Contenido del notebook

- **Análisis exploratorio de datos (EDA)**  
- **Limpieza y preprocesamiento de datos reales de la base de Properati**  
  - Tratamiento de valores faltantes  
  - Detección y manejo de outliers  
  - Codificación de variables categóricas  
- **Ingeniería de características (Feature Engineering)**  
- **Enriquecimiento de datos con capas geoespaciales**  
- **Modelado predictivo**  
  - Entrenamiento y comparación de múltiples modelos de regresión:  
    - Regresión Lineal  
    - Árboles de Decisión  
    - Random Forest  
    - Otros modelos supervisados  
- **Evaluación del rendimiento utilizando RMSE**  
- **Análisis de importancia de variables y visualizaciones interpretables**  
- **Generación de predicciones finales para submitir a la competencia**




