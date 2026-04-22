# Análisis del Uso del Tiempo — Ciudad de Buenos Aires (2016)

![Python](https://img.shields.io/badge/Python-3.10-blue) ![Pandas](https://img.shields.io/badge/Pandas-2.0-lightblue) ![Seaborn](https://img.shields.io/badge/Seaborn-0.12-green) ![Status](https://img.shields.io/badge/Status-Completo-brightgreen)

## 📌 Descripción

Análisis cuantitativo de la **Encuesta de Uso del Tiempo 2016** realizada por el Gobierno de la Ciudad de Buenos Aires. El proyecto examina cómo se distribuye el tiempo dedicado al trabajo **remunerado** y **reproductivo** (doméstico y de cuidados) según el **sexo** y el **rango etario** de los habitantes de CABA.

## ❓ Pregunta de investigación

> ¿Existe una doble carga laboral para las mujeres cuando se considera tanto el trabajo remunerado como el reproductivo?

## 🔍 Principales hallazgos

- Las mujeres concentran el **58.6% del trabajo total** (con simultaneidad) a pesar de representar el 57.6% de la muestra.
- La tasa de participación en trabajo reproductivo es del **93.6% en mujeres** vs 87.5% en varones.
- La **simultaneidad amplifica la brecha**: las mujeres realizan múltiples tareas de cuidado en paralelo, lo que su carga real invisible en mediciones estándar.
- El perfil más afectado son las **mujeres de 25 a 49 años**, que combinan alta carga reproductiva con participación activa en el mercado laboral.

## 📊 Visualizaciones

| Gráfico | Descripción |
|---|---|
| Distribución del trabajo total | Donut chart con/sin simultaneidad por sexo |
| Desagregación del trabajo | Remunerado vs reproductivo apilado por sexo |
| Tasas de participación | % de cada grupo que realiza cada tipo de trabajo |
| Heatmap por rango etario | Distribución del trabajo reproductivo por edad y sexo |

## 🗂️ Estructura del repositorio

```
├── uso_del_tiempo_portfolio.ipynb   # Notebook principal
├── Data_set_encuesta_uso_de_tiempo_2016.csv  # Dataset original
└── README.md
```

## 🛠️ Herramientas utilizadas

- **Python 3.10**
- **Pandas** — limpieza, transformación y análisis de datos
- **Matplotlib / Seaborn** — visualización
- **Jupyter Notebook**

## 📁 Fuente de datos

Dirección General de Estadística y Censos — GCBA (2017).  
*Encuesta de Uso del Tiempo 2016*. Disponible en [Buenos Aires Data](https://data.buenosaires.gob.ar/).

## 👤 Autor

**Ignacio Javier D'Amico**  
[LinkedIn](https://linkedin.com/in/[tu-usuario]) · [Portfolio](https://[tu-link])
