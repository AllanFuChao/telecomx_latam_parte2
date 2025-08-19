# Challenge Telecom X - análisis de evasión de clientes - Parte 2: Un Proyecto de Aplicación Práctica

Este repositorio contiene el desarrollo de un proyecto integral de ciencia de datos, cuyo objetivo principal fue aplicar y consolidar los conocimientos adquiridos a lo largo de diversos cursos con ALURA LATAM . El desafío central consistió en predecir el **churn** (abandono de clientes) en una empresa de telecomunicaciones, un problema complejo y de gran valor para el negocio.

Afrontar este proyecto representó un reto considerable, exigiéndome combinar técnicas de limpieza de datos, análisis exploratorio, ingeniería de características y modelado predictivo. Cada fase, desde la formulación del problema hasta la optimización del modelo final, fue una valiosa experiencia de aprendizaje que puso a prueba y expandió mis habilidades técnicas.

---

## 📂 Estructura del Proyecto

El proyecto está organizado de la siguiente manera para facilitar su comprensión y ejecución:

-   `telecomx_latam_part2.ipynb`: Es el cuaderno principal de Jupyter/Google Colab que contiene todo el código, los análisis y las conclusiones del proyecto, desde la carga de datos hasta la evaluación final del modelo.
-   `datos_tratados.csv`: Es el conjunto de datos limpio y pre-procesado que sirve como punto de partida para todo el análisis y modelado.
-   `modelo_clasificacion_churn.pkl`: Es el modelo de clasificación final (Árbol de Decisión), entrenado y guardado, listo para ser utilizado en predicciones de abandono de clientes.
-   `modelo_regresion_final.pkl`: Es el modelo de regresión final (Random Forest), optimizado y guardado, para la predicción de cargos totales. (Por razones de que este archivo tiene un peso mayor de lo que Github puede soportar no esta dentro del repositorio, al ejecutar el cuadro final se producira la descarga de este analisis).
-   `README.md`: Este archivo, que proporciona una visión general del proyecto.

---

## 🛠️ Proceso de Preparación de Datos

Una parte fundamental y desafiante del proyecto fue la preparación de los datos. 

1.  **Clasificación de Variables** 
2.  **Codificación y Normalización**
3.  **Separación en Entrenamiento y Prueba**

---

## 🧠 Justificaciones y Decisiones de Modelado

Durante el proyecto, se tomaron varias decisiones estratégicas que fueron determinantes para el resultado final:

* **Manejo del Desbalance de Clases**
* * **Validación Robusta**
* * **Ingeniería de Características**
 
  
---

## 📊 Insights del Análisis Exploratorio (EDA)

El análisis exploratorio fue esencial para guiar el proceso de modelado. Uno de los hallazgos más importantes fue la visualización del desbalance de clases en la variable `Churn`, lo que justificó todo el enfoque posterior en el manejo de datos desbalanceados.

---

Este proyecto fue arduamente dificil sin la ayuda del IA, pude claramente ver lo dificultad de trabajar con datos y manejarlos en una situación de "trabajo", durante el inicio del proyecto se puede notar la falta de organización y análisis en los datos, lo cual poco a poco la práctica fue realmente buena para ajustar la manera en manejar los datos y los análisis.
