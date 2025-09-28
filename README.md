# 📊 Proyecto Final — Bitcoin: ¿Riesgo o Refugio?

## 📌 Descripción
Este proyecto analiza si **Bitcoin (BTC)** se comporta más como un **activo de riesgo** (similar al S&P 500) o como un **activo refugio** (similar al Oro).  
Para ello se ha realizado un **Análisis Exploratorio de Datos (EDA)** y un **Dashboard en Excel**, combinando diferentes fuentes de datos y aplicando técnicas de análisis descriptivo y estadístico.

---

## 🎯 Objetivos del proyecto
1. **Transformación y limpieza de datos**  
   - Integración de datasets de BTC, S&P 500 y Oro.  
   - Homogeneización de formatos (fechas, precios, volúmenes).  
   - Gestión de valores nulos y outliers.

2. **Análisis descriptivo y estadístico**  
   - Visualización de tenedencias y picos másximos y mínimos.  
   - Volatilidad.  
   - Correlación entre activos.  
   

3. **Visualización de resultados**  
   - Gráficos de evolución de precios normalizados (Base 100).  
   - Evolución de la volatilidad.  
   - Scatter plots BTC vs S&P y BTC vs Oro.  
   - Dashboard interactivo en Excel con segmentadores (año, mes).

4. **Informe explicativo**  
   - Documento con análisis y conclusiones sobre si BTC actúa como “oro digital” o como activo de riesgo.

---

## 🗂️ Estructura del repositorio

- Folder Data_sets:
    - BTC.csv (data BTC)
    - fut_oro.csv (data Oro)
    - sp-historical.csv (data S&P)
    - merge.csv (archivo creado sobre merge y limpieza)
    - merge&clean (Jupiter Notebook)
    - charts (Jupiter Notebook, analisis drescriptivo y estadístico)
 
- Dashboard_BTC
- Readme 

---

## 📊 Dashboard
El dashboard interactivo en Excel incluye:
- Segmentadores por **mes** y **año**.  
- KPIs de cada activo (máximo precio, volatilidad media, máximo volumen).  
- Gráficos de evolución de cotización y volatilidad.  
- Comparativas BTC vs S&P y BTC vs Oro.
<img width="1309" height="718" alt="Screenshot 2025-09-28 202924" src="https://github.com/user-attachments/assets/958b28fc-d09d-4e36-8199-f59844ae3b3a" />



> ⚡ Guardado en formato `.xlsb` para evitar límites de Excel en fórmulas largas.

---

## 🛠️ Tecnologías utilizadas
- **Python**: pandas, matplotlib, numpy.  
- **Excel**: tablas dinámicas, segmentadores, dashboard visual.  
- **Jupyter Notebook**: EDA, análisis estadístico, generación de KPIs.  

---

## 📌 Conclusiones

# Informe explicativo — ¿BTC es “oro digital” o un activo de riesgo?

1) Resumen Ejecutivo
Con los datos históricos integrados (BTC, S&P 500 y Oro) y el dashboard construido, el análisis muestra que **Bitcoin se comporta mayoritariamente como un activo de riesgo**, no como un refugio.
A pesar de ello la adopción masiva de los últimos años ha provocado una tendencia extraordinariamente alcista, mucho más que los otros dos activos estudiados y la volatilidad muestra una tendencia muy pronunciada a la baja, llegando a igualarse (y a ser inferior incluso), por primera a la del S&P este 2025. 
De seguir así con esa tendencia, no es para nada imposible un escenario a medio plazo, en que BTC llegue a asemejarse más al Oro. La escasez de BTC (máx. 21 millones una vez minado todo el BTC) puede hacer que la adopción sea exponencialmente masiva y que se pueda llegar a convertir en el activo de reserva de valor del s. XXI, quien sabe si desbancando al propio Oro.

2) Datos y fuentes
Activos: BTC, S&P 500, Oro (2010–2025).  
	-https://www.kaggle.com/
	-https://es.investing.com/
Archivos: merge.csv, notebooks (merge&clean, charts), dashboard Excel.

3) Metodología
•	- Limpieza de datos.  
•	- Retornos diarios, volatilidad, precios base 100.  
•	- Correlaciones y scatter BTC vs S&P / BTC vs Oro. 

---












