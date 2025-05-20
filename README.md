# Universidad Politécnica Salesiana  
![image](https://github.com/user-attachments/assets/75f69835-9635-48a4-831d-d6e6df11f0fe)

**Carrera:** Ingeniería en Computación  
**Periodo:** 2025 - 2025
**Estudiante:** Jorge Cristobal Lituma Teran


## Introducción Teórica al Cuarteto de Anscombe

El **Cuarteto de Anscombe** es un conjunto de cuatro conjuntos de datos creados por el estadístico Francis Anscombe en 1973. Su objetivo era demostrar la importancia de visualizar los datos antes de analizarlos estadísticamente, ya que conjuntos de datos muy distintos pueden tener estadísticas descriptivas similares, como la media, varianza y correlación.

A pesar de que los cuatro conjuntos tienen casi **idénticos valores estadísticos** —media, desviación estándar, coeficiente de correlación, y regresión lineal—, sus distribuciones son completamente diferentes cuando se visualizan gráficamente. Esto evidencia cómo confiar únicamente en los análisis numéricos puede conducir a interpretaciones erróneas de los datos.

A continuación se muestran las gráficas de ejemplo que representan visualmente los cuatro conjuntos del Cuarteto de Anscombe:

![image](https://github.com/user-attachments/assets/d15230be-c911-4118-b678-0adbacbe4f55)

Fuente: Wikipedia. [Anscombe's Quartet](https://en.wikipedia.org/wiki/Anscombe%27s_quartet)

Cada uno de los cuatro conjuntos tiene aproximadamente los mismos valores estadísticos clásicos:
- Promedio (**media**) de las variables `x` y `y`
- **Varianza** de `x` y `y`
- **Correlación** lineal entre `x` y `y`
- Ecuación de la **regresión lineal**

Sin embargo, cuando se grafican, revelan patrones de distribución completamente diferentes:

1. **Primer conjunto**: una relación lineal clara con puntos alineados y una ligera dispersión.
2. **Segundo conjunto**: una relación no lineal; parece una parábola.
3. **Tercer conjunto**: la mayoría de los puntos están alineados, pero hay un **outlier** (dato atípico) que distorsiona la estadística.
4. **Cuarto conjunto**: todos los puntos tienen el mismo valor de `x` excepto uno, que genera la regresión lineal por sí solo.

Estos conjuntos destacan que las **medidas estadísticas básicas no son suficientes** para entender completamente un conjunto de datos. Una visualización puede revelar **patrones, relaciones no lineales, y valores atípicos** que las estadísticas descriptivas no muestran.


Este conjunto de datos sirve como una lección fundamental en estadística y análisis de datos: **la visualización de datos es esencial** para comprender completamente su estructura y comportamiento.


### Aplicaciones del Cuarteto de Anscombe
- Enseñanza de estadística y análisis de datos.
- Argumento para el uso de gráficos en el análisis exploratorio de datos (EDA).
- Prueba de que los modelos estadísticos deben ser validados gráficamente.

---

## Conclusión

El Cuarteto de Anscombe es una herramienta educativa poderosa. Enseña que **no basta con confiar en los cálculos estadísticos** al analizar un conjunto de datos. Las visualizaciones permiten detectar comportamientos inesperados que los números por sí solos no pueden revelar.


**Referencia:**

Anscombe, F. J. (1973). *Graphs in statistical analysis*. The American Statistician, 27(1), 17–21. doi:[10.1080/00031305.1973.10478966](https://doi.org/10.1080/00031305.1973.10478966)
