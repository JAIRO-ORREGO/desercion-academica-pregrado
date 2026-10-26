# Deserción académica de pregrado en una institución de educación superior de Boyacá, 2020-2025

Proyecto de grado – **Proyecto 2**, Especialización en Analítica de Datos, Corporación Unificada Nacional de Educación Superior (CUN).
Autor: Jairo Andrés Orrego Claros · Versión **v0.1** (avance 1: formulación, ETL y análisis exploratorio).

## Objetivo
Desarrollar un análisis de la deserción académica de pregrado en una institución de educación superior de Boyacá, en el periodo 2020-2025, mediante técnicas de analítica de datos, como apoyo al fortalecimiento de la gestión institucional y de las estrategias de permanencia.

## Metodología
El proyecto sigue CRISP-DM, adaptada en la ruta de seis etapas del curso. Esta versión cubre la etapa 1 (formulación y datos) y la ETL y el EDA de la etapa 2 (preparación).

## Contenido del repositorio
| Archivo | Descripción |
|---|---|
| `Desercion_academica_ETL_EDA.ipynb` | Cuaderno de Google Colab: carga desde la API, exploración, ETL con conteos, diccionario de datos y EDA |
| `datos/desercion_academica_pregrado_limpio.csv` | Conjunto de datos limpio: 3.091 registros de pregrado y 16 variables |
| `datos/diccionario_de_datos.csv` | Diccionario de datos de las 16 variables |
| `datos/bitacora_conteos_etl.csv` | Bitácora de la ETL con los conteos antes y después de cada paso |
| `figuras/` | Figuras del análisis univariado y multivariado |

## Reproducibilidad
Abra el cuaderno en Google Colab y ejecute **Entorno de ejecución > Ejecutar todo**. Los datos se leen directamente de la API del portal datos.gov.co, por lo que no se requiere descargar archivos.

Cuaderno en Colab: https://colab.research.google.com/drive/1a0DUz9_L0Y7MGKslB-zcXdlnLU2NX86T?usp=sharing

## Fuente de los datos y licencia
Universidad Pedagógica y Tecnológica de Colombia. (2025). *Deserción académica pregrado y posgrado* [Conjunto de datos]. Portal de Datos Abiertos de Colombia. https://www.datos.gov.co/d/3iew-7wpx

Los datos se publican bajo la licencia **Creative Commons Atribución-CompartirIgual 4.0 (CC BY-SA 4.0)**. Los datos derivados de este repositorio (carpeta `datos/`) se comparten bajo la misma licencia. Por protección de datos personales (Ley 1581 de 2012), el conjunto limpio excluye el tipo de identificación, el lugar de expedición del documento y la fecha de nacimiento exacta, que se reemplaza por la edad y el rango de edad.

## Versiones
- **v0.1** (octubre de 2026): ETL, diccionario de datos y análisis exploratorio univariado y multivariado.
