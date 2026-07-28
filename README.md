![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-005C84?style=for-the-badge)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex)

# 🐦 Recuperación de Fauna Silvestre de Bizkaia (2022–2025)

Proyecto de análisis de datos desarrollado a partir de información pública del Centro de Recuperación de Fauna Silvestre de Bizkaia (2022–2025).

El proyecto recorre el ciclo completo de un proceso de Data Analytics: obtención, limpieza, validación y preparación de los datos, análisis exploratorio, desarrollo de un dashboard interactivo en Power BI y elaboración de una guía ilustrada en LaTeX para comunicar los principales resultados de forma visual y accesible.

---

# ⭐ Aspectos destacados

- ✔ Obtención de datos abiertos del portal Open Data Bizkaia.
- ✔ Limpieza y estandarización de datos mediante Python.
- ✔ Validación de la información mediante contraste con la fuente oficial.
- ✔ Consultas analíticas desarrolladas en SQL.
- ✔ Dashboard interactivo creado en Power BI.
- ✔ Guía ilustrada diseñada íntegramente en LaTeX (Overleaf).
- ✔ Documentación completa del proyecto en GitHub.

---

# 🎯 Objetivos del proyecto

Este proyecto tiene como finalidad analizar la actividad del Centro de Recuperación de Fauna Silvestre de Bizkaia entre 2022 y 2025 para responder, entre otras, a las siguientes preguntas:

- ¿Qué especies ingresan con mayor frecuencia?
- ¿En qué épocas del año se producen más ingresos?
- ¿Cuáles son las principales causas de ingreso?
- ¿Cómo evoluciona el estado de los animales a lo largo de los años?
- ¿Qué patrones pueden ayudar a comprender mejor la fauna silvestre del territorio?

Además del análisis técnico, el proyecto busca transformar los resultados en un formato accesible mediante una guía ilustrada dirigida a cualquier persona interesada en la biodiversidad. La guía presenta las tres especies con mayor número de ingresos registradas durante el periodo analizado, junto con gráficos, curiosidades y recomendaciones para favorecer el conocimiento y la conservación de la fauna silvestre.

---

# 📂 Conjunto de datos

**Fuente de datos**

Portal Open Data Bizkaia.

Datos públicos correspondientes al Centro de Recuperación de Fauna Silvestre de Bizkaia.

**Periodo analizado**

2022–2025

El conjunto de datos contiene más de **13.000 registros** correspondientes a animales atendidos por el Centro de Recuperación de Fauna Silvestre de Bizkaia. Cada registro incluye información relacionada con:

- especie
- clase zoológica
- causa de ingreso
- estado de ingreso
- evolución del animal
- fechas
- localización de recogida
- otras variables asociadas a cada registro

---

# ✅ Validación y preparación de los datos

Antes de comenzar el análisis fue necesario revisar y preparar toda la información procedente del portal Open Data Bizkaia.

Durante esta fase se realizaron, entre otras, las siguientes tareas:

- Corrección de problemas de codificación de caracteres mediante Python.
- Estandarización y unificación de los archivos correspondientes a los años 2022–2025.
- Revisión de columnas, categorías y valores inconsistentes.
- Preparación del conjunto de datos para su posterior análisis en SQL y Power BI.
- Validación de la información mediante la comparación entre diferentes variables y años del conjunto de datos.

Como parte del proceso de validación, algunas observaciones fueron contrastadas directamente con el equipo responsable del portal Open Data Bizkaia con el objetivo de garantizar la calidad de la información utilizada durante el análisis.

Este proceso permitió trabajar con un conjunto de datos más consistente y obtener resultados más fiables.

---

# ⚙ Metodología

El proyecto siguió las siguientes fases:

```text
Obtención de datos abiertos
          │
          ▼
Preparación y limpieza
   (Python + SQL)
          │
          ▼
Validación de la información
          │
          ▼
Análisis exploratorio
          │
          ▼
Visualización
    (Power BI)
          │
          ▼
Guía ilustrada
      (LaTeX)
```

---

# 📊 Dashboard en Power BI

El dashboard fue diseñado para facilitar la exploración interactiva del conjunto de datos mediante indicadores, gráficos y filtros que permiten responder a las principales preguntas del proyecto.

## 📈 Visión general

![Dashboard General](images/dashboard_general.png)

Incluye indicadores generales del proyecto:

- Total de ingresos
- Evolución anual
- Distribución mensual
- Comparativa entre años

---

## 📊 Evolución temporal

![Dashboard Evolución](images/dashboard_evolucion.png)

Analiza la evolución de:

- Estados de ingreso
- Evolución de los animales
- Tendencias temporales

---

## 🔍 Análisis por especies

![Dashboard Análisis](images/dashboard_analisis.png)

Permite explorar:

- Clases zoológicas
- Especies
- Principales causas de ingreso
- Distribución de registros

---

## 📌 Principales hallazgos

![Dashboard Hallazgos](images/dashboard_hallazgos.png)

Resume visualmente las principales conclusiones obtenidas durante el análisis.

---

# 📖 Guía ilustrada

Además del dashboard, el proyecto incluye una guía ilustrada diseñada íntegramente en **LaTeX (Overleaf)**.

La guía resume los principales resultados del análisis mediante fichas de especies, gráficos y recomendaciones para acercar la información a cualquier persona interesada en la conservación de la fauna silvestre.

<p align="center">

<img src="images/guia_portada.png" width="220">

<img src="images/guia_gaviota.png" width="220">

<img src="images/guia_final.png" width="220">

</p>

---

# 🔎 Principales hallazgos

- 🦅 Las aves constituyen la clase con mayor número de ingresos.

- 🐦 La gaviota patiamarilla es la especie más frecuente.

- 🌱 La primavera y el verano concentran el mayor volumen de ingresos.

- 🚑 La época de cría constituye la principal causa registrada.

- ❤️ Más de la mitad de los animales ingresan vivos.

- 🌍 Los datos muestran la influencia directa de la actividad humana sobre la fauna silvestre.

---

# 🛠 Tecnologías utilizadas

| Tecnología | Uso |
|------------|-----|
| Python | Limpieza y preparación de datos |
| SQL | Consultas analíticas |
| Power BI | Dashboard interactivo |
| LaTeX (Overleaf) | Guía ilustrada |
| GitHub | Documentación y control de versiones |
| Google Sheets | Apoyo en la limpieza de datos y preparación de datos |

---

# 📁 Estructura del proyecto

```text
recuperacion-fauna-bizkaia/

├── dashboard/
│   └── Dashboard Power BI (.pbix)
│
├── data/
│   ├── raw/
│   └── clean/
│
├── guia/
│   ├── main.tex
│   └── PDF final
│
├── images/
│   ├── dashboards
│   ├── guía
│   └── recursos
│
└── README.md
```

---

# 💡 Lo que aprendí

Este proyecto me permitió trabajar con un conjunto de datos reales procedentes de una administración pública, enfrentándome a tareas habituales dentro del ciclo de vida de un proyecto de análisis de datos.

Durante su desarrollo reforcé competencias relacionadas con la limpieza y preparación de datos, la validación de la calidad de la información, el análisis exploratorio, la creación de visualizaciones y la documentación técnica de un proyecto completo.

Más allá del uso de Python, SQL, Power BI o LaTeX, uno de los principales aprendizajes fue la importancia de comprender y validar los datos antes de extraer conclusiones, un paso esencial para realizar análisis fiables y útiles.

---

# 📬 Contacto

<p align="center">

<a href="https://github.com/carolinahm-tech">
<img src="https://img.shields.io/badge/GitHub-carolinahm--tech-181717?style=for-the-badge&logo=github">
</a>

<a href="https://www.kaggle.com/wildina">
<img src="https://img.shields.io/badge/Kaggle-wildina-20BEFF?style=for-the-badge&logo=kaggle">
</a>

<a href="https://www.linkedin.com/in/carolina-hm">
<img src="https://img.shields.io/badge/LinkedIn-Carolina_H.M.-0A66C2?style=for-the-badge&logo=linkedin">
</a>

</p>