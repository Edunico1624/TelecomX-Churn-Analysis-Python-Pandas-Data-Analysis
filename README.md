📊 Telecom X – Análisis de Evasión de Clientes (Churn)
📌 Descripción del proyecto

Este proyecto forma parte del Challenge de Data Science de Alura LATAM y tiene como objetivo analizar la evasión de clientes (Churn) en la empresa ficticia Telecom X.

La empresa enfrenta una alta tasa de cancelaciones de servicios, por lo que se realizó un análisis exploratorio de datos (EDA) utilizando Python y Pandas para identificar patrones y factores asociados a la pérdida de clientes.

Los resultados de este análisis pueden ayudar al equipo de Data Science y negocio a desarrollar estrategias para mejorar la retención de clientes.

🎯 Objetivos del análisis

Importar y procesar datos desde una API en formato JSON

Aplicar el proceso ETL (Extract, Transform, Load)

Realizar limpieza y transformación de datos

Explorar los datos mediante análisis exploratorio (EDA)

Crear visualizaciones para identificar patrones

Generar insights estratégicos para reducir el churn

🛠️ Tecnologías utilizadas

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

📂 Estructura del proyecto
TelecomX-Churn-Analysis
│
├── TelecomX_LATAM.ipynb
├── TelecomX_Data.json
├── TelecomX_diccionario.md
├── README.md

Descripción de los archivos:

Archivo	Descripción
TelecomX_LATAM.ipynb	Notebook con todo el análisis
TelecomX_Data.json	Dataset original de clientes
TelecomX_diccionario.md	Diccionario de datos
README.md	Documentación del proyecto
🔄 Proceso de análisis

El proyecto sigue las etapas principales del análisis de datos.

1️⃣ Extracción de datos

Los datos fueron obtenidos desde un archivo JSON alojado en GitHub, que simula una API.

El dataset contiene información sobre:

Datos demográficos de clientes

Servicios contratados

Facturación

Métodos de pago

Estado de cancelación (Churn)

2️⃣ Transformación y limpieza de datos

Se realizaron varias tareas de limpieza:

Normalización de columnas anidadas en JSON

Conversión de tipos de datos

Identificación y tratamiento de valores nulos

Estandarización de variables categóricas

Creación de la variable Cuentas_Diarias

Esto permitió preparar el dataset para el análisis exploratorio.

📊 Análisis Exploratorio de Datos (EDA)

Durante el análisis se exploraron diferentes variables relacionadas con la evasión de clientes.

Se analizaron principalmente:

Variables categóricas

Tipo de contrato

Método de pago

Género

Servicios contratados

Variables numéricas

Tiempo de permanencia del cliente (tenure)

Facturación mensual (MonthlyCharges)

Facturación total (TotalCharges)

Se utilizaron visualizaciones como:

gráficos de barras

boxplots

histogramas

matriz de correlación

📈 Principales hallazgos (Insights)

Del análisis se identificaron varios patrones importantes:

1️⃣ Clientes con contrato mensual presentan mayor evasión

Los clientes con contratos month-to-month tienen mayor probabilidad de cancelar el servicio.

2️⃣ Los clientes nuevos cancelan más

Los clientes con menor tiempo de permanencia (tenure) tienen mayor probabilidad de churn.

Esto indica que los primeros meses del servicio son críticos.

3️⃣ Clientes con mayor gasto total tienden a permanecer

Los clientes con mayor facturación acumulada muestran menor tasa de evasión.

4️⃣ Algunos métodos de pago presentan mayor churn

Los clientes que utilizan ciertos métodos de pago electrónicos presentan mayor tendencia a cancelar.

💡 Recomendaciones estratégicas

A partir del análisis se proponen las siguientes estrategias:

Incentivar contratos anuales o de largo plazo

Implementar programas de fidelización para clientes nuevos

Ofrecer beneficios o promociones durante los primeros meses

Analizar estrategias específicas para clientes con mayor riesgo de churn

🚀 Posibles mejoras futuras

Este análisis puede ampliarse con:

Modelos de Machine Learning para predicción de churn

Segmentación de clientes

Análisis de Customer Lifetime Value

Modelos de clasificación como:

Logistic Regression

Random Forest

XGBoost

👨‍💻 Autor

Andrés Ayala

Técnico en equipos biomédicos con interés en Data Science, Python y análisis de datos.

📚 Fuente de datos

Dataset proporcionado por:

Alura LATAM – Challenge Data Science
