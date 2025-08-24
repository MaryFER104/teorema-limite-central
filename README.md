# teorema-limite-central


Este proyecto ilustra el **Teorema del Límite Central (TLC)** mediante simulaciones y visualizaciones en Python.   
El TLC establece que, bajo ciertas condiciones, la suma (o promedio) de variables aleatorias independientes 
tiende a una distribución normal, sin importar la distribución original de dichas variables.


🚀 Resumen del Proyecto

- Generar muestras aleatorias de distribuciones **Uniforme** y **Gamma**.  
- Calcular sumas y promedios de las muestras para observar su distribución.  
- Comparar las distribuciones originales con la distribución de las medias muestrales.  
- Mostrar cómo las medias muestrales se aproximan a una **distribución normal** al aumentar el tamaño de la muestra.  

---

## 🛠️ Metodología

- **Librerías utilizadas:** `numpy`, `pandas`, `matplotlib`, `scipy.stats`, `seaborn`.  
- **Distribuciones simuladas:**  
  - Uniforme(0,10)  
  - Gamma(k, θ) con distintos parámetros  
- **Experimentos realizados:**  
  1. Generar muestras grandes (n=10,000).  
  2. Calcular medias de muestras repetidas.  
  3. Visualizar histogramas y curvas KDE.  
  4. Comparar diferentes distribuciones para validar el TLC.  

---

## 📈 Resultados

- Las distribuciones **Uniforme** y **Gamma** originales no son normales.  
- Al tomar repetidamente **promedios muestrales**, su distribución se acerca a una normal.  
- Esto confirma el **Teorema del Límite Central**: sin importar la distribución original,
   la distribución del promedio muestral tiende a la normal conforme crece el tamaño de la muestra.  
