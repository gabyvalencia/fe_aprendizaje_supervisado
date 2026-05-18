# fe_aprendizaje_supervisado
Clasificación de Rendimiento de Equipos de Fútbol usando Machine Learning

Proyecto de Aprendizaje Supervisado enfocado en la clasificación del rendimiento de equipos de fútbol mediante técnicas de Machine Learning y análisis exploratorio de datos.

Repositorio: GitHub - fe_aprendizaje_supervisado

Objetivo del Proyecto

El objetivo de este proyecto es aplicar la metodología completa de Machine Learning para resolver un problema de clasificación multiclase en el contexto deportivo.

Se busca clasificar equipos de fútbol en categorías de:
- Alto rendimiento
- Rendimiento medio
- Bajo rendimiento
Proyecto en Google Colab
Contenido del Proyecto

El notebook contiene:

1. Introducción del Problema

Contextualización del problema y motivación del análisis deportivo mediante Machine Learning.

2. Carga y Preparación de Datos
limpieza de datos
tratamiento de valores faltantes
codificación de variables
normalización y escalamiento
3. Análisis Exploratorio de Datos (EDA)

Se realizaron análisis sobre:

distribución de variables
correlaciones
comportamiento por temporadas
análisis de estacionalidad
detección de patrones

4. Visualización con TSNE

Se utilizó TSNE para reducir dimensionalidad y visualizar el espacio de características en 2 dimensiones.

La visualización permite observar:

separación entre clases
agrupamiento natural de equipos
similitud entre rendimientos deportivos

Cuando se utilizó clasificación supervisada, los puntos fueron coloreados según su label correspondiente.

5. Modelado de Machine Learning

Se aplicaron modelos de clasificación multiclase para predecir el rendimiento de los equipos.

Entre las etapas implementadas:

división train/test
entrenamiento de modelos
evaluación de métricas
comparación de desempeño
6. Evaluación de Resultados

Se analizaron métricas como:

Accuracy
Recall
Precision
F1-Score

Además, se interpretaron los resultados obtenidos y el comportamiento de los modelos.

Cómo Ejecutar el Proyecto
- Clonar el repositorio:
  git clone https://github.com/gabyvalencia/fe_aprendizaje_supervisado.git
- Abrir el notebook en Google Colab o Jupyter Notebook.
- Instalar dependencias:
  pip install pandas numpy matplotlib seaborn scikit-learn
- Ejecutar las celdas del notebook.

Estructura del Repositorio
fe_aprendizaje_supervisado/
│
├── ProyectoAS.ipynb
├── README.md
└── dataset/
Autora

Daisy Gabriela Valencia A.
