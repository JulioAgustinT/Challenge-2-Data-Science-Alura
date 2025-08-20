# Challenge-2-Data-Science-Alura
Predicción y análisis de Customer Churn en telecomunicaciones usando Python. Incluye exploración de datos, visualización de métricas de churn y preparación de variables para modelado.

Este proyecto analiza la fuga de clientes (churn) en una empresa de telecomunicaciones.  
El objetivo es entender los factores que influyen en la cancelación de clientes y preparar el dataset para entrenar modelos de predicción.

## Contenido del proyecto
- Exploración y limpieza de datos
- Expansión de variables anidadas (customer, phone, internet, account)
- Análisis descriptivo de variables numéricas y categóricas
- Visualización de churn por diferentes categorías
- Creación de variables derivadas como monthly_charges, total_charges y cuentas_diarias

## Estructura
- TelecomX_Churn_challenge.ipynb: notebook principal con análisis y visualizaciones
- data/ (opcional): carpeta de datos
- README.md: documentación del proyecto

## Tecnologías utilizadas
- Python 3
- pandas, numpy
- matplotlib
- Jupyter Notebook

## Ejemplos de visualizaciones
- Churn por género
- Churn por tipo de contrato
- Churn por método de pago y facturación electrónica
- Churn por deciles de tenure
- Distribución de gasto mensual y churn

## Próximos pasos
- Entrenar modelos de clasificación
- Evaluar métricas como AUC, F1 y recall
- Identificar clientes en riesgo con mayor precisión
