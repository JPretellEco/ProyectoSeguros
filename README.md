# **Proyecto: Detección de Clientes en Estado de Siniestro**  

## **Contexto**
La aseguradora **Seguros Titan** busca optimizar la identificación de clientes en estado de siniestro para reducir riesgos financieros. Para ello, se utilizará un modelo de **regresión logística** que analizará el comportamiento financiero de los clientes con base en sus datos históricos.

## **El Dataset**
El conjunto de datos contiene información de **5,800 clientes**, con **18 variables clave**, entre las que se encuentran:
- **Cliente_ID**: Identificador único de cada cliente.
- **Antigüedad_Maxima**: Tiempo que el cliente ha sido parte de la aseguradora.
- **Nivel_Ingresos**: Rango de ingresos del cliente. 0(bajo) a 5(alto)
- **Saldo_Pendiente**: Deuda actual del cliente.
- **Puntajes de Morosidad durante 6 meses**: Indicadores que reflejan el comportamiento de pago del cliente. 0:NoDq,1:1-29  a 6:150-179
- **Siniestros durante 6 meses**: Número de reclamaciones realizadas en distintos períodos.
- **Estado_Siniestro**: Variable categórica que indica si el cliente está en estado de siniestro (valores nulos presentes).

## **Objetivo del Proyecto**
- **Limpieza y preprocesamiento de los datos** para garantizar su calidad y fiabilidad.
- **Análisis exploratorio de datos (EDA)** para identificar patrones y correlaciones clave.
- **Implementación de un modelo de regresión logística** para predecir qué clientes están en estado de siniestro.
- **Evaluación del modelo** mediante métricas como precisión, recall y AUC-ROC.

## **Tecnologías Utilizadas**
🔹 Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)  
🔹 Jupyter Notebook para análisis interactivo  
🔹 Regresión Logística para la predicción de siniestros  
🔹 GitHub para control de versiones y documentación  

## **Impacto Esperado**
Con este modelo, **Seguros Titan** podrá anticiparse a futuros riesgos financieros y tomar medidas preventivas para clientes con alto riesgo de siniestro. Esto permitirá mejorar la eficiencia operativa y la gestión de cobros, reduciendo pérdidas y optimizando la relación con los asegurados.

