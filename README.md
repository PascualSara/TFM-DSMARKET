# TFM-DSMARKET
TFM en grupo del Máster en Data Scientist &amp; AI (Nuclio Digital School): modelo de forecasting de ventas con XGBoost aplicado a datos de retail.
## 📌 Descripción del proyecto

Este proyecto forma parte de mi Trabajo de Fin de Máster (TFM) y consiste en el desarrollo de un modelo de **predicción de ventas (forecasting)** utilizando técnicas de Machine Learning, concretamente **XGBoost**.

El objetivo es predecir la demanda futura de productos a partir de datos históricos de retail, incorporando información temporal, precios y eventos del calendario.

---

## 🧠 Enfoque del proyecto

El pipeline sigue un enfoque completo de Data Science:

### 1. Preparación de datos

* Transformación de formato wide → long
* Procesamiento eficiente de grandes volúmenes de datos
* Optimización de memoria (reducción significativa del uso de RAM)

### 2. Feature Engineering

* Variables temporales (día, semana, mes, año)
* Eventos (festivos, promociones, etc.)
* Ciclo de vida del producto (`life_progress`)
* Tratamiento de valores faltantes

### 3. Integración de datos

* Unión con dataset de calendario
* Unión con dataset de precios
* Manejo de inconsistencias y datos ausentes

### 4. Modelado

* Modelo basado en **XGBoost**
* Preparación de dataset para entrenamiento
* Enfoque orientado a series temporales

---

## 🛠️ Tecnologías utilizadas

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost

---

## 📊 Datos

Debido al tamaño de los archivos, los datos no están incluidos directamente en este repositorio.

📥 **Descargar datos aquí:**
👉 https://drive.google.com/drive/folders/1Rzz4w5n4w-bd2OaerHVFjd0zY4i4z-vy?usp=sharing

### Archivos necesarios:

* `sales_train_evaluation.csv` → ventas históricas
* `calendar.csv` → información temporal y eventos
* `sell_prices.csv` → precios por producto

📁 Colocar los archivos en una carpeta llamada:

```bash
data/
```

---

## ▶️ Cómo ejecutar el proyecto

1. Clonar el repositorio:

```bash
git clone https://github.com/PascualSara/TFM-DSMARKET.git
```

2. Navegar al proyecto:

```bash
cd TFM-DSMARKET
```

3. Abrir el notebook:

```bash
xgboost_sales_forecasting.ipynb
```

4. Ejecutar todas las celdas

---

## 📈 Resultados

El modelo permite capturar patrones de demanda complejos mediante:

* Variables temporales
* Eventos externos
* Dinámica de precios

Se obtienen predicciones consistentes para forecasting de ventas en retail.

---

## ⚙️ Retos abordados

* 📦 Manejo de grandes volúmenes de datos
* 🧠 Ingeniería de variables complejas
* 🧩 Integración de múltiples fuentes de datos
* ⚡ Optimización de rendimiento

---

## 🚀 Mejoras futuras

* Validación temporal (Time Series Split)
* Optimización de hiperparámetros
* Comparación con otros modelos (LightGBM, Prophet)
* Deploy del modelo

---

## 👤 Autor

**Sara Pascual**
GitHub: https://github.com/PascualSara

---

## ⭐ Notas

Este proyecto está orientado a demostrar habilidades en:

* Data Engineering
* Machine Learning aplicado
* Modelado de series temporales
* Desarrollo de proyectos end-to-end

---
