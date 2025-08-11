# challenge-3-Telecom-X-parte-2
# 📈 Proyecto de Predicción y Análisis de Deserción de Clientes – Telecom X

Este repositorio presenta el desarrollo de un estudio integral orientado a **detectar, analizar y predecir** la cancelación de clientes (*churn*) en la compañía ficticia **Telecom X**.  
El trabajo abarca desde la preparación de los datos hasta la generación de modelos predictivos, con el propósito de apoyar la toma de decisiones estratégicas para la retención de usuarios.

---

## 🎯 Propósito del Proyecto

La meta principal es reconocer patrones de comportamiento y variables determinantes que contribuyen a la pérdida de clientes.  
Estos hallazgos ofrecen a la empresa la posibilidad de anticiparse al churn y aplicar medidas proactivas para fidelizar a su base de usuarios.

---

## 🗂 Estructura y Desarrollo

### 1️⃣ **Procesamiento y Preparación de Datos**
- Conversión y normalización del archivo **JSON** inicial para segmentar la información en múltiples DataFrames.  
- Depuración de valores vacíos o inconsistentes, además de la estandarización de variables categóricas y numéricas.  
- Creación de métricas adicionales, como el indicador de **gasto diario** (`cuentas_diarias`).  
- Integración final de todos los conjuntos en un único DataFrame maestro para un análisis global.

---

### 2️⃣ **Análisis Exploratorio (EDA)**
- Estudio de la distribución de churn según variables como: tipo de contrato, método de pago, antigüedad del cliente, entre otras.  
- Análisis visual y estadístico de métricas clave:  
  - `Charges.Total` → Gasto total acumulado  
  - `Tenure` → Tiempo total como cliente  
- Detección de relaciones y patrones que explican la mayor propensión al abandono.

---

### 3️⃣ **Construcción de Modelos Predictivos**
Se entrenaron y evaluaron tres algoritmos con el fin de estimar la probabilidad de churn:
- **Dummy Classifier** → Modelo base de referencia (*accuracy*: 0.50)  
- **Decision Tree Classifier** → Árbol de decisión simple (*accuracy*: 0.80)  
- **Random Forest Class**
