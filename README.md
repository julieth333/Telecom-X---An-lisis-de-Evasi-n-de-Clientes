Telecom X – Análisis de Evasión de Clientes (Churn)
Descripción del Proyecto

Este proyecto tiene como objetivo analizar la evasión de clientes (Churn) de Telecom X para identificar patrones, factores de riesgo y oportunidades de retención. A partir de un dataset en formato JSON con información demográfica, de servicios y pagos, se realiza un análisis completo que incluye limpieza de datos, exploración, visualización y generación de insights estratégicos.

El análisis permite entender qué características de los clientes y servicios están asociadas con mayor probabilidad de abandono y proporciona recomendaciones para reducir la evasión.

Estructura del Proyecto

TelecomX_Churn_Analysis.ipynb → Notebook principal con todo el análisis, gráficos y conclusiones.

TelecomX_Data.json → Dataset original con información de clientes.

README.md → Descripción del proyecto y guía para ejecutar el análisis.

Tecnologías Utilizadas

Python 3.12

Pandas → Manipulación y limpieza de datos.

NumPy → Cálculos y manejo de datos numéricos.

Matplotlib y Seaborn → Visualización de datos.

Jupyter / Google Colab → Entorno de ejecución del notebook.

Diccionario de Datos
Columna	Descripción
customerID	ID único del cliente
Churn	Indica si el cliente dejó la empresa (Yes/No)
gender	Género del cliente (Male/Female)
SeniorCitizen	Cliente mayor o igual a 65 años (0/1)
Partner	Si el cliente tiene pareja (Yes/No)
Dependents	Si el cliente tiene dependientes (Yes/No)
tenure	Meses que el cliente lleva con el servicio
PhoneService	Suscripción al servicio telefónico (Yes/No)
MultipleLines	Suscripción a más de una línea (Yes/No)
InternetService	Tipo de servicio de internet contratado
OnlineSecurity	Seguridad en línea adicional (Yes/No)
OnlineBackup	Respaldo en línea adicional (Yes/No)
DeviceProtection	Protección de dispositivo adicional (Yes/No)
TechSupport	Soporte técnico (Yes/No)
StreamingTV	Servicio de TV (Yes/No)
StreamingMovies	Servicio de streaming de películas (Yes/No)
Contract	Tipo de contrato (Month-to-month, One year, Two year)
PaperlessBilling	Facturación digital (Yes/No)
PaymentMethod	Método de pago del cliente
Charges.Monthly	Total de cargos mensuales
Charges.Total	Total gastado por el cliente
Pasos Realizados

Importación y carga de datos desde el archivo JSON en un DataFrame de Pandas.

Limpieza de datos: aplanamiento de columnas con diccionarios, conversión de valores binarios y numéricos, manejo de valores nulos y duplicados.

Análisis Exploratorio de Datos (EDA):

Distribución general de Churn.

Churn según variables categóricas (porcentaje de clientes que se fueron por categoría).

Churn según variables numéricas (violin plots para visualizar la distribución).

Conclusiones e insights sobre los factores que más afectan la evasión de clientes.

Recomendaciones estratégicas para reducir el Churn y mejorar la retención.

Resultados Clave

Los clientes con contratos Month-to-month tienen mayor probabilidad de cancelar.

Los servicios adicionales como soporte técnico, seguridad online y protección de dispositivos reducen la evasión.

Clientes con menor tiempo de permanencia y cargos altos presentan mayor riesgo de Churn.

Se identificaron patrones que permiten segmentar clientes de alto riesgo y tomar acciones preventivas.

Recomendaciones

Incentivar contratos más largos con promociones.

Ofrecer servicios adicionales para aumentar la fidelidad.

Implementar un programa de retención para clientes nuevos.

Analizar métodos de pago y facturación digital para mejorar la experiencia.

Monitorear clientes con alto riesgo de Churn y brindar incentivos personalizados.

Cómo Ejecutar

Abrir TelecomX_Churn_Analysis.ipynb en Google Colab o Jupyter Notebook.

Ejecutar las celdas de importación y limpieza de datos.

Revisar los bloques de EDA para generar gráficos interactivos y obtener insights.

Consultar las conclusiones y recomendaciones al final del notebook.
