📊 TheJerseyClub – Data Analysis Project

Proyecto de análisis de datos de ventas de jerseys que incluye limpieza y transformación de datos con Python, análisis exploratorio (EDA) y un dashboard interactivo en Power BI para analizar desempeño de ventas, rentabilidad e inventario.

📁 Estructura del proyecto
TheJerseyClub-DataAnalysis

Analisis EDA TheJerseyClub/
   cleaning_data.ipynb
   overview_general.ipynb
   analisis_producto.ipynb
   analisis_rentabilidad.ipynb
   analisis_temporal.ipynb
   analisis_inventario.ipynb
   conclusiones_estrategicas.ipynb


dashboard/
   jersey_sales_dashboard.pbix

data/
    cleaned data/
      data_jerseys_cleaned.csv
    raw data/
      raw datajerseys.csv
      tabla jerseyx.xlsx
    
docs/ 
    Analisis de inventario.jpg
    Overview General.jpg
    Costos Unitarios.jpg
    rentabilidad.jpg
    
scripts/ 
  cleaning_data.ipynb

    

El proceso de limpieza de datos incluyó:

conversión de columnas de fechas al formato datetime

corrección y completado de valores faltantes en fechas de llegada

limpieza y estandarización de texto en la columna modelo

creación de variables derivadas como temporada y tiempo en llegar

conversión de variables financieras (costo, envío, venta, ganancia) a formato numérico

generación de un dataset limpio listo para análisis exploratorio y visualización en Power BI.

Herramientas utilizadas:

Python

Pandas

Numpy

🔎 Análisis Exploratorio de Datos (EDA)

Se realizaron distintos análisis para entender el comportamiento del negocio:

📈 Análisis temporal

ventas por mes

evolución de ingresos y ganancias

⚽ Análisis por producto

jerseys más vendidos

desempeño por equipo

💰 Análisis de rentabilidad

ROI por equipo

ROI por liga

ganancia por pedido

📦 Análisis de inventario

stock actual

valor del inventario

rotación del inventario

días promedio para vender

📊 Dashboard en Power BI

Se desarrolló un dashboard interactivo con 4 páginas principales:

1️⃣ Sales Overview

Resumen general del negocio:

ingresos totales

ganancia total

margen

jerseys vendidas

ventas por mes

equipos más vendidos

2️⃣ Profitability & ROI

Análisis de rentabilidad:

ROI por equipo

ROI por liga

ganancia por pedido

relación entre ROI y tiempo de venta

3️⃣ Inventory Analysis

Gestión de inventario:

stock actual

valor del inventario

inventario por liga

inventario por equipo

productos con mayor tiempo en inventario

4️⃣ Unit Economics

Análisis de métricas unitarias:

ganancia promedio por jersey

costo promedio

precio promedio

distribución de ganancias

rotación de inventario por talla

📌 Principales insights

Algunos hallazgos del análisis:

ciertas ligas presentan mayor ROI promedio

algunos equipos generan mayor ganancia por unidad

ciertas tallas tienen rotación de inventario más rápida

parte del inventario permanece demasiado tiempo sin vender

Estos insights pueden ayudar a optimizar:

decisiones de compra

gestión de inventario

selección de productos

🛠️ Tecnologías utilizadas

Python

Pandas

Jupyter Notebook

Power BI

Excel

📷 Dashboard
![Analisis de inventario](https://github.com/user-attachments/assets/76ce5198-bf4b-4c60-a4a3-3ac4c78da1fa)
![rentabilidad](https://github.com/user-attachments/assets/296ac9f4-d838-4e9e-ba79-6e3e44c0ae80)
![overview general](https://github.com/user-attachments/assets/85205612-b06b-4c8f-8ecc-11b7b4347a7d)
![Costos unitarios](https://github.com/user-attachments/assets/ac2ad8cd-844a-4bff-9836-a7764309035c)


🚀 Objetivo del proyecto

Demostrar un flujo completo de análisis de datos aplicado a un negocio real, desde la limpieza de datos hasta la creación de visualizaciones e insights para la toma de decisiones.
