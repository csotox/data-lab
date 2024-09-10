# Data Lab by Carlos Rafael Soto

![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)
![Último commit](https://img.shields.io/github/last-commit/csotox/data-lab)
![Repo Size](https://img.shields.io/github/repo-size/csotox/data-lab)


## Descripción del Proyecto

Este proyecto tiene como objetivo proporcionar un conjunto de datos en diferentes formatos y con configuraciones regionales variadas, ideales para la práctica de **análisis de datos** y la implementación de diversas técnicas de **ETL** (Extracción, Transformación y Carga). Los datos están diseñados para simular escenarios reales de manejo de información financiera, permitiendo a los usuarios trabajar con formatos comunes en distintos contextos internacionales.

### Público objetivo

El laboratorio de datos está orientado principalmente a **estudiantes**, **docentes** y **profesionales** que buscan ejemplos prácticos para aprender y enseñar sobre:
- Manipulación de datos en formatos diversos (Excel, JSON, Web).
- Prácticas de **web scraping**.
- Simulación de **APIs** para el consumo de datos.
- Procesos de **ETL** utilizando diferentes configuraciones regionales.

### Contenido del Proyecto

Los archivos proporcionados contienen datos reales (como el valor del dólar en Chile) y están estructurados para facilitar la experimentación con diferentes herramientas de análisis de datos.

### Formatos y configuraciones regionales

El proyecto incluye datos en los siguientes formatos:
- **Excel** con configuraciones regionales para **Chile** y **Estados Unidos** (formato de fecha, separadores de decimales, etc.).
- **JSON** con simulaciones de una API REST, representando datos con diferentes estándares internacionales.
- **HTML** para realizar prácticas de **web scraping**.

### Observaciones

- Los archivos se generan manualmente para mantener un control adecuado de los datos.
- La **frecuencia de actualización** de los archivos es semanal, generalmente los días **viernes o sábado**.
- Este laboratorio se mantendrá actualizado con nuevas configuraciones y formatos adicionales conforme las necesidades educativas evolucionen.

---

### Estructura del Proyecto

~~~ bash
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

~~~

---
## Guía de Uso

Esta guía te ayudará a interactuar con los diferentes recursos del proyecto, incluyendo páginas web para **web scraping**, la descarga de archivos **Excel** y la simulación de una **API REST** utilizando **JSON**.

### URL para Práctica de Web Scraping

He creado una página web con una tabla de datos básicos en HTML, diseñada para que los usuarios puedan practicar técnicas de **web scraping**. Esta página incluye una maquetación simple en **HTML** y **CSS**, ideal para quienes recién comienzan a trabajar con scraping de datos estructurados.

- **Versión v1**:
  - [Tabla en formato matriz para el año 2024 | https://csotox.github.io/data-lab/dolar/chile/web/v1/2024/](https://csotox.github.io/data-lab/dolar/chile/web/v1/2024/)

### Descarga de Archivos Excel

Los archivos Excel contienen los valores observados del dólar, organizados por año y configuraciones regionales para Chile y Estados Unidos. Estos archivos están diseñados para su descarga y posterior análisis en herramientas como Excel o Google Sheets.

- **Listado de archivos de Excel (v1)**:
  - [Descargar archivos Excel | https://csotox.github.io/data-lab/dolar/chile/excel/v1](https://csotox.github.io/data-lab/dolar/chile/excel/v1)

- **Archivos disponibles**:
  - [Dólar Chile 2024 (CL) | https://csotox.github.io/data-lab/dolar/chile/excel/v1/cl/dolarCL_2024.xlsx](https://csotox.github.io/data-lab/dolar/chile/excel/v1/cl/dolarCL_2024.xlsx)
  - [Dólar Estados Unidos 2024 (US) | https://csotox.github.io/data-lab/dolar/chile/excel/v1/us/dolarUS_2024.xlsx](https://csotox.github.io/data-lab/dolar/chile/excel/v1/us/dolarUS_2024.xlsx)

### Simulación de la API (JSON)

Este proyecto está alojado en **GitHub Pages**, lo que significa que no contamos con un backend real para manejar solicitudes dinámicas. Sin embargo, hemos creado una simulación de **API REST** que devuelve archivos JSON estáticos cuando se realiza una petición GET a las URL correspondientes. Esto permite simular el consumo de datos desde una API para análisis o prácticas de desarrollo de software.

Puedes acceder a los siguientes endpoints para obtener los datos de acuerdo con la configuración regional y el año:

- **Versión v1**:
  - [Dólar Chile 2024 (CL) | https://csotox.github.io/data-lab/dolar/chile/api/v1/2024/cl/dolarCL_2024.json](https://csotox.github.io/data-lab/dolar/chile/api/v1/2024/cl/dolarCL_2024.json)
  - [Dólar Estados Unidos 2024 (US) | https://csotox.github.io/data-lab/dolar/chile/api/v1/2024/us/dolarUS_2024.json](https://csotox.github.io/data-lab/dolar/chile/api/v1/2024/us/dolarUS_2024.json)

#### Ejemplo de Consumo con `curl`

Para realizar una simulación de una llamada a la API desde la terminal utilizando `curl`, puedes usar el siguiente comando. Este comando realiza una solicitud GET y devuelve el archivo JSON con los datos del dólar observado en Chile en el año 2024.

~~~bash
curl -X GET https://csotox.github.io/data-lab/dolar/chile/api/v1/2024/cl/dolarCL_2024.json
~~~

Puedes modificar este comando para obtener los datos de otros años simplemente cambiando la URL correspondiente.

---

## Licencia

Este proyecto está licenciado bajo la licencia **MIT**, lo que significa que puedes utilizar, modificar y distribuir el código de manera libre, siempre y cuando se reconozca la autoría original. Esto fomenta la reutilización y adaptación del proyecto para otros contextos, asegurando que se respeten los créditos.

Para más detalles sobre los términos de la licencia, consulta el archivo [LICENSE](./LICENSE).

---

## Contacto

Si tienes preguntas, comentarios, sugerencias o deseas contribuir al proyecto, no dudes en ponerte en contacto conmigo a través de los siguientes medios:

- **Autor**: Carlos Rafael Soto
- **Email**: [algo@algo.com](mailto:algo@algo.com)
- **LinkedIn**: [Carlos Rafael Soto](https://www.linkedin.com/in/csotox/)
- **YouTube**: [Canal de YouTube](https://www.youtube.com/@CSotoX)

Tu retroalimentación es bienvenida y valorada, y será un gusto responder tus dudas o discutir posibles mejoras.

---

## Fuente de datos

Los datos utilizados en este proyecto provienen de fuentes confiables y verificables. Principalmente, se extraen del [Banco Central de Chile](https://si3.bcentral.cl/Indicadoressiete/secure/Indicadoresdiarios.aspx), que proporciona información financiera oficial y precisa sobre el valor del dólar y otros indicadores económicos.

Es importante tener en cuenta que los datos han sido adaptados para fines educativos y de simulación, por lo que podrían no estar actualizados en tiempo real.

---

## Roadmap

Este proyecto está en constante evolución. Aquí presentamos algunas de las mejoras planificadas para el futuro:

### Futuras mejoras:
- **Salida a producción**: Preparar el proyecto para ser usado en entornos educativos de análisis de datos.
- **Datos históricos**: Añadir más años de datos históricos sobre el valor del dólar para aumentar la profundidad del análisis.
- **Automatización**: Implementar automatización para mejorar la frecuencia y precisión de la actualización de los datos, permitiendo que estos se sincronicen de manera automática semanalmente.
- **Nuevo DataSet de Supermercado**: Crear un conjunto de datos simulado para reflejar las ventas diarias de un supermercado, diseñado específicamente para la práctica de **algoritmos de análisis descriptivo** y **análisis predictivo**. Una de las características del dataset sera su actualización diariamente con nuevos datos, lo que permite trabajar con modelos dinámicos que evolucionan con el tiempo y simular escenarios de ventas y tendencias.


Si tienes alguna idea o sugerencia para mejorar el proyecto, no dudes en abrir un **issue** en el repositorio. Estamos abiertos a colaboraciones que hagan crecer el proyecto.

---

## Bitácora

A continuación se registra el progreso y los hitos alcanzados durante el desarrollo del proyecto:

- **2024-09-10**: Se agregaron los años 2020, 2021 y 2022. Se actualizo el año 2024 para el dólar en Chile.
- **2024-09-08**: Prueba de concepto inicial lanzada, implementando la simulación de datos del dólar en Chile.

Mantendremos esta sección actualizada para reflejar los avances y cambios significativos en el proyecto.
