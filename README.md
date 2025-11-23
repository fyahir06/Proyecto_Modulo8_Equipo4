# Mercado laboral y desempleo – Dashboard Shiny

Este repositorio contiene un **dashboard interactivo en Shiny** y un **informe en HTML** para analizar el mercado laboral mundial a partir de datos del Banco Mundial. El proyecto forma parte del **Proyecto Módulo 8 – Análisis Estadístico (Equipo 4)** del diplomado.

## Equipo 4

- Cornejo Peralta Luis Axel  
- Domínguez Amaro Aurora  
- Fernández Sánchez Yahir Sebastián  
- Gonzalez García Abimael  
- Mosqueda Nieto Fernanda  

## Descripción del proyecto

El objetivo del proyecto es analizar tres indicadores clave del mercado laboral:

- **Tasa de desempleo (%)**
- **Tasa de participación laboral (%)**
- **Población total**

A partir de estos indicadores se busca:

- Comparar niveles de desempleo entre países.  
- Explorar diferencias por **sexo** (hombres vs. mujeres).  
- Describir la evolución temporal entre **2000 y 2023**.  
- Evaluar si existe una relación entre **participación laboral** y **tasa de desempleo** mediante visualizaciones y un **modelo de regresión lineal**.

El archivo [Ver informe en HTML](./ProyMod8_Analisis.html)  incluye el análisis estadístico más detallado (limpieza de datos, tablas, gráficos y modelo lineal).

## Fuentes de datos

Los datos provienen del **Banco Mundial** y de estimaciones de la **Organización Internacional del Trabajo (OIT)**:

- `WB_GS_SL_UEM_ZS` – **Tasa de desempleo** (% de la fuerza laboral).  
- `WB_WDI_SL_TLF_CACT_NE_ZS` – **Tasa de participación laboral** (población ≥ 15 años).  
- `WB_WDI_SP_POP_TOTL` – **Población total** por país y año.

Los archivos CSV correspondientes se utilizan para construir una base integrada que permite comparar y modelar los indicadores.

## Dashboard
El dashboard te permite:

- Visualizar la **tasa de desempleo (%)** por país y año.
- Explorar la **tasa de participación laboral (%)**.
- Analizar la **población total** por país.
- Filtrar la información por:
  - Año
  - País
  - Sexo (cuando está disponible)
- Interactuar con:
  - Gráficos de líneas
  - Mapas mundiales
  - Diagramas de dispersión
  - Tarjetas con indicadores globales (KPIs)
    
Puedes visualizarlo dando clic [Aquí](https://f3llbj-gonzalez0garc0a0abimael.shinyapps.io/ProyMod8_Dashboard/#section-mapa-interactivo)
