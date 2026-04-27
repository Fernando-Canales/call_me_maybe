# CallMeMaybe: Telecom Call Center Inefficiency Analysis 📞📊

**[English]**
## Project Overview
This repository contains the final capstone project for the TripleTen Data Analytics Bootcamp. The objective was to analyze over 50,000 call records from a telecommunications call center to identify inefficient operators and determine the root cause of a recent decline in service quality. 

Instead of relying on surface-level metrics, I engineered a custom "inefficiency formula" based on missed calls, wait times, and outgoing call volume ratios. 

### Key Business Insights & Impact
* **Custom Metric Engineering:** Identified 205 inefficient operators out of 1,092 by combining data on extreme wait times (90th percentile > 546s) and excessive missed calls.
* **Statistical Hypothesis Testing:** Conducted T-tests (SciPy) which revealed a critical insight: **inefficient operators handle the exact same volume of calls as efficient ones (p-value = 0.93)**. 
* **Data-Driven Recommendation:** Proved that the drop in quality was caused by a massive call volume spike in September, compounded by a lack of software efficiency—not laziness. Recommended a targeted re-training program instead of layoffs, saving the company significant turnover and hiring costs.

### Tech Stack
* **Python:** Pandas, NumPy (Data Wrangling)
* **Statistics:** SciPy (A/B Testing, T-Tests, Hypothesis Validation)
* **Visualization:** Matplotlib, Seaborn, Tableau

🔗 **[View the Interactive Tableau Dashboard Here](https://public.tableau.com/views/Dashboard_proyecto_final_tripleten_Fernando_Gutierrez/DashboardCallmeMaybe)**

---

**[Español]**
## Resumen del Proyecto
Este repositorio contiene el proyecto final del bootcamp de Data Analytics de TripleTen. El objetivo fue analizar más de 50,000 registros de llamadas de un centro de atención de telecomunicaciones para identificar operadores ineficaces y determinar la causa raíz de una reciente caída en la calidad del servicio.

En lugar de depender de métricas superficiales, diseñé una "fórmula de ineficacia" personalizada basada en llamadas perdidas, tiempos de espera y proporciones de volumen de llamadas salientes.

### Hallazgos Clave e Impacto Comercial
* **Ingeniería de Métricas:** Se identificaron 205 operadores ineficaces de un total de 1,092 al combinar datos sobre tiempos de espera extremos (percentil 90 > 546s) y exceso de llamadas perdidas.
* **Pruebas de Hipótesis Estadísticas:** Se realizaron pruebas T (SciPy) que revelaron un dato crítico: **los operadores ineficaces manejan exactamente el mismo volumen de llamadas que los eficientes (valor p = 0.93)**.
* **Recomendación Basada en Datos:** Se demostró que la caída en la calidad fue causada por un aumento masivo en el volumen de llamadas en septiembre, agravado por la falta de eficiencia en el uso del software, no por falta de esfuerzo. Se recomendó un programa de reentrenamiento en lugar de despidos, ahorrando a la empresa costos significativos de rotación y contratación.

### Herramientas Utilizadas
* **Python:** Pandas, NumPy (Limpieza y manipulación de datos)
* **Estadística:** SciPy (Pruebas A/B, Pruebas T, Validación de Hipótesis)
* **Visualización:** Matplotlib, Seaborn, Tableau

🔗 **[Ver el Dashboard Interactivo en Tableau Aquí](https://public.tableau.com/views/Dashboard_proyecto_final_tripleten_Fernando_Gutierrez/DashboardCallmeMaybe)**
