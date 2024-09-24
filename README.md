# Data Lab by Carlos Rafael Soto

![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)
![Último commit](https://img.shields.io/github/last-commit/csotox/data-lab)
![Tamaño del repositorio](https://img.shields.io/github/repo-size/csotox/data-lab)

## 📖 Descripción del proyecto

Este proyecto tiene como objetivo proporcionar un conjunto de datos en diferentes formatos y con configuraciones regionales variadas, ideales para la práctica de **análisis de datos** y la implementación de diversas técnicas de **ETL** (Extracción, Transformación y Carga). Los datos están diseñados para simular escenarios reales de manejo de información financiera, permitiendo a los usuarios trabajar con formatos comunes en distintos contextos internacionales.

### 🎯 Público objetivo

El laboratorio de datos está orientado principalmente a **estudiantes**, **docentes** y **profesionales** que buscan ejemplos prácticos para aprender y enseñar sobre:

- Manipulación de datos en formatos diversos (Excel, JSON, Web).
- Prácticas de **web scraping**.
- Simulación de **APIs** para el consumo de datos.
- Procesos de **ETL** utilizando diferentes configuraciones regionales.

### 🗂️ Contenido del proyecto

Los archivos proporcionados contienen datos reales (como el valor del dólar en Chile) y están estructurados para facilitar la experimentación con diferentes herramientas de análisis de datos.

### 🌐 Formatos y configuraciones regionales

El proyecto incluye datos en los siguientes formatos:

- **Excel** con configuraciones regionales para **Chile** y **Estados Unidos** (formato de fecha, separadores de decimales, etc.).
- **JSON** con simulaciones de una API REST, representando datos con diferentes estándares internacionales.
- **HTML** para realizar prácticas de **web scraping**.

### ⚠️ Observaciones

- Los archivos se generan manualmente para mantener un control adecuado de los datos.
- La **frecuencia de actualización** de los archivos es semanal, generalmente los días **viernes o sábado**.
- Este laboratorio se mantendrá actualizado con nuevas configuraciones y formatos adicionales conforme las necesidades educativas evolucionen.

---

## 📁 Estructura del proyecto

```bash
data-lab/
  data/
    calidad-data/
      v1/ (Archivo CSV para practicar diferentes técnicas de análisis de calidad de data)
    etl/
  dolar/
    chile/
      api/v1/2024/
          cl/ (Archivos JSON para 2024 Configuración regional CL)
          us/ (Archivos JSON para 2024 Configuración regional US)

      excel/v1/
        cl/ (Archivos Excel con configuración regional CL)
        us/ (Archivos Excel con configuración regional US)

      web/v1/
        2024/ (HTML con información del 2024 para hacer web scraping)

```

## 🚀 Guía de uso

Esta guía te ayudará a interactuar con los diferentes recursos del proyecto, incluyendo páginas web para **web scraping**, la descarga de archivos **Excel** y la simulación de una **API REST** utilizando **JSON**.

### 🌐 URL para práctica de Web Scraping

He creado una página web con una tabla de datos básicos en HTML, diseñada para que los usuarios puedan practicar técnicas de **web scraping**. Esta página incluye una maquetación simple en **HTML** y **CSS**, ideal para quienes recién comienzan a trabajar con scraping de datos estructurados.

#### Versión v1

Tabla en formato matriz para el año:

| **Año** | **Archivo**    | **Enlace**                                                  |
|---------|----------------|-------------------------------------------------------------|
| 2024    | [Ver página](https://csotox.github.io/data-lab/dolar/chile/web/v1/2024) | https://csotox.github.io/data-lab/dolar/chile/web/v1/2024 |
| 2023    | [Ver página](https://csotox.github.io/data-lab/dolar/chile/web/v1/2023) | https://csotox.github.io/data-lab/dolar/chile/web/v1/2023 |
| 2022    | [Ver página](https://csotox.github.io/data-lab/dolar/chile/web/v1/2022) | https://csotox.github.io/data-lab/dolar/chile/web/v1/2022 |
| 2021    | [Ver página](https://csotox.github.io/data-lab/dolar/chile/web/v1/2021) | https://csotox.github.io/data-lab/dolar/chile/web/v1/2021 |
| 2020    | [Ver página](https://csotox.github.io/data-lab/dolar/chile/web/v1/2020) | https://csotox.github.io/data-lab/dolar/chile/web/v1/2020 |

### 📥 Descarga de Archivos Excel

Los archivos Excel contienen los valores observados del dólar, organizados por año y configuraciones regionales para Chile y Estados Unidos. Estos archivos están diseñados para su descarga y posterior análisis en herramientas como Excel o Google Sheets.

#### 📃 Listado de archivos de Excel (v1)

[Lista de descargas de archivos Excel](https://csotox.github.io/data-lab/dolar/chile/excel/v1)

#### 📄 Archivos Disponibles

| **País**                | **Archivo**             | **Año** | **Enlace**                                                                                          |
|-------------------------|-------------------------|---------|-----------------------------------------------------------------------------------------------------|
| Chile (CL)              | Dólar Chile             | 2024    | [Descargar](https://csotox.github.io/data-lab/dolar/chile/excel/v1/cl/dolarCL_2024.xlsx)            |
| Chile (CL)              | Dólar Chile             | 2023    | [Descargar](https://csotox.github.io/data-lab/dolar/chile/excel/v1/cl/dolarCL_2023.xlsx)            |
| Chile (CL)              | Dólar Chile             | 2022    | [Descargar](https://csotox.github.io/data-lab/dolar/chile/excel/v1/cl/dolarCL_2022.xlsx)            |
| Chile (CL)              | Dólar Chile             | 2021    | [Descargar](https://csotox.github.io/data-lab/dolar/chile/excel/v1/cl/dolarCL_2021.xlsx)            |
| Chile (CL)              | Dólar Chile             | 2020    | [Descargar](https://csotox.github.io/data-lab/dolar/chile/excel/v1/cl/dolarCL_2020.xlsx)            |
| Estados Unidos (US)     | Dólar Estados Unidos    | 2024    | [Descargar](https://csotox.github.io/data-lab/dolar/chile/excel/v1/us/dolarUS_2024.xlsx)            |
| Estados Unidos (US)     | Dólar Estados Unidos    | 2023    | [Descargar](https://csotox.github.io/data-lab/dolar/chile/excel/v1/us/dolarUS_2023.xlsx)            |
| Estados Unidos (US)     | Dólar Estados Unidos    | 2022    | [Descargar](https://csotox.github.io/data-lab/dolar/chile/excel/v1/us/dolarUS_2022.xlsx)            |
| Estados Unidos (US)     | Dólar Estados Unidos    | 2021    | [Descargar](https://csotox.github.io/data-lab/dolar/chile/excel/v1/us/dolarUS_2021.xlsx)            |
| Estados Unidos (US)     | Dólar Estados Unidos    | 2020    | [Descargar](https://csotox.github.io/data-lab/dolar/chile/excel/v1/us/dolarUS_2020.xlsx)            |

### 🛠️ Simulación de la API (JSON)

Este proyecto está alojado en **GitHub Pages**, lo que significa que no contamos con un backend real para manejar solicitudes dinámicas. Sin embargo, hemos creado una simulación de **API REST** que devuelve archivos JSON estáticos cuando se realiza una petición GET a las URL correspondientes. Esto permite simular el consumo de datos desde una API para análisis o prácticas de desarrollo de software.

Puedes acceder a los siguientes endpoints para obtener los datos de acuerdo con la configuración regional y el año:

#### 🌐 Endpoints disponibles

| **País**                | **Año** | **Enlace (JSON)**                                                                                 |
|-------------------------|---------|---------------------------------------------------------------------------------------------------|
| Chile (CL)              | 2024    | [Ver JSON](https://csotox.github.io/data-lab/dolar/chile/api/v1/2024/cl/dolarCL_2024.json)        |
| Chile (CL)              | 2023    | [Ver JSON](https://csotox.github.io/data-lab/dolar/chile/api/v1/2023/cl/dolarCL_2023.json)        |
| Chile (CL)              | 2022    | [Ver JSON](https://csotox.github.io/data-lab/dolar/chile/api/v1/2022/cl/dolarCL_2022.json)        |
| Chile (CL)              | 2021    | [Ver JSON](https://csotox.github.io/data-lab/dolar/chile/api/v1/2021/cl/dolarCL_2021.json)        |
| Chile (CL)              | 2020    | [Ver JSON](https://csotox.github.io/data-lab/dolar/chile/api/v1/2020/cl/dolarCL_2020.json)        |
| Estados Unidos (US)     | 2024    | [Ver JSON](https://csotox.github.io/data-lab/dolar/chile/api/v1/2024/us/dolarUS_2024.json)        |
| Estados Unidos (US)     | 2023    | [Ver JSON](https://csotox.github.io/data-lab/dolar/chile/api/v1/2023/us/dolarUS_2023.json)        |
| Estados Unidos (US)     | 2022    | [Ver JSON](https://csotox.github.io/data-lab/dolar/chile/api/v1/2022/us/dolarUS_2022.json)        |
| Estados Unidos (US)     | 2021    | [Ver JSON](https://csotox.github.io/data-lab/dolar/chile/api/v1/2021/us/dolarUS_2021.json)        |
| Estados Unidos (US)     | 2020    | [Ver JSON](https://csotox.github.io/data-lab/dolar/chile/api/v1/2020/us/dolarUS_2020.json)        |

#### 📌 Ejemplo de consumo con `curl`

Para realizar una simulación de una llamada a la API desde la terminal utilizando `curl`, puedes usar el siguiente comando. Este comando realiza una solicitud GET y devuelve el archivo JSON con los datos del dólar observado en Chile en el año 2024.

```bash
curl -X GET https://csotox.github.io/data-lab/dolar/chile/api/v1/2024/cl/dolarCL_2024.json
```

---

## 📊 Fuente de Datos

Debemos diferenciar dos orígenes de datos:

- 🔄 **Datos generados aleatoriamente**.
- 📈 **Datos reales** tomados de alguna fuente oficial.

El valor del dólar para Chile se extrae del **[Banco Central de Chile](https://si3.bcentral.cl/Indicadoresdiarios/secure/Indicadoresdiarios.aspx)**, que proporciona información financiera oficial y precisa sobre el valor del dólar y otros indicadores económicos.

> ⚠️ **Nota importante**: Los datos han sido adaptados para fines educativos y de simulación, por lo que podrían no estar actualizados en tiempo real.

---

## 📄 Licencia

Este proyecto está licenciado bajo la licencia **MIT**, lo que significa que puedes utilizar, modificar y distribuir el código de manera libre, siempre y cuando se reconozca la autoría original. Esto fomenta la reutilización y adaptación del proyecto para otros contextos, asegurando que se respeten los créditos.

Para más detalles sobre los términos de la licencia, consulta el archivo [LICENSE](./LICENSE).

## 📞 Contacto

Si tienes preguntas, comentarios, sugerencias o deseas contribuir al proyecto, no dudes en ponerte en contacto conmigo a través de los siguientes medios:

- **Autor**: Carlos Rafael Soto
- **Email**: [algo@algo.com](mailto:algo@algo.com)
- **LinkedIn**: [Carlos Rafael Soto](https://www.linkedin.com/in/csotox/)
- **YouTube**: [Canal de YouTube](https://www.youtube.com/@CSotoX)

Tu retroalimentación es bienvenida y valorada, y será un gusto responder tus dudas o discutir posibles mejoras.

---

## 🛣️ Roadmap

Este proyecto está en constante evolución. Aquí presentamos algunas de las mejoras planificadas para el futuro:

### 🔧 Futuras mejoras

- **Salida a producción**: Preparar el proyecto para ser usado en entornos educativos de análisis de datos.
- **Automatización**: Implementar automatización para mejorar la frecuencia y precisión de la actualización de los datos, permitiendo que estos se sincronicen de manera automática semanalmente.
- **Nuevo DataSet de Supermercado**: Crear un conjunto de datos simulado para reflejar las ventas diarias de un supermercado, diseñado específicamente para la práctica de **algoritmos de análisis descriptivo** y **análisis predictivo**. Una de las características del dataset será su actualización diaria con nuevos datos, lo que permite trabajar con modelos dinámicos que evolucionan con el tiempo y simular escenarios de ventas y tendencias.

Si tienes alguna idea o sugerencia para mejorar el proyecto, no dudes en abrir un **issue** en el repositorio. Estamos abiertos a colaboraciones que hagan crecer el proyecto.

---

## 📅 Bitácora

A continuación se registra el progreso y los hitos alcanzados durante el desarrollo del proyecto:

- **2024-09-24**: Agregado el archivo **etl/VentasCjile.csv** estructura básica para explicar conceptos básicos de ETL.
- **2024-09-13**: Salida a **PRODUCCIÓN** las estructuras creadas hasta el momento no serán modificadas.
- **2024-09-12**: Se agregó DataSet para escenario de calidad de datos.
- **2024-09-10**: Se agregaron los años 2020, 2021 y 2022. Se actualizó el año 2024 para el dólar en Chile.
- **2024-09-08**: Prueba de concepto inicial lanzada, implementando la simulación de datos del dólar en Chile.

Mantendremos esta sección actualizada para reflejar los avances y cambios significativos en el proyecto.

---
