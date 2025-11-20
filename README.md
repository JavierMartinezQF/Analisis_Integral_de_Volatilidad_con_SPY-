# Analisis_Integral_de_Volatilidad_con_SPY-
Análisis Integral de Volatilidad con SPY (S&amp;P 500)


# Volatility Lab  
**Análisis Integral de Volatilidad con SPY (S&P 500)**

Este repositorio contiene un laboratorio completo de volatilidad utilizando datos reales del ETF **SPY**, que replica el índice S&P 500.  
El proyecto combina teoría cuantitativa con implementación práctica en Python, con el objetivo de entender cómo la volatilidad se manifiesta y se utiliza en el pricing de opciones.

---

##  Objetivos del proyecto

- Entender la diferencia entre **volatilidad histórica** y **volatilidad implícita**.
- Aplicar el modelo de **Black–Scholes–Merton (BSM)** a opciones europeas.
- Analizar:
  - El **sesgo de volatilidad (volatility skew)**.
  - La **estructura temporal** de la volatilidad implícita (term structure).
  - La **superficie de volatilidad** en 3D.
- Estudiar el **impacto de cambios en la volatilidad** sobre la ganancia/pérdida de una estrategia con opciones (ejemplo: long call/put).

Este proyecto está pensado como pieza de portafolio para roles de **Quant, Risk, Data Science en Finanzas**, o como material de estudio avanzado.

---

##  Contenido del repositorio

- `Volatility_Lab_SPY.ipynb`  
  Notebook principal del proyecto. Incluye todo el análisis paso a paso:
  1. Volatilidad histórica de SPY.
  2. Volatilidad implícita de una opción real.
  3. Sesgo de volatilidad (skew).
  4. Estructura temporal (term structure).
  5. Superficie de volatilidad en 3D.
  6. Impacto de la volatilidad en una estrategia con opciones.



---

##  Tecnologías y librerías utilizadas

- **Python 3.x**
- `yfinance` – Descarga de datos de mercado (precios y opciones desde Yahoo! Finance).
- `pandas` – Manipulación de datos.
- `numpy` – Cálculos numéricos.
- `matplotlib` – Visualizaciones 2D y 3D.
- `scipy` – Funciones estadísticas y optimización (cálculo de volatilidad implícita).
- `datetime` – Manejo de fechas.

---
“Volatility is not a bug, it’s a feature.”
– Todo buen quant, alguna vez.


## Si tienes comentarios, sugerencias o quieres colaborar:

Autor: Javier Martínez González

E-Mail: javiermg.act@gmail.com

LinkedIn: www.linkedin.com/in/javiermartinezqf
