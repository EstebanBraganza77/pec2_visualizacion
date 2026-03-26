# 📊 PEC 2 – Visualización de Datos

Este repositorio contiene las visualizaciones desarrolladas para la PEC 2, donde se exploran distintas técnicas de representación gráfica con el objetivo de entender su adecuación según el tipo de datos y el propósito comunicativo.

🔗 Página principal:  
https://estebanbraganza77.github.io/pec2_visualizacion/

---

## 🌍 1. Mapa Coroplético (Choropleth Map)

🔗 Ver visualización:  
https://estebanbraganza77.github.io/pec2_visualizacion/choropleth.html

### 📌 Descripción
Este gráfico representa la **esperanza de vida por país** mediante un mapa coroplético.

Cada país está coloreado según su valor, utilizando una escala de color donde:
- Tonos verdes → mayor esperanza de vida  
- Tonos rojos → menor esperanza de vida  

### 🎯 Objetivo
Permitir una **lectura rápida de patrones geográficos**, identificando regiones con valores altos o bajos.

### ⚠️ Consideraciones
- Se han utilizado **códigos ISO** para asegurar la correcta correspondencia entre datos y mapa.
- Los países en **color gris** representan aquellos sin datos o que no han podido ser asociados correctamente.

---

## 🧇 2. Gráfico de Gofre (Waffle Chart)

🔗 Ver visualización:  
https://estebanbraganza77.github.io/pec2_visualizacion/waffle_chart.html

### 📌 Descripción
Este gráfico muestra el **porcentaje de recaudación de películas respecto a su presupuesto**, agrupadas por rangos de puntuación IMDB.

Cada panel representa un rango de puntuación y contiene una cuadrícula de 100 elementos donde:
- Cada cuadrado = 1%  
- Color azul → porcentaje recaudado  
- Gris → parte no recuperada  

### 🎯 Objetivo
Facilitar la **comparación visual de proporciones** entre distintos grupos de películas.

### ⚠️ Consideraciones
- Es una técnica muy intuitiva, aunque menos precisa para comparaciones detalladas.
- Ideal para representar partes de un todo.

---

## 🐝 3. Gráfico de Enjambre (Beeswarm Plot)

🔗 Ver visualización:  
https://estebanbraganza77.github.io/pec2_visualizacion/beeswarm.html

### 📌 Descripción
Este gráfico representa la **distribución de puntuaciones IMDB por género**.

Cada punto corresponde a una película y se ha aplicado un desplazamiento vertical (jitter) para evitar el solapamiento, generando el efecto de enjambre.

### 🎯 Objetivo
Mostrar la **distribución completa de los datos**, permitiendo observar:
- Densidad  
- Dispersión  
- Valores atípicos  

### ⚠️ Consideraciones
- Técnica muy potente para análisis exploratorio
- Puede ser menos intuitiva para usuarios no familiarizados

---

## 🎯 Conclusión

Cada técnica responde a un tipo de necesidad diferente:

- 🌍 Choropleth → análisis geográfico  
- 🧇 Waffle → proporciones  
- 🐝 Beeswarm → distribuciones  

Este proyecto demuestra cómo la elección de la visualización adecuada depende del tipo de datos y del objetivo de comunicación.

---
