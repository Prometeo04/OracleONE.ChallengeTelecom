# OracleONE.ChallengeTelecom
 Oracle ONE - Challenge Telecom X (Análisis de Churn)
 Descripción del Proyecto

Telecom X es una empresa de telecomunicaciones que enfrenta un alto índice de evasión de clientes (churn).

En este proyecto se realiza:

Extracción y normalización de datos

Limpieza y transformación del dataset

Análisis Exploratorio de Datos (EDA)

Identificación de variables relacionadas con la evasión

Preparación de los datos para modelado predictivo

El objetivo final es entregar un dataset limpio y estructurado para que el equipo de Ciencia de Datos pueda construir modelos predictivos que anticipen el abandono de clientes.

 Objetivos

Comprender la estructura del dataset

Detectar valores faltantes o inconsistencias

Transformar variables categóricas

Analizar relaciones entre variables y churn

Identificar patrones de comportamiento en clientes que abandonan el servicio

Preparar datos para futuros modelos de Machine Learning

🛠️ Tecnologías Utilizadas

Python 3

Pandas

NumPy

Matplotlib

Seaborn

Plotly

SciPy (Chi-Square Test)

Requests

JSON

📂 Fuente de Datos

El dataset fue extraído en formato JSON desde un repositorio público y posteriormente normalizado para su análisis.

El proceso incluye:

Conversión de JSON a DataFrame

Normalización de estructuras anidadas (customer, phone, internet, account)

Concatenación de tablas

Limpieza y transformación de variables

 Proceso de Limpieza

Se realizaron las siguientes transformaciones:

Conversión de Churn a variable binaria (Yes → 1, No → 0)

Transformación de SeniorCitizen a variable categórica

Eliminación de columnas irrelevantes (customerID)

Manejo de columnas auxiliares

Revisión de valores nulos

 Análisis Exploratorio (EDA)

Durante el análisis se realizaron:

Visualizaciones de distribución

Comparaciones entre churn y variables categóricas

Análisis de variables numéricas

Pruebas estadísticas (Chi-Cuadrado) para evaluar independencia entre variables

Se utilizaron:

Gráficos de barras

Histogramas

Subplots interactivos con Plotly

Mapas de frecuencia

 Principales Insights

El análisis permitió identificar:

Variables con mayor relación con churn

Patrones de comportamiento en clientes que abandonan

Factores contractuales y de servicio asociados a mayor evasión

Posibles segmentos de riesgo

Estos resultados permiten orientar estrategias de retención.
