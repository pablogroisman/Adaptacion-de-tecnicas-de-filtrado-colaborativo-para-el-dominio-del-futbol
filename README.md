# Recomendación de Jugadores de Fútbol con Filtrado Colaborativo

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Este repositorio contiene el código y los recursos desarrollados para mi tesis de licenciatura en Ciencias de Datos, titulada: **"Investigación sobre la aplicación de técnicas de filtrado colaborativo para la recomendación de jugadores a equipos de fútbol"**.

## 📝 Descripción del Proyecto

Este proyecto explora la adaptación y aplicación de algoritmos avanzados de sistemas de recomendación, inspirados en las soluciones ganadoras del Grand Netflix Prize, al dominio del fútbol profesional. El objetivo principal es ir más allá de las métricas de rendimiento tradicionales (como goles y asistencias) para predecir la compatibilidad y el rendimiento potencial de un jugador en un nuevo equipo, basándose únicamente en su historial de rendimiento en clubes anteriores.

La investigación implementa y evalúa un espectro de modelos de filtrado colaborativo, incluyendo:
-   **Predictores Base:** Modelos de sesgos para capturar la "calidad" intrínseca de jugadores y equipos.
-   **Modelos de Vecindario:** Enfoques basados en la similaridad de equipos para encontrar contextos de rendimiento parecidos.
-   **Modelos de Factores Latentes:** Técnicas de factorización matricial (SVD, SVD++, TimeSVD++) para descubrir características subyacentes de jugadores y equipos.
-   **Dinámicas Temporales:** Incorporación de la evolución del rendimiento a lo largo de las temporadas.
-   **Blending de Modelos:** Ensambles que combinan las predicciones de múltiples modelos para mejorar la precisión final.

El repositorio contiene el código para el preprocesamiento de datos, la implementación de los modelos, el entrenamiento, la evaluación y el análisis de resultados.

## 📂 Estructura del Repositorio

A continuación se detalla la estructura principal del repositorio:

-   `tesis.pdf`: Versión final del documento de la tesis.
-   `data/`: Carpeta para alojar el dataset tomado de BeSoccer. 
-   `notebooks/`: Jupyter Notebooks utilizados para la exploración de datos, visualización y análisis de resultados.

## 🛠️ Instalación y Uso

Para ejecutar este proyecto se puede explorar los Jupyter Notebooks en la carpeta `notebooks/` para un análisis paso a paso.

## 📈 Resultados Principales

La evaluación de los modelos reveló una interesante tensión entre la complejidad del modelo y el rendimiento predictivo. Modelos más simples como el `basicSVD` o el `Item_Vector_Model` demostraron ser robustos y competitivos. El blending de modelos, combinando las predicciones de los modelos de CF con estadísticas clásicas del fútbol, arrojó los mejores resultados globales.

El análisis cualitativo mostró que diferentes modelos exhiben distintas "personalidades", con algunos recomendando "estrellas" globales y otros, jugadores de nicho más específicos.

Para un análisis detallado de los resultados, por favor consulta el **Capítulo 5 y 6** de la tesis (`tesis/tesis.pdf`).

## 🎓 Autor

-   **Pablo Groisman**
    -   GitHub: [@tu_usuario_de_github](https://github.com/tu_usuario_de_github)
    -   LinkedIn: [Tu Perfil de LinkedIn](https://www.linkedin.com/in/tu_perfil/)
