# Proyecto-analisis-de-datos-

## Visión General del Proyecto

Este repositorio contiene un análisis exploratorio de datos (EDA) exhaustivo centrado en la evasión de clientes (Churn) de una empresa de telecomunicaciones ficticia. El objetivo principal de este proyecto es identificar los factores y patrones clave que contribuyen a que los clientes decidan cancelar sus servicios. Al comprender estas causas, la empresa puede desarrollar estrategias de retención más efectivas y proactivas.

El proyecto abarca desde la limpieza y preprocesamiento de los datos hasta la generación de insights accionables y recomendaciones estratégicas.

## Problema de Negocio

La evasión de clientes representa una pérdida significativa de ingresos y es un desafío constante para las empresas en el sector de las telecomunicaciones. Reemplazar a un cliente que se va es considerablemente más costoso que retener a uno existente. Este análisis busca proporcionar una comprensión profunda de por qué los clientes se van, permitiendo a la empresa tomar decisiones basadas en datos para mejorar la lealtad y la satisfacción del cliente.

## Estructura del Repositorio

* `README.md`: Este archivo, que proporciona una visión general del proyecto.
* `[nombre_de_tu_notebook].ipynb`: El notebook principal de Jupyter que contiene todo el código de análisis, visualizaciones, conclusiones e informe final.
* `data/`
## Fases del Proyecto

El análisis se estructura en las siguientes fases clave:

1.  **Carga y Limpieza de Datos:**
    * Importación de datos desde un archivo **JSON**.
    * Manejo de valores nulos (especialmente en la columna `Total` y la variable objetivo `Churn`).
    * Conversión de tipos de datos (`object` a numérico/categórico).
    * Estandarización y verificación de la consistencia de los datos.

2.  **Análisis Exploratorio de Datos (EDA):**
    * **Distribución de Churn:** Análisis de la proporción general de clientes que evaden.
    * **Análisis de Variables Categóricas:** Exploración de cómo factores como el tipo de contrato, los servicios adicionales, el método de pago y las características demográficas influyen en la evasión, con tablas de contingencia y gráficos de barras agrupadas.
    * **Análisis de Variables Numéricas:** Estudio de la relación entre la evasión y variables como la antigüedad del cliente (`tenure`), los cargos mensuales (`Monthly`) y los cargos totales (`Total`), utilizando estadísticas descriptivas, gráficos de densidad (KDE) y box plots.

3.  **Conclusiones e Insights:**
    * Resumen de los principales hallazgos del EDA, identificando los factores más influyentes en la evasión de clientes.

4.  **Recomendaciones Estratégicas:**
    * Sugerencias accionables y basadas en datos para que la empresa pueda diseñar e implementar programas efectivos de retención de clientes.
