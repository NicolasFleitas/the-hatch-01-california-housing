# 🏡 Análisis del Mercado Inmobiliario en California
## 🌐 Visualización Interactiva

* **Ejecución en vivo:** [Ver el Notebook interactivo en Kaggle](https://www.kaggle.com/code/nicolasfleitas/california-housing-eda-insights)
* **Mi Perfil:** [Conecta conmigo en Kaggle](https://www.kaggle.com/nicolasfleitas)

Este proyecto forma parte del primer desafío de la etapa **The Hatch** en Penguin Academy. El objetivo principal es realizar un Análisis Exploratorio de Datos (EDA) exhaustivo para descubrir cuáles son los verdaderos impulsores detrás de los altos precios de las viviendas en el estado de California, utilizando datos del censo de 1990.

## 🎯 Objetivos del Proyecto
* Limpiar y preprocesar un conjunto de datos espaciales y demográficos.
* Identificar correlaciones entre el nivel de ingresos, la ubicación geográfica y el valor de las propiedades.
* Generar visualizaciones narrativas (Data Storytelling) que expliquen el comportamiento del mercado.

## 🛠️ Tecnologías y Herramientas
* **Lenguaje:** Python
* **Análisis y Manipulación:** Pandas, NumPy
* **Visualización:** Matplotlib, Seaborn
* **Entorno:** Jupyter Notebook

## 🗂️ Fuente de Datos
Los datos originales no están incluidos en este repositorio por su tamaño y para mantener el historial de Git limpio. Para ejecutar este proyecto localmente, debes:
1. Descargar el dataset oficial desde Kaggle: [California Housing Prices Dataset](https://www.kaggle.com/datasets/camnugent/california-housing-prices)
2. Extraer el archivo `housing.csv`.
3. Colocar el archivo en la misma carpeta raíz donde se encuentra el notebook `01_analisis_mercado_inmobiliario.ipynb`.

## 📊 Hallazgos Principales
1. **El factor Rey (Ingresos):** Se descubrió una fuerte correlación positiva (~0.69) entre los ingresos medios de un vecindario y el valor de las casas, siendo el predictor más fuerte del dataset.
2. **Impacto Costero:** Mediante mapeo geográfico, se evidenció que los valores inmobiliarios se disparan en los clústeres cercanos al Océano Pacífico (Bahía de San Francisco y Los Ángeles), decayendo drásticamente hacia el interior (Inland).
3. **Topes Artificiales (Capping):** Se detectaron e identificaron anomalías en la recolección de datos, específicamente topes artificiales fijados en $500,000 para el valor de las casas y 50 años para la antigüedad, un dato crucial para futuros modelos de Machine Learning.

## 🚀 Cómo ejecutar este proyecto
1. Clona este repositorio: `git clone https://github.com/tu-usuario/the-hatch-01-california-housing.git`
2. Asegúrate de tener instalado Python y las librerías requeridas.
3. Abre el archivo `01_analisis_mercado_inmobiliario.ipynb` en Jupyter Notebook o VS Code.
4. Ejecuta las celdas secuencialmente.
