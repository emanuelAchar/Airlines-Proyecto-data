# Proyecto Airlines: Proyección de Mejora Financiera

## Tabla de Contenidos
1. [Descripción del Proyecto](#descripción-del-proyecto)
2. [Problema](#problema)
3. [Objetivo](#objetivo)
4. [Requerimientos](#requerimientos)
5. [Plan de Análisis](#plan-de-análisis)
6. [Resultados Esperados e Impacto](#resultados-esperados-e-impacto)
7. [Fases Propuestas](#fases-propuestas)
8. [Herramientas y Tecnologías](#herramientas-y-tecnologías)
9. [Estructura del Proyecto](#estructura-del-proyecto)
10. [Conclusiones](#conclusiones)
11. [Colaboradores](#colaboradores)
12. [Licencia](#licencia)

## Descripción del Proyecto
Este proyecto se centra en la **aviación comercial**, abordando desafíos como fluctuaciones en la demanda de vuelos, variaciones en los precios de los combustibles y la creciente competencia entre aerolíneas. La búsqueda de mantener o aumentar la rentabilidad es crucial para el sector.

## Problema
El objetivo principal es aumentar la rentabilidad a través del análisis de dos flujos:
- *Identificar rutas más y menos rentables.*
- *Optimizar la capacidad y demanda por avión y ruta.*

## Objetivo
Identificar rutas con alto potencial de rentabilidad a través del análisis de la demanda y determinar aquellas que no son rentables para considerarlas en posibles ajustes. Desarrollar un sistema de análisis de datos que optimice la gestión operativa y mejore la experiencia de los pasajeros en las aerolíneas. Esto incluye la creación de dashboards interactivos para maximizar la eficiencia de los recursos y un análisis profundo de los datos de vuelo para detectar oportunidades de mejora. 

## Requerimientos
Como analistas, debemos:
- Identificar patrones de rutas.
- Realizar análisis geoespaciales.
- Analizar la rentabilidad de las rutas actuales.

## Plan de Análisis
1. **Exploración de datos**: Limpieza de datos y eliminación de valores nulos.
2. **Análisis de demanda**: Evaluar la ocupación promedio de las rutas actuales.
3. **Análisis geoespacial**: Mapear rutas existentes y posibles nuevas.
4. **Modelado predictivo**: Evaluar la demanda potencial de nuevas rutas.
5. **Simulación de costos**: Estimar costos de apertura y cierre de rutas.
6. **Recomendaciones**: Informe con recomendaciones de rutas a abrir o cerrar.

## Resultados Esperados e Impacto
- Detectar rutas con alto potencial de demanda.
- Recomendar la discontinuación de rutas no rentables.
- Mejorar la **eficiencia operativa** y **optimizar recursos**.

## Fases Propuestas
- **Procesamiento de datos**: Limpieza y tratamiento de valores faltantes.
- **Análisis exploratorio de datos (EDA)**: Visualización y análisis de patrones.
- **Modelado predictivo**: Anticipar la demanda en nuevas rutas.
- **Evaluación de rentabilidad**: Comparar demanda proyectada con costos operativos.

## Herramientas y Tecnologías
- **Python**: Análisis de datos.
- **SQL**: Almacenamiento y consulta de datos.
- **Pandas y Numpy**: Manipulación de datos.
- **Matplotlib y Seaborn**: Visualización de datos.
- **Geopandas**: Análisis geoespacial.
- **Power BI**: Generación de visualizaciones y reportes interactivos.
- **Google Cloud**: Almacenamiento de datos.

## Estructura del Proyecto
- **Airlines**: Carpeta principal.
  - **Base de Datos**: Archivos sobre conexión y estado de la base de datos.
    - *`Conexión Google Cloud-Power BI`*: Descripción de la conexión.
    - *`Limpieza de Datos y Creación de DDBB Local`*: Proceso de limpieza y creación de base de datos.
    - *`Proyecto Airlines en la Nube`*: Motivos para usar Google Cloud.
  - **Documentación**: Archivos con información variada.
    - *`Guía_Tablas`*: Información sobre las tablas del dataset.
    - *`Limpieza_Tablas`*: Proceso de limpieza del dataset.
  - **Power BI**: Archivos relacionados con reportes y visualizaciones.
    - *`Mockup`*: Representación visual del diseño final.
    - *`Airlines-dashboard`*: Dashboards basados en el reporte.
    - *`Reporte`*: Reporte final del análisis.
  - **Raw_data**: Archivos CSV sin limpiar.

## Conclusiones 

A través de técnicas avanzadas de análisis de datos, hemos logrado identificar rutas no rentables que pueden ser desestimadas y rutas emergentes con alto potencial de demanda. 

El enfoque de **análisis geoespacial**, combinado con el **modelado predictivo**, permitirá al cliente tomar decisiones estratégicas con datos respaldados, optimizando sus recursos y aumentando su competitividad en un mercado dinámico y desafiante.

### Impacto Esperado:
- **Reducción de costos** al eliminar rutas poco rentables.
- **Incremento en ingresos** mediante la apertura de rutas en mercados emergentes.
- **Optimización de operaciones** para una mayor eficiencia y sustentabilidad a largo plazo.

Gracias al uso de herramientas como **Python**, **Power BI**, y **Google Cloud**, el análisis ha sido exhaustivo y visualmente claro, facilitando la toma de decisiones basada en datos sólidos y proyecciones precisas.

Este proyecto ayuda a mejorar la eficiencia operativa y proporciona un marco escalable para futuros análisis dentro del sector de la aviación.

## Colaboradores
- **Verónica Villagra**  
  - Analista de datos
  - **LinkedIn**: [Verónica Villagra](https://www.linkedin.com/in/veronica-villagra)

- **María de los Angeles Páez**  
  - Analista de datos
  - **LinkedIn**: [María de los Angeles Páez](https://www.linkedin.com/in/maria-de-los-angeles-paez)

- **Emanuel Achar**  
  - Analista de datos
  - **LinkedIn**: [Emanuel Achar](https://www.linkedin.com/in/emanuel-achar)

## Licencia
Este proyecto está bajo la licencia MIT. Para más detalles, consulta el archivo [LICENSE](LICENSE).
