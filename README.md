# DS-Challenge3
Telecom X - Parte 2, predicción de Churn: Pipeline completo de Machine Learning (EDA + Clasificación) para predecir la evasión de clientes usando Python, Scikit-Learn y técnicas de preprocesamiento.

# TelecomX Churn Predictor: Estrategia de Retención 2026

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?logo=scikit-learn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-informational?logo=pandas)

Este proyecto nace de la necesidad de **Telecom X** de transformar sus datos en decisiones estratégicas. El objetivo principal es predecir la fuga de clientes (**Churn**) mediante Machine Learning, pasando de un análisis reactivo a uno proactivo.

## El Desafío del Negocio
La deserción de clientes es uno de los mayores costos operativos en telecomunicaciones. En fases previas, identificamos que factores como la **Fibra Óptica** y los **contratos mensuales** eran detonantes críticos. Este proyecto entrega un modelo capaz de identificar quiénes están en riesgo para intervenir antes de la pérdida del activo.

## Análisis y Metodología
El proyecto se desarrolló en tres etapas fundamentales:
1. **EDA (Análisis Exploratorio):** Uso de Box Plots y Heatmaps para identificar patrones de comportamiento.
2. **Feature Engineering:** Tratamiento de datos desbalanceados y selección de variables críticas.
3. **Machine Learning:** Comparativa entre modelos lineales (Regresión Logística) y no lineales (Árboles de Decisión).

## Resultados del Modelo Seleccionado
Se optó por el **Modelo de Regresión Logística con Pesos Balanceados** debido a su alto desempeño en la métrica de negocio más importante: el **Recall**.

| Métrica | Resultado | Significado |
| :--- | :---: | :--- |
| **Recall (Churn)** | **79%** | Identifica a 8 de cada 10 clientes en riesgo de fuga. |
| **Precisión** | **51%** | Optimiza el gasto en campañas de retención. |
| **F1-Score** | **0.62** | Garantiza estabilidad y capacidad de generalización. |



## Tecnologías Utilizadas
* **Python** como lenguaje núcleo.
* **Scikit-Learn** para el modelado y métricas.
* **Imbalanced-learn (SMOTEENN)** para el balanceo de clases.
* **Seaborn & Matplotlib** para visualizaciones de impacto.
* **Joblib** para la persistencia de los modelos entrenados.

## Conclusiones Estratégicas
* **Foco en Fibra Óptica:** El modelo confirma que la infraestructura de fibra requiere mantenimiento preventivo prioritario.
* **Retención Temprana:** Los clientes con menos de 12 meses de permanencia deben entrar en planes de fidelización automática.
* **Eficiencia en CAC:** Retener al 79% de los desertores reduce drásticamente el Costo de Adquisición de Clientes.

---
**Desarrollado por:** Jaime Cuesta  
*Emprendedor, Backend Developer & Data Scientist*
