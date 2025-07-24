# Predicción de Precios de Propiedades

Este proyecto fue desarrollado de forma individual en el marco de la **Maestría en Explotación de Datos y Descubrimiento del Conocimiento**, como parte de la materia **Data Mining**.

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

- Análisis exploratorio de datos (EDA)
- Limpieza: tratamiento de valores faltantes, outliers y codificación
- Preprocesamiento de variables
- Entrenamiento y comparación de múltiples modelos de regresión:
  - Regresión Lineal
  - Árbol de Decisión
  - Random Forest
  - Otros modelos supervisados
- Evaluación con **RMSE**
- Preparación de la predicción final para submitir a la competencia

## Enfoque

El proyecto se centró en:

- Aplicar buenas prácticas de **limpieza y preparación de datos**
- Evaluar cómo afecta el preprocesamiento al rendimiento de los modelos
- Comparar diferentes algoritmos supervisados
- Generar una solución reproducible y clara para un problema realista

