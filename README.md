# Análisis mercado alquiler Valencia 🏙️

**Objetivo**: estudiar el mercado de alquiler turístico en Valencia y evaluar el posicionamiento de un cliente ficticio con 16 inmuebles frente a la competencia, usando **datos públicos de Airbnb**, **Python** y **Tableau**.

## 🌐 Dashboard
- Tableau Public: [Ver dashboard](https://public.tableau.com/views/valencia-rentals-dashboard)
- Preview:
  ![Dashboard preview](tableau/dashboard_preview.png)

## 📁 Estructura
- `notebooks/` → 01–04 (diseño, limpieza, datamart, análisis) + export a HTML  
- `data/processed/` → `datamart_valencia_total.csv` (base para Tableau)  
- `src/` → utilidades (cálculo de distancia, normalizaciones)  
- `outputs/` → figuras/tablas clave

## 🔧 Tecnologías
Python (Pandas, NumPy, Seaborn, Matplotlib) · Geopy · Jupyter · Tableau

## 🔑 KPIs
- **Precio vs distancia al centro**
- **Precio por capacidad (accommodates)**
- **Gap de precio (mercado – propios) por segmento**
