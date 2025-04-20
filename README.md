# walmart-BI-Dashboard
Walmart Sales Dashboard (Análisis de ventas, productos, utilidades y desempeño por región)

# 📊 Walmart Sales Dashboard

Este proyecto presenta un dashboard interactivo desarrollado en **Power BI**, complementado con código en **Python**, para analizar los datos de ventas de Walmart. Es parte de mi portafolio personal para mostrar habilidades de visualización, análisis de datos y storytelling con herramientas de BI.

---

## 🧠 Objetivo

Explorar patrones de ventas, utilidad y volumen de productos, con el fin de identificar oportunidades de negocio, entender el desempeño por región y categoría, y demostrar el uso profesional de Power BI y Python.

---

## 🛠️ Herramientas utilizadas

- **Power BI Desktop** (Visualizaciones y diseño del dashboard)
- **Python** (Análisis y gráficos usando `pandas`, `matplotlib` y `seaborn`)
- **Excel** (Fuente de datos original)
- **Git & GitHub** (Control de versiones y exposición del proyecto)

---

## 📁 Estructura del Proyecto

---

## 👀 Visualizaciones Incluidas

- KPI's principales (Ventas, Utilidad, Cantidad)
- Ventas por categoría y subcategoría
- Top 10 productos más vendidos
- Análisis por estado (mapa y tabla)
- Visualización generada con Python (Seaborn)

---

## 🧭 Cómo navegar el dashboard

- Usa los **filtros interactivos** (categoría, estado, fechas) para explorar los datos
- Pasa el cursor sobre los gráficos para ver los detalles
- Presiona el botón 🔄 **“Borrar filtros”** para reiniciar la vista
- Recorre las páginas inferiores del tablero para ver cada sección:

  1. **Summary**
  2. **Analysis by product and category**
  3. **Analysis by state**
  4. **Customer Analysis**
  5. **Insight Outliers**

---

## 📸 Capturas del Dashboard

### 🔹 Visión General
![Dashboard Main](images/dashboard_main.png)

### 🔹 Top Productos
![Top 10](images/top_products.png)

---

## 🧩 Integración con Python

Se incluye una visualización generada desde un script Python embebido en Power BI.

```python
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt

