# 🚦 Análisis de Movilidad Urbana y Economía

## 📌 Descripción del proyecto

Este proyecto analiza la relación entre la **movilidad urbana y la productividad económica**, con especial atención a ciudades latinoamericanas.

El análisis combina información sobre tráfico y congestión urbana con indicadores económicos para explorar cómo las condiciones de movilidad pueden relacionarse con el desempeño económico de las ciudades.

Para ello se utilizan datos del **TomTom Traffic Index** y de **OECD Cities**, realizando un proceso completo de exploración, limpieza, transformación, combinación y análisis de los datos.

El objetivo principal es identificar patrones que puedan servir como apoyo para evaluar posibles necesidades de inversión en infraestructura de transporte.

---

## 🎓 Contexto

Este proyecto fue desarrollado como parte del programa de **Data Analyst de TripleTen**, con el objetivo de aplicar en un caso práctico habilidades de limpieza, transformación, análisis y visualización de datos utilizando Python.

El análisis, desarrollo del código, interpretación de resultados y conclusiones forman parte del trabajo realizado durante el proyecto.

---

## 🎯 Objetivos

Los principales objetivos del proyecto son:

- Explorar y comprender los datasets de movilidad y economía.
- Limpiar y preparar los datos para el análisis.
- Estandarizar columnas, variables y tipos de datos.
- Analizar indicadores de movilidad urbana.
- Integrar información de tráfico con indicadores económicos.
- Explorar la relación entre congestión y PIB per cápita.
- Comparar distintas ciudades latinoamericanas.
- Identificar ciudades que podrían requerir una evaluación más profunda de su infraestructura de transporte.

---

## 📊 Fuentes de datos

El análisis utiliza dos conjuntos de datos principales:

- **TomTom Traffic Index:** información relacionada con tráfico, congestión y movilidad urbana.
- **OECD Cities:** indicadores económicos, demográficos y ambientales de diferentes ciudades.

Entre las variables analizadas se encuentran:

- Congestión y retrasos por tráfico.
- Índice de tráfico.
- Tiempo de viaje.
- PIB per cápita.
- Desempleo.
- Población.
- Contaminación atmosférica (PM2.5).

El análisis se concentra principalmente en los datos correspondientes a **2024**.

---

## 📁 Contenido del repositorio

### `mobility_economy_analysis.ipynb`

Notebook principal de Jupyter que contiene el desarrollo completo del proyecto:

1. Carga y exploración inicial de los datos.
2. Limpieza y preparación.
3. Estandarización de columnas y tipos de datos.
4. Agregación de información de tráfico por ciudad y año.
5. Integración de los datasets de movilidad y economía.
6. Análisis exploratorio de datos.
7. Visualización de resultados.
8. Análisis de valores atípicos.
9. Comparación entre congestión y PIB per cápita.
10. Conclusiones y recomendaciones.

Durante el análisis también se genera el dataset limpio:

`ladb_mobility_economy_2024_clean.csv`

---

## 🛠️ Herramientas utilizadas

El proyecto fue desarrollado utilizando:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔍 Principales hallazgos

El análisis no muestra una relación general claramente definida entre un mayor PIB per cápita y una mayor congestión vehicular.

Existen ciudades con menor PIB per cápita que presentan niveles elevados de congestión, mientras que algunas ciudades con mayor PIB per cápita presentan niveles menores.

Esto sugiere que la congestión urbana puede depender de otros factores, como:

- Tamaño de la población.
- Infraestructura de transporte.
- Disponibilidad y eficiencia del transporte público.
- Características propias de la estructura urbana.

Dentro de la comparación realizada entre **Bogotá, Lima y Buenos Aires**, Bogotá presentó la combinación más marcada de alta congestión y menor PIB per cápita.

Los resultados sugieren que Bogotá podría ser considerada como candidata para una evaluación más profunda de posibles inversiones en infraestructura de transporte. Sin embargo, sería necesario realizar análisis estadísticos adicionales antes de tomar una decisión de inversión.

---

## ▶️ Cómo abrir el notebook en Google Colab

El notebook puede abrirse utilizando Google Colab.

### Opción 1: desde el archivo descargado

1. Descarga `mobility_economy_analysis.ipynb` desde este repositorio.
2. Abre Google Colab.
3. Selecciona **Archivo → Subir cuaderno**.
4. Selecciona el archivo `.ipynb`.

### Opción 2: desde GitHub

1. Abre Google Colab.
2. Selecciona la opción **GitHub**.
3. Busca este repositorio.
4. Selecciona `mobility_economy_analysis.ipynb`.

---

## 🔄 Cómo reproducir el análisis

Para reproducir el proyecto:

1. Abre `mobility_economy_analysis.ipynb`.
2. Asegúrate de disponer de los datasets:
   - `tomtom_traffic.csv`
   - `oecd_city_economy.csv`
3. Modifica las rutas de los archivos si es necesario.
4. Ejecuta las celdas del notebook en orden, desde la primera hasta la última.
5. El notebook realizará las etapas de limpieza, transformación, agregación, combinación, visualización y análisis de los datos.
6. Como resultado del proceso puede generarse el archivo limpio:

   `ladb_mobility_economy_2024_clean.csv`

### ⚠️ Importante

El notebook original utiliza las siguientes rutas para cargar los datasets:

`/datasets/tomtom_traffic.csv`

`/datasets/oecd_city_economy.csv`

Estas rutas corresponden al entorno original donde se desarrolló el proyecto.

Si el notebook se ejecuta en **Google Colab u otro entorno**, será necesario cargar los archivos CSV y modificar las rutas correspondientes.

---

## 🚀 Posibles mejoras futuras

Este proyecto puede ampliarse mediante:

- Análisis estadístico de correlación entre congestión e indicadores económicos.
- Inclusión de más ciudades latinoamericanas.
- Análisis de la relación entre población y congestión.
- Incorporación de indicadores de transporte público e infraestructura.
- Investigación más detallada de valores atípicos.
- Desarrollo de un dashboard interactivo para comparar ciudades.

---

## 👤 Autora

**Tatiana Barthélémy**

Proyecto desarrollado como parte de mi formación en **Data Analysis en TripleTen**.
