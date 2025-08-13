# Telecom_x_Analisis_01

## Análisis de Evasión de Clientes (Churn) - Telecom X
### 📄Descripción del Proyecto
Este repositorio contiene el análisis de datos completo realizado para el proyecto "Churn de Clientes" de la empresa ficticia Telecom X. El objetivo principal es identificar los factores clave que influyen en la cancelación del servicio por parte de los clientes, utilizando un conjunto de datos en formato JSON.

El análisis sigue un flujo de trabajo estructurado de ciencia de datos, desde la extracción y limpieza de los datos (ETL) hasta el análisis exploratorio (EDA) y la generación de conclusiones estratégicas para el negocio.

🛠️ **Tecnologías Utilizadas**
Para llevar a cabo este análisis, se utilizaron las siguientes herramientas y bibliotecas de Python:

Entorno de Desarrollo: Google Colab

Lenguaje: Python 3

**Bibliotecas Principales**:

Pandas: Para la manipulación, limpieza y análisis de los datos.

Requests: Para la extracción de los datos desde la URL fuente.

Matplotlib & Seaborn: Para la creación de visualizaciones y gráficos estadísticos.

### 📊 Resumen del Análisis
El proyecto se dividió en las siguientes etapas clave:

Extracción, Transformación y Carga (ETL):

Se extrajeron los datos de un archivo JSON anidado.

Se "aplanó" la estructura de los datos utilizando pandas.json_normalize para crear una tabla de datos coherente.

Se realizó una limpieza exhaustiva que incluyó:

Corrección de tipos de datos (ej. Cargos_Totales).

Imputación de valores nulos con la mediana.

Estandarización de categorías inconsistentes (ej. unificar 'No internet service' a 'No').

Análisis Exploratorio de Datos (EDA):

Se calculó la tasa de evasión general, resultando en un 25.7%.

Se generaron visualizaciones para analizar la relación entre la evasión y diversas variables categóricas y numéricas.

### Conclusiones e Insights Clave:

Se identificó que el tipo de contrato es el factor más influyente, siendo los clientes con contrato mes a mes los más propensos a cancelar.

La antigüedad (tenure) es el principal factor de retención; a mayor antigüedad, menor es la probabilidad de evasión.

Los clientes con cargos mensuales más altos y servicios de Fibra Óptica también mostraron una mayor tendencia a la cancelación.

### 🚀 Cómo Replicar el Análisis
Puedes replicar este análisis completo directamente en tu navegador utilizando Google Colab. Sigue estos sencillos pasos:

**Requisitos Previos:**

Tener una cuenta de Google.

Abrir el Notebook en Google Colab:

Navega al archivo .ipynb en este repositorio.

Haz clic en el botón "Open in Colab" que aparece en la parte superior del archivo.

Alternativamente, ve a Google Colab, selecciona Archivo > Abrir cuaderno, elige la pestaña GitHub, pega la URL de este repositorio y selecciona el archivo .ipynb.

**Ejecutar el Análisis:**

Una vez que el notebook esté abierto, puedes ejecutar todas las celdas de código de forma secuencial.

La forma más sencilla es ir al menú Entorno de ejecución > Ejecutar todo.

También puedes ejecutar cada celda individualmente presionando Shift + Enter.

El notebook está diseñado para ser auto-contenido; instalará todas las dependencias necesarias y descargará los datos automáticamente.

👨‍💻 Autor
Jhair Lescano Guevara
Escuela: Alura Latam - One Oracle
