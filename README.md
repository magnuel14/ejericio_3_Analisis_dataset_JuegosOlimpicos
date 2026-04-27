# 🏅 Análisis de Datos – Juegos Olímpicos

## 📌 Descripción del dataset

Este proyecto utiliza un dataset histórico de los Juegos Olímpicos que contiene información sobre atletas, países, disciplinas deportivas y medallas obtenidas a lo largo de diferentes ediciones.

El dataset incluye variables como:

* Año (`year`)
* País (`country_name`)
* Disciplina (`discipline_title`)
* Tipo de participante (`participant_type`)
* Tipo de medalla (`medal_type`)
* Total de medallas (`total_medals`)

---

## 🎯 Objetivo del proyecto

Analizar el comportamiento de los Juegos Olímpicos a través del tiempo, identificando patrones relevantes como:

* Países con mayor cantidad de medallas
* Evolución de medallas por año
* Participación de atletas y equipos
* Deportes con mayor cantidad de medallas

---

## 🧹 Limpieza y transformación de datos

Se realizó un proceso de limpieza que incluyó:

* Eliminación de valores nulos
* Revisión de tipos de datos
* Eliminación de duplicados
* Creación de nuevas variables como:

  * Total de medallas
  * Indicador de medalla (`has_medal`)
* Organización del dataset final en:

```
data/processed/olympics_clean.csv
```

---

## 📊 Análisis y visualización

### 🥇 Top 10 países con más medallas

Se identificaron los países con mayor número de medallas acumuladas en la historia de los Juegos Olímpicos.

![Top países](images/top10_paises_medallas.png)

---

### 📈 Evolución de medallas por año

Se analizó cómo ha cambiado la cantidad de medallas a lo largo del tiempo.

![Evolución](images/evolucion_medallas_anio.png)


---

### 🏆 Deportes con mayor número de medallas

Se identificaron los deportes que han acumulado más medallas en la historia (Top 10).

![Deportes](images/top10_deportes_medallas.png)

---

## 🔍 Hallazgos principales

* Algunos países dominan históricamente el medallero olímpico.
* La cantidad de medallas ha aumentado con el paso del tiempo.
* La participación individual es mayor que la participación en equipo.
* Deportes como atletismo y natación concentran la mayor cantidad de medallas.

---

## 📌 Conclusiones

El análisis permite identificar tendencias importantes en los Juegos Olímpicos, destacando la evolución del evento y la concentración de medallas en ciertos países y disciplinas.

A pesar de las limitaciones, el dataset ofrece información valiosa para comprender el comportamiento histórico del deporte olímpico.

---

## 👨‍💻 Tecnologías utilizadas

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook / VS Code

---

## 📁 Estructura del proyecto

```
data/
 ├── raw/
 └── processed/
      └── olympics_clean.csv

notebooks/
 ├── 01_cleaning.ipynb
 ├── 02_eda.ipynb
 └── 03_visualization.ipynb

images/
 ├── top10_paises_medallas.png
 ├── evolucion_medallas_anio.png
 └── top10_deportes_medallas.png
```
