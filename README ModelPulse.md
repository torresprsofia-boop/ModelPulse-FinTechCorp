# 📊 ModelPulse — ML Model Performance Dashboard

> Dashboard desarrollado en **Power BI** para analizar y comparar el rendimiento de modelos de Machine Learning aplicados a detección de fraude y clasificación de riesgo financiero.

---

![Dashboard Preview](dashboard_preview.png)

---

## 🏢 Contexto

**Empresa:** FinTech Corp  
**Período:** 2020 – 2022  
**Objetivo:** Evaluar y comparar modelos de ML en tareas críticas del sector financiero, identificando el modelo más eficiente en términos de precisión, F1 Score y tiempo de entrenamiento.

---

## 🚶 Paso a Paso

1. **Exploración de los datos** — análisis inicial del dataset para entender las variables disponibles: modelo, tarea, accuracy, F1 score, tiempo de entrenamiento, horario, dispositivo y país.

2. **Limpieza y preparación** — normalización de los datos y definición de relaciones entre tablas en Power BI.

3. **Creación de visualizaciones** — diseño de gráficos de barras comparativos para cada métrica clave, segmentados por modelo.

4. **Análisis de fraude** — incorporación de visualizaciones por horario, dispositivo y país para entender el comportamiento del fraude.

5. **Tabla de resumen** — construcción de una tabla consolidada con accuracy y F1 score por modelo y tarea.

6. **Diseño del dashboard** — aplicación de tema oscuro con paleta dorada para una presentación profesional y clara.

---

## 🔍 Principales Hallazgos

- 🥇 **XGBoost** es el modelo con mayor accuracy y F1 Score en ambas tareas
- ⏱️ **SVM** presenta el mayor tiempo de entrenamiento; **Regresión Logística** es el más rápido
- 🌙 La **madrugada (0-6hs)** concentra la mayor cantidad de fraudes
- 📱 **Mobile** es el dispositivo con más casos de fraude detectados
- 🌎 **Argentina** lidera en cantidad de fraudes por país en el período analizado

---

## 📈 Visualizaciones Incluidas

- Accuracy por modelo
- F1 Score por modelo
- Tiempo de entrenamiento por modelo
- Fraude por franja horaria
- Fraude por dispositivo
- Falsos positivos y negativos por modelo
- Fraude por país

---

## 🛠️ Tecnologías

- [Power BI Desktop](https://powerbi.microsoft.com/)
- DAX para medidas calculadas
- Modelado de datos relacional

---

## 👤 Autor

> Sofía  mail torreprsofia@gmail.com https://www.linkedin.com/in/sophie-t-878488249/
