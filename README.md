# Dinámica Inmobiliaria en Bogotá

Proyecto académico desarrollado en el marco del curso **Gerencia de Proyectos de Analytics** de la Maestría en Inteligencia Analítica de Datos.

## Descripción del proyecto

El proyecto busca desarrollar un Sistema de Soporte a las Decisiones (DSS) que integre información inmobiliaria y territorial de Bogotá para identificar sectores donde coinciden patrones de concentración de oferta turística de corta estancia y crecimiento histórico del valor de referencia del suelo.

La solución integra fuentes de información geográfica, inmobiliaria y turística para caracterizar el comportamiento territorial y generar insumos que apoyen el análisis y seguimiento institucional.

## Objetivo

Analizar la dinámica inmobiliaria de Bogotá mediante la integración y exploración de datos territoriales, con énfasis en la distribución de anuncios de Airbnb y la evolución del valor de referencia del suelo entre 2015 y 2026.

## Estructura del repositorio

```text
dinamica-inmobiliaria-bogota-grupo2/
│
├── README.md
│
└── notebooks/
    ├── 01_ETL_Datos_Finales.ipynb
    └── 02_Entendimiento_de_los_datos.ipynb
```

## Contenido

### 1. Extracción y procesamiento de datos

Archivo: `01_ETL_Datos_Finales.ipynb`

Contiene los procedimientos de extracción, limpieza, transformación e integración de las fuentes de información utilizadas para construir la matriz territorial unificada.

### 2. Entendimiento y análisis exploratorio de los datos

Archivo: `02_Entendimiento_de_los_datos.ipynb`

Contiene la revisión de calidad de los datos, análisis descriptivo, evaluación de distribuciones, identificación de valores extremos, comparación territorial y selección exploratoria de sectores mediante indicadores de densidad de Airbnb y crecimiento inmobiliario.

## Tecnologías utilizadas

- Python
- Jupyter Notebook
- Pandas
- NumPy
- GeoPandas
- Matplotlib
- Seaborn
- Shapely

## Alcance

Los resultados corresponden a un análisis exploratorio y territorial. La selección de sectores constituye un insumo para el seguimiento y análisis institucional. No representa evidencia de causalidad entre la oferta turística y el crecimiento inmobiliario.

## Equipo de trabajo

Proyecto desarrollado por el Grupo 2.

## Repositorio

[GitHub: dinamica-inmobiliaria-bogota-grupo2](https://github.com/Informer20/dinamica-inmobiliaria-bogota-grupo2)
