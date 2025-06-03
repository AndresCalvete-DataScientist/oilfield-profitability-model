## 🛢️ Predicción de rentabilidad en yacimientos petroleros — OilyGiant

### 📌 Introducción

Este proyecto simula el trabajo del departamento de análisis de una empresa petrolera ficticia llamada **OilyGiant**. El objetivo es identificar qué región es más prometedora para perforar nuevos pozos y maximizar la rentabilidad, utilizando datos históricos de producción y un modelo predictivo de machine learning.

El análisis incluye exploración de datos, entrenamiento y evaluación de modelos, y cálculo del beneficio esperado considerando incertidumbre y riesgo.

### Objetivo

- Analizar los datos de producción de tres regiones petroleras.
- Construir un modelo de regresión para predecir la producción futura.
- Calcular la rentabilidad esperada para cada región y evaluar riesgos asociados.
- Recomendar la mejor región para inversión basada en predicción y simulación.

---

### 🧠 Habilidades técnicas demostradas

Este proyecto demuestra competencias técnicas clave en análisis predictivo y evaluación financiera bajo incertidumbre:

- **Análisis exploratorio de datos (EDA)**: visualización de patrones de producción y correlaciones entre variables.
- **Limpieza y transformación de datos**: normalización, revisión de distribuciones y formatos.
- **Modelado predictivo**: entrenamiento de modelos de regresión lineal para estimar producción.
- **Evaluación de modelos**: cálculo del RMSE, R2 y MAE.
- **Simulación de ingresos y riesgos**: estimación de ganancias potenciales usando técnicas de bootstrap.
- **Toma de decisiones bajo incertidumbre**: análisis del riesgo de pérdidas e interpretación estadística.
- **Documentación clara y modular**: estructura coherente del flujo de trabajo, documentación de funciones.

---

### 🛠️ Tecnologías y herramientas utilizadas

- **Python**
- **pandas**: manejo de datos tabulares.
- **scikit-learn**: modelado predictivo y validación.
- **NumPy**: operaciones numéricas y simulaciones.
- **matplotlib / seaborn**: visualización.
- **Funciones clave**: `LinearRegression`, `train_test_split`, `root_mean_squared_error`, `r2_score`, `mean_absolute_error`, `sample`.

---

### ✅ Resultados y conclusiones

- Se entrenó un modelo de regresión lineal para cada región con buen desempeño (RMSE razonable).
- Se calcularon los ingresos esperados para cada región bajo una inversión limitada.
- La región seleccionada como la más rentable muestra:
  - Alto valor esperado de retorno.
  - Riesgo de pérdida inferior al 2.5% bajo el umbral de decisión.
- El análisis ayuda a justificar decisiones de inversión basadas en datos y probabilidad.

---

### 📈 Posibles mejoras futuras

- Probar modelos más complejos como `RandomForestRegressor`.
- Incorporar más variables geológicas o económicas para mejorar la predicción y análisis.
- Implementar evaluación cruzada para validar modelos.

---

### 👨‍💻 Autor

**Andrés Calvete**  
Científico de Datos Junior  
[LinkedIn](https://www.linkedin.com/in/andrescalvete/)  
ascalvete@hotmail.com
