# TelecomX
# 📊 Análisis de Evasión de Clientes (Churn)

Este proyecto tiene como objetivo analizar los factores que influyen en la **evasión de clientes (Churn)** en una empresa de telecomunicaciones, mediante un enfoque de análisis exploratorio de datos (EDA).

---

## 📌 Objetivo

Identificar patrones de comportamiento en los clientes que cancelan el servicio con el fin de:

- Entender qué variables están asociadas a la evasión.
- Detectar perfiles de clientes con mayor riesgo.
- Sugerir acciones estratégicas para aumentar la retención.

---

## 🛠️ Herramientas Utilizadas

- **Python 3**
- **Pandas**: Manipulación de datos.
- **NumPy**: Operaciones numéricas.
- **Plotly Express / Seaborn / Matplotlib**: Visualización de datos.
- **Google Colab**

---

## 🧪 Proceso

### 1. **Carga y Preparación de Datos**
- Lectura del dataset.
- Conversión de tipos de datos.
- Estandarización de variables categóricas y numéricas.
- Creación de nuevas variables como `Cuentas_diarias` y `Total_servicios`.

### 2. **Análisis Exploratorio de Datos**
- Gráficos de barras y pastel para explorar la distribución de `Churn` frente a variables categóricas (género, contrato, método de pago, etc.).
- Boxplots y histogramas para evaluar la relación entre churn y variables numéricas (`Charges.Total`, `Meses_contrato`, etc.).

### 3. **Análisis de Correlación (Extra)**
- Evaluación estadística de correlaciones con `Churn`.
- Visualización de la matriz de correlación.
- Análisis específico de la relación entre:
  - Servicios contratados y churn.
  - Gasto diario promedio y churn.

---

## 📈 Resultados y Hallazgos

- Los clientes con **contrato mensual** y **pago por cheque electrónico** tienen mayor tendencia a cancelar.
- Clientes con **menos servicios contratados** o **menos tiempo en la empresa** presentan mayor churn.
- La **cuenta diaria alta** puede indicar insatisfacción si no se acompaña de valor agregado.

---

## 💡 Recomendaciones

- Fomentar contratos a largo plazo con beneficios exclusivos.
- Incentivar el uso de métodos de pago automáticos.
- Implementar programas de fidelización durante los primeros 6 meses.
- Desarrollar alertas tempranas para clientes de alto riesgo.

---

## 🚀 Posibles Extensiones

- Construcción de un modelo de **predicción de churn** con machine learning.
- Segmentación de clientes según riesgo.
- Automatización de reportes mensuales de retención.

---

## 📁 Estructura del Proyecto

