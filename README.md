Análisis de Datos - Evaluación Final Módulo 3

Descripción del Proyecto

Este proyecto corresponde a la evaluación final del Módulo 3 del curso de Data Analyst en Adalab. El objetivo principal es analizar el comportamiento de los clientes en un programa de lealtad de una aerolínea, utilizando técnicas de Exploratory Data Analysis (EDA), estadística descriptiva e inferencial, y visualización de datos.


Estructura del Proyecto

El repositorio contiene los siguientes archivos:

Customer Flight Activity.csv → Datos sobre vuelos reservados, distancia recorrida y puntos acumulados por los clientes.

Customer Loyalty History.csv → Información personal y de fidelización de los clientes, incluyendo nivel educativo, ingresos y estado civil.

evaluacion-final-fatimagonzalezya.ipynb → Notebook con el análisis y las visualizaciones.

README.md → Documentación del proyecto.


Tecnologías y Herramientas Utilizadas

Python

Pandas para manipulación y análisis de datos

Matplotlib y Seaborn para visualización de datos

Scipy y Statsmodels para estadística inferencial y pruebas de hipótesis

Git y GitHub para control de versiones


Análisis Realizado

Fase 1: Exploración y Limpieza de Datos

Análisis de valores nulos y su imputación según la distribución de los datos.

Eliminación de duplicados asegurando que cada cliente se cuente correctamente.

Conversión de columnas categóricas y unión de datasets.

Fase 2: Visualización de Datos

Se generaron gráficas para responder preguntas clave:

Distribución de vuelos reservados por mes.

Relación entre distancia recorrida y puntos acumulados.

Distribución de clientes por estado civil y género.

Comparación de salario según nivel educativo.

Proporción de clientes según tipo de tarjeta de fidelidad.

Fase 3: Estadística Inferencial

Se realizaron pruebas estadísticas para evaluar diferencias significativas en los datos:

ANOVA y prueba t para analizar diferencias en vuelos reservados según nivel educativo.

Prueba de hipótesis para verificar patrones en la acumulación de puntos.


Conclusiones Finales

Se identificaron picos de vuelos en verano y Navidad, lo que confirma la estacionalidad de los viajes.

No se encontraron grandes diferencias en el salario promedio por nivel educativo, pero sí en la cantidad de vuelos reservados.

Se confirmó que la tarjeta "Nova" acumula más puntos por distancia recorrida que otras tarjetas.

La estadística inferencial confirmó que el nivel educativo afecta la cantidad de vuelos reservados, siendo los clientes con estudios universitarios quienes más viajan.


Autora

Fatima González
Este análisis ha sido realizado como parte del fin de módulo 3 del curso de Data Analyst en Adalab (promo-c)
