# Modelo de Ajuste de Arrhenius

Proyecto desarrollado en **Python** para el curso de **Modelamiento Matemático**, enfocado en el análisis y ajuste de datos experimentales mediante la ecuación de Arrhenius para describir la dependencia de la constante de velocidad de reacción ($k$) con la temperatura absoluta ($T$).

## Fundamento del modelo

La relación de Arrhenius expresa la constante de velocidad en función de la temperatura:

$$k = A \, e^{-\frac{E_a}{R T}}$$

y en su forma linealizada:

$$\ln(k) = \ln(A) - \frac{E_a}{R} \left(\frac{1}{T}\right)$$

donde $A$ es el factor preexponencial o de frecuencia, $E_a$ es la energía de activación, $R$ es la constante universal de los gases y $T$ es la temperatura en kelvin.

## Contenido del repositorio

* Cuaderno de Jupyter / scripts con el procesamiento de datos experimentales, linealización o ajuste no lineal, estimación de parámetros ($E_a$ y $A$), análisis de bondad de ajuste y gráficas comparativas.
* `.gitignore`: Exclusión de archivos temporales, caché y entornos virtuales.

## Herramientas utilizadas

* **Python 3** y **Jupyter Notebook**
* **NumPy** y **SciPy** (cálculo numérico y regresión / ajuste de curvas)
* **Matplotlib** (visualización de datos y modelo ajustado)
