# # 📊 Proyecto Telecom X - Predicción de Cancelación de Clientes (Churn)

Este proyecto corresponde al desafío **Telecom X – Parte 2: Predicción de Cancelación (Churn)**, donde se busca analizar y predecir el abandono de clientes en una empresa de telecomunicaciones mediante técnicas de machine learning y análisis de datos.

---

## 🧠 Objetivo

Predecir la cancelación de clientes (churn) utilizando modelos de clasificación basados en datos históricos. Se busca también identificar los factores más influyentes para diseñar estrategias de retención efectivas.

---

## 📁 Estructura del Proyecto

- 📂 Limpieza y preprocesamiento de datos
- 📈 Análisis exploratorio y correlacional
- 🤖 Entrenamiento de modelos
- 📊 Evaluación y comparación de resultados
- 📌 Conclusiones y recomendaciones

---

## 🔍 Principales Tareas Realizadas

1. **Importación y revisión de datos originales**
2. **Limpieza de columnas irrelevantes y duplicadas**
3. **Codificación de variables categóricas** (One-Hot Encoding)
4. **Análisis de proporciones de cancelación (Churn)**
5. **Balanceo de clases** con SMOTE
6. **Separación de datos en entrenamiento y prueba (80/20)**
7. **Entrenamiento de dos modelos**:
   - Regresión Logística (requiere normalización)
   - Random Forest (no requiere normalización)
8. **Evaluación con métricas:**
   - Accuracy, Precision, Recall, F1-score
   - Matriz de confusión
9. **Análisis de importancia de variables**
10. **Análisis de correlación y visualización**
11. **Conclusiones y estrategias de retención**

---

## 🔑 Variables Clave que Influyen en la Cancelación

- 🌐 Tipo de servicio de internet: **Fibra óptica** está asociada a mayor churn
- 💳 Método de pago: **Cheque electrónico** aumenta el riesgo de cancelación
- 💸 Cargos mensuales elevados: Mayor probabilidad de churn
- 🧾 Tipo de contrato: **Contratos largos** reducen la cancelación
- 📆 Antigüedad del cliente: A mayor tenencia, menor churn

---

## 💡 Estrategias de Retención Sugeridas

- Ofrecer beneficios por contratar a largo plazo
- Mejorar experiencia de usuarios con fibra óptica
- Analizar y ajustar cargos mensuales
- Reemplazar métodos de pago poco amigables
- Fidelizar nuevos clientes con atención personalizada

---

## 📎 Recursos

- 📁 Dataset tratado: [`df_telecom_limpio.csv`](https://gist.githubusercontent.com/jose-ns/c7ed7427338c5661eb1cc9fe5784d7eb/raw/1472691b247b92c06909da1293f03157f801e176/df_telecom_limpio.csv)
- 📔 Google Colab Notebook: [Ver notebook](https://colab.research.google.com/drive/1AsQVCWFOOGuHkPp-mR5AVILRHwULg8Oj)

---

## 🧠 Autor

José Neira — *Diseñaador Ux/UI | Analista de datos*

---
