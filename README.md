# Tarea 3 - Bases de Datos NoSQL (MongoDB)

**Integrantes:**
- Javier Canepa (201910028-9)
- Iván Weber (202104092-7)

---

## Descripción de la Entrega

Esta tarea corresponde a la **implementación de una base de datos distribuida utilizando MongoDB**, enfocada en lograr **alta disponibilidad** mediante el despliegue de múltiples nodos en contenedores.

La entrega consiste en un archivo comprimido (`.zip`) que contiene todos los documentos necesarios para ejecutar la tarea:

- Un archivo **`.ipynb` (Jupyter Notebook)** que incluye:
  - El código para poblar la base de datos.
  - Las consultas realizadas sobre la misma.

- Un archivo **`.yml` (Docker Compose)** encargado de crear los contenedores que alojan la base de datos MongoDB y sus réplicas (nodos), permitiendo la configuración del clúster para garantizar **tolerancia a fallos y replicación de datos**.

---

## Estructura del Proyecto

| Archivo | Descripción |
|----------|--------------|
| `tarea3.ipynb` | Script en Jupyter Notebook con la creación y consultas de la base de datos. |
| `docker-compose.yml` | Define los contenedores y la configuración de los nodos de MongoDB. |
| `README.md` | Documento de descripción y ejecución del proyecto. |
| `data.json` *(enlace externo)* | Archivo con los datos utilizados para poblar la base de datos. |

---

## Archivo de Datos

El archivo **`data.json`**, que contiene los registros utilizados para poblar la base de datos, posee un tamaño considerable, por lo cual **no fue incluido directamente** en la entrega debido a las restricciones de tamaño en la plataforma.

El archivo puede ser descargado desde el siguiente enlace de Google Drive:

🔗 [Descargar data.json](https://drive.google.com/file/d/1PxW6XCK50vKm9D_BETM-BCm7Ev1_LDqH/view?usp=sharing)

---

## Ejecución

1. Clonar o descomprimir el proyecto en el entorno local.  
2. Iniciar los contenedores de MongoDB con:
   ```bash
   docker-compose up -d
3. Abrir el archivo `tarea3.ipynb` y ejecutar las celdas en orden para poblar y consultar la base de datos.

---

## Tecnologías Utilizadas

* MongoDB (Replica Set con múltiples nodos)
* Docker / Docker Compose
* Python (con librerías `pymongo`, `json`, entre otras)
* Jupyter Notebook

---

*UTFSM - Ingeniería Civil Telemática*
