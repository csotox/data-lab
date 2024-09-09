# Data Lab by Carlos Rafael Soto

![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)
![Último commit](https://img.shields.io/github/last-commit/csotox/data-lab)
![Repo Size](https://img.shields.io/github/repo-size/csotox/data-lab)


## Descripción del Proyecto

El objetivo de este proyecto es proporcionar diferentes formatos con diferente configuración regional para realizar prácticas de análisis de datos y utilizar diferentes técnicas de ETL.

Los datos de este laboratorio están orientado principalmente a estudiantes y docentes que buscan datos de ejemplos.

### Observaciones

- Los archivos son generados de manera manual.
- Frecuencia de actualización de los datos: cada viernes o sábado.

### Contenido

Puedes interactuar con los datos de tres maneras diferentes:

- Interacción con **Página Web** para el uso de Web Scraping.
- Descarga de archivos **Excel**.
- Simulando llamadas a una **API REST** que devuelve archivos JSON (esta API REST es una simulación).

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

## Guía de uso

### URL para práctica de web scraping

Página Web con maquetación básica de HTML y un poco de CSS, ideal para realizar prácticas de iniciación al web scraping.

- **v1**
  - [Tabla en formato matriz para el año 2024](https://csotox.github.io/data-lab/dolar/chile/web/v1/2024/)

### Descarga de Archivos Excel

Los archivos Excel contienen los valores observados del dólar generado por año y configuración regional. Estos archivos están disponibles para ser descargados desde la siguiente ruta:

- **v1**
  - [Listado de archivos de Excel](https://csotox.github.io/data-lab/dolar/chile/excel/v1)

- **Archivos generados**
  - [2024-CL](https://csotox.github.io/data-lab/dolar/chile/excel/v1/cl/dolarCL_2024.xlsx)
  - [2024-US](https://csotox.github.io/data-lab/dolar/chile/excel/v1/us/dolarUS_2024.xlsx)

### Simulación de la API (JSON)

Este proyecto esta alojado en **GitHub Page** por lo que no contamos con un BackEnd por lo tanto el comportamiento de la API es simulado. Esta simulación básicamente devuelve un **JSON** por cada petición GET a la URL correspondiente. Puedes realizar solicitudes a los siguientes endpoints para obtener los datos por año y configuración regional.

- **v1**
  - [Dólar Chile 2024 (CL)](https://csotox.github.io/data-lab/dolar/chile/api/v1/2024/cl/dolarCL_2024.json)
  - [Dólar Chile 2024 (CL)](https://csotox.github.io/data-lab/dolar/chile/api/v1/2024/us/dolarUS_2024.json)

#### Ejemplo de consumo con `curl`

Si deseas realizar una simulación de la API utilizando `curl`, puedes usar el siguiente comando para obtener los datos de Chile en 2024:

~~~ bash
curl -X GET https://csotox.github.io/data-lab/dolar/chile/api/v1/2024/cl/dolarCL_2024.json
~~~

---

## Licencia

Este proyecto está licenciado bajo la licencia **MIT**. Puedes utilizar, modificar y distribuir el código libremente, pero se requiere atribución al autor original.

Consulta el archivo [LICENSE](LICENSE) para más detalles.

---

## Contacto

Si tienes alguna pregunta, comentario o sugerencia sobre este proyecto, no dudes en ponerte en contacto conmigo:

- **Autor**: Carlos Rafael Soto
- **Email**: algo@algo.com
- **LinkedIn**: [Perfil](https://www.linkedin.com/in/csotox/)
- **YouTube**: [Canal personal](https://www.youtube.com/@CSotoX)

---

## Fuente de datos

Los datos son tomados desde la página del [Banco Central de Chile](https://si3.bcentral.cl/Indicadoressiete/secure/Indicadoresdiarios.aspx)

---

## Roadmap

### Futuras mejoras:
- Salida a producción.
- Añadir más años de datos históricos sobre el valor del dólar.
- Crear automatización que mejore la frecuencia de actualización de los datos.

Si tienes alguna sugerencia de mejora o funcionalidad, no dudes en abrir un **_issue_**.


### Bitacora

- **2024-09-08**: Prueba de concepto
