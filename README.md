<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/b/b0/Logo_Universidad_Polit%C3%A9cnica_Salesiana_del_Ecuador.png" alt="Logo UPS" width="300"/>
</p>

<h1 align="center">Práctica 1: Cuarteto de Anscombe y Regresión Lineal</h1>

<p align="center">
  <strong>Universidad Politécnica Salesiana</strong>
  <br>
  
  Nombre: Daniel Alfredo Collaguazo Malla
  
  Carrera: Ingeniería en Ciencias de la Computación<br>
  
  Periodo: 2025-2025<br>
</p>

# Introducción teórica al Cuarteto de Anscombe

El **Cuarteto de Anscombe**, propuesto por Francis Anscombe en 1973, es un ejemplo paradigmático en el campo de la visualización de datos que demuestra las limitaciones de los descriptores estadísticos clásicos, como la media, la varianza o el coeficiente de correlación. cuando se usan de forma aislada para resumir conjuntos de datos. Este cuarteto consiste en cuatro conjuntos diferentes de once puntos (x, y) que, sorprendentemente, presentan valores estadísticos idénticos: misma media y varianza para cada variable, y la misma línea de regresión lineal ajustada. No obstante, al ser representados gráficamente, estos conjuntos revelan estructuras completamente distintas, como relaciones no lineales, outliers o distribuciones atípicas que los resúmenes numéricos no logran reflejar.

Este experimento estadístico subraya la necesidad de utilizar herramientas visuales para complementar el análisis cuantitativo, ya que una simple gráfica de dispersión puede revelar patrones, anomalías o estructuras que los estadísticos resumen. Tal como se indica en la guía de Minguillón, el Cuarteto de Anscombe es un caso sintético pero eficaz para destacar cómo la visualización de datos permite una comprensión más rica y precisa del comportamiento subyacente de los datos, y cómo puede evitar conclusiones erróneas derivadas de una interpretación puramente numérica.

## Representación gráfica

![Anscombe](https://github.com/user-attachments/assets/5f0b598f-7af5-4068-8aba-e7b005a3a17b)

## Bibliografía

Minguillón, J. (s.f.). *Introducción a la visualización de datos*. Fundació per a la Universitat Oberta de Catalunya. Recuperado de:  
[ http://hdl.handle.net/10609/57624](http://hdl.handle.net/10609/57624)

---

## Carpeta `data/` – Conjuntos de datos

Esta carpeta contiene los archivos de datos utilizados para los ejercicios:

* `anscombe.csv`: clásico conjunto usado en ejemplos de regresión.
* `datasaurus.csv`: incluye variaciones con estadísticas similares pero distribuciones diferentes (Datasaurus Dozen).

---

## Carpeta `R/` – Código fuente y reportes

Aquí se encuentran los archivos desarrollados en clase:

* `Practica1_datasaurosRegresion.Rmd`: documento editable en RMarkdown (similar a un notebook de Jupyter).
* `Practica1_datasaurosRegresion.html`: versión renderizada del análisis en formato HTML.

---

## Herramienta utilizada

Para la implementación de la regresión lineal se utilizó **R** con soporte de las librerías `tidyverse`, `ggplot2` y `datasauRus`. Todos los scripts están disponibles en la carpeta `R`.

---

## Predicción de regresión

Previamente, en clase se explicó cómo sería la regresión de *slant up*, la cual fue la siguiente:

### Regresión estimada por el estudiante
![regresion_wsp](https://github.com/user-attachments/assets/953d08df-1340-4852-901c-4f46786223ff)


### Regresión Real
![regresion_real](https://github.com/user-attachments/assets/1814e3d8-cafe-4ff3-a638-49940680bfa8)

---

## Repositorio

Puedes acceder al repositorio completo del proyecto en GitHub:

🔗 [https://github.com/DanielCollaguazo2003/Anscombe_Regresion](https://github.com/DanielCollaguazo2003/Anscombe_Regresion)
