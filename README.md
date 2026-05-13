# Análisis de Movilidad y Modelado de Tiempos - Bogotá-Colombia

Este repositorio contiene un estudio detallado sobre la **Encuesta de Movilidad de Bogotá**, desarrollado como parte de la Maestría en Big Data y Data Science. El objetivo principal es caracterizar los patrones de viaje y modelar los factores que influyen en la duración de los desplazamientos en la ciudad.

El análisis se divide en dos fases fundamentales que corresponden a los notebooks incluidos:

### 1. Exploración y Caracterización (Parte 1)
Se realiza un Análisis Exploratorio de Datos (EDA) sobre un dataset de **147,251 registros**, identificando:
* **Principales Motivos de Viaje:** Predominancia de "Volver a casa" (48.18%) y "Trabajar" (19.32%).
* **Modos de Transporte:** Distribución entre Peatón, SITP, Transmilenio y otros medios.
* **Geolocalización:** Mapeo de puntos críticos de origen y destino mediante coordenadas.

### 2. Preprocesamiento y Modelado (parte 2)
Enfocado en la preparación de datos para modelos predictivos de duración de viaje:
* **Limpieza de Datos:** Tratamiento de valores nulos y filtrado de valores atípicos.
* **Feature Engineering:** Creación de variables basadas en franjas horarias (Pico vs. Valle) y tipos de transporte.
* **Análisis de Correlación:** Identificación de las variables con mayor impacto en el tiempo total de desplazamiento.

## Tecnologías y Librerías
* **Lenguaje:** Python 3.x
* **Entorno:** Jupyter Notebook / Google Colab
* **Librerías:** * `Pandas` y `NumPy` para manipulación de datos.
  * `Matplotlib` y `Seaborn` para visualización estadística.
  * `Scikit-learn` para el preprocesamiento de variables.
