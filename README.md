# Pruena_Tecnica_Etraining-
Proyecto de análisis de datos que integra información de ventas y clima mediante un proceso ETL, realiza análisis descriptivo y un modelo de regresión lineal para evaluar la relación entre la precipitación diaria y el volumen de ventas.

---

## Descripción de los archivos

### 📘 Notebook (documento principal)
**Archivo:** `Prueba Tecnica Etraining.ipynb`  

Contiene el desarrollo completo de la prueba técnica, incluyendo:
- Extracción de datos desde MySQL y MongoDB Atlas  
- Proceso de limpieza, transformación e integración de datos (ETL)  
- Análisis descriptivo completo del dataset final  
- Construcción de un modelo predictivo basado en regresión lineal  
- Visualización de resultados y análisis de patrones  
- Conclusiones y recomendaciones  

Este notebook constituye el **documento principal de la entrega y validación**.

---

### 🐍 Script en Python
**Archivo:** `Prueba Tecnica Etraining.py`  

Versión en script del notebook, generada como respaldo del desarrollo en Python.  
No es el documento principal, pero permite ejecutar el flujo ETL y análisis fuera del entorno de notebooks.

---

### 📂 Dataset final
**Archivo:** `df_modelo_fastfood.xlsx`  

Dataset resultante del proceso ETL, limpio y estructurado, que integra:
- Información de ventas
- Datos de tiendas
- Sensor meteorológico más cercano
- Precipitación diaria asociada  

Este archivo fue exportado para su consumo en herramientas de Business Intelligence.

---

### 📊 Visualización en Power BI
**Archivo:** `FastFood.pbix`  

Dashboard desarrollado en Power BI que permite explorar visualmente:
- La relación entre precipitación y volumen de ventas
- Patrones y tendencias identificadas en el análisis  

Funciona como complemento visual del análisis realizado en el notebook.

---

## Metodología

1. **Extracción:**  
   Datos transaccionales desde MySQL y datos meteorológicos desde MongoDB Atlas.
2. **Transformación (ETL):**  
   Limpieza, normalización, integración geoespacial y agregación temporal.
3. **Análisis descriptivo:**  
   Evaluación de estructura, calidad de datos, estadísticos y patrones.
4. **Modelado predictivo:**  
   Regresión lineal para analizar el impacto de la precipitación en las ventas.
5. **Visualización y conclusiones:**  
   Interpretación de resultados y comunicación de hallazgos.

---

## Ejecución
El análisis puede ejecutarse directamente desde el notebook en Google Colab o Jupyter Notebook.  
Los archivos Excel y Power BI corresponden a salidas del proceso ETL y análisis.

---

## Conclusión
El proyecto permite identificar una relación moderada entre la precipitación diaria y el volumen de ventas, destacando la influencia de factores externos en el comportamiento del consumidor y sentando bases para análisis futuros con variables adicionales.
