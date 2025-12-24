# Predicción de Calificaciones de Estudiantes 🎓

Proyecto de **Machine Learning** para predecir las calificaciones de estudiantes a partir de variables académicas y hábitos personales, utilizando **Random Forest Regressor** dentro de un pipeline de scikit-learn.

---

## 📌 Objetivo
Desarrollar un modelo capaz de predecir la nota de un estudiante considerando factores como:
-Horas diarias de estudio
-Porcentaje de asistencia a clase
-Duración y calidad del sueño
-Disponibilidad de internet
-Método de estudio
-Valoración de la instalación institucional
-Nivel de dificultad del examen.

---

## 📂 Estructura del proyecto
1. **Exploración de datos (EDA):** análisis descriptivo y visualización de variables.
2. **Preprocesamiento:** imputación de valores faltantes, codificación categórica (OneHotEncoder) y escalado de variables numéricas.
3. **Selección de características:** uso de RFE para identificar las variables más relevantes.
4. **Modelado:** entrenamiento con RandomForestRegressor y optimización de hiperparámetros (`n_estimators`, `max_samples`).
5. **Evaluación:** métricas de desempeño (R² y RMSE) y análisis de residuos.
6. **Resultados y conclusiones.**

---

## ⚙️ Tecnologías utilizadas
- Python 3
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab

---

## 📊 Resultados principales
- **R² optimizado:** 0.92  
- **RMSE optimizado:** 5.46  
- Las predicciones están más **centradas y menos dispersas**, mostrando un modelo robusto y confiable.

**Features seleccionadas por RFE:**
- `sleep_quality`
- `age`
- `study_hours`
- `class_attendance`
- `sleep_hours`
- `study_method`
- `facility_rating`

---

## 🚀 Cómo ejecutar
1. Clona el repositorio:
   ```bash
   git clone https://github.com/alecorlo1314/prediccion-calificacion-estudiante.git

