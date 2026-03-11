# 📊 Telecom X - Análisis de Evasión de Clientes (Churn)

## 📌 Introducción

La evasión de clientes (Churn) representa uno de los principales desafíos para las empresas de telecomunicaciones, ya que implica la pérdida de ingresos y el aumento en los costos de adquisición de nuevos clientes.

El objetivo de este proyecto es analizar los datos de clientes de **Telecom X** para identificar patrones y factores asociados con la cancelación del servicio. A través del análisis exploratorio de datos, se busca comprender qué características están más relacionadas con la evasión y generar insights que permitan mejorar la retención de clientes.

---

## 🎯 Objetivo del análisis

- Analizar la distribución del churn entre los clientes.
- Identificar patrones en variables categóricas y numéricas.
- Detectar factores que influyen en la evasión de clientes.
- Proponer recomendaciones estratégicas basadas en los resultados del análisis.

---

## 🛠️ Tecnologías utilizadas

- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab

---

## 🔍 Procesamiento y limpieza de datos

Durante el análisis se realizaron los siguientes pasos de preparación de datos:

- Importación de datos desde una API en formato JSON.
- Conversión de los datos a un DataFrame utilizando **pandas**.
- Exploración de la estructura del dataset.
- Identificación de valores nulos y registros duplicados.
- Estandarización de variables categóricas (por ejemplo, "yes" y "no").
- Conversión de columnas numéricas al tipo adecuado.
- Creación de la variable **Cuentas_Diarias**, calculada a partir del cargo mensual dividido entre 30.

---

## 📈 Análisis Exploratorio de Datos

El análisis exploratorio permitió identificar patrones relevantes en la evasión de clientes.

### Distribución del churn

Se analizó la proporción de clientes que permanecen en la empresa frente a aquellos que cancelan el servicio.

En general, se observa que la mayoría de los clientes permanecen en la compañía, aunque existe una proporción significativa de clientes que abandonan el servicio.

### Churn y variables categóricas

Se exploró la relación entre churn y variables como:

- Género
- Tipo de contrato
- Método de pago

El análisis mostró que los clientes con **contratos mensuales (month-to-month)** presentan una mayor tasa de evasión en comparación con aquellos con contratos de uno o dos años.

### Churn y variables numéricas

También se analizaron variables numéricas relevantes como:

- Antigüedad del cliente
- Cargo mensual
- Cargo total
- Gasto diario aproximado

Los resultados sugieren que los clientes con **menor antigüedad** y **mayores cargos mensuales** tienen una mayor probabilidad de cancelar el servicio.

---

## 📊 Principales insights

- Los clientes con **contratos mensuales** presentan una mayor probabilidad de cancelar el servicio.
- Los clientes con **menor tiempo en la empresa** tienen mayor tendencia a abandonar.
- Los **cargos mensuales más altos** parecen estar asociados con mayores tasas de churn.
- Los contratos de mayor duración contribuyen a una **mayor retención de clientes**.

---

## 💡 Recomendaciones

A partir de los resultados obtenidos, se proponen las siguientes acciones:

- Incentivar la migración de clientes hacia **contratos de mayor duración** mediante promociones o descuentos.
- Implementar estrategias de **fidelización durante los primeros meses del cliente**, período en el que se observa mayor riesgo de cancelación.
- Analizar los planes con **cargos mensuales más elevados** para evaluar su competitividad en el mercado.
- Desarrollar modelos predictivos que permitan **identificar clientes con alto riesgo de churn** y aplicar estrategias de retención de forma anticipada.

---

## 🚀 Autor

Proyecto desarrollado por **Rómulo García** como parte del desafío de análisis de datos de Telecom X.
