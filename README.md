# Analisis-Ingresantes-UNCP-2025-II
# Dashboard de Análisis de Ingresantes UNCP 2025-II

## Descripción

Este proyecto presenta un análisis descriptivo de los ingresantes al periodo académico **2025-II** de la **Universidad Nacional del Centro del Perú (UNCP)**, utilizando datos públicos del portal **Exprésate Perú con Datos**.

El objetivo es transformar un conjunto de datos en información útil mediante procesos de limpieza, transformación, análisis y visualización, desarrollando un dashboard interactivo en Microsoft Excel que facilite la interpretación de los principales indicadores del proceso de admisión.

---

## 🎯 Objetivos

- Realizar la limpieza y preparación de los datos para garantizar su calidad.
- Analizar la distribución de ingresantes por escuela profesional, modalidad de admisión, sexo y procedencia.
- Diseñar un dashboard interactivo que facilite el análisis mediante filtros y gráficos dinámicos.
- Aplicar buenas prácticas de análisis de datos utilizando Microsoft Excel y Power Query.

---

## Dataset

**Fuente:** Portal de Datos Abiertos – Exprésate Perú con Datos

**Periodo:** 2025-II

**Registros analizados:** 882

### Variables utilizadas

- FECHA_CORTE
- PERIODO_INGRESANTE
- DEPARTAMENTO
- PROVINCIA
- DISTRITO
- TIPO_ADMISION
- ESCUELA
- SEXO

> **Nota:** La columna `UUID` fue eliminada durante el proceso de limpieza debido a que corresponde a un identificador único y no aporta valor al análisis.

---

##  Limpieza y preparación de datos

Antes de iniciar el análisis se realizó un proceso de preparación del conjunto de datos:

- Eliminación de la columna `UUID`.
- Conversión de `FECHA_CORTE` desde el formato `YYYYMMDD` a tipo fecha.
- Verificación de registros incompletos y valores nulos.
- Corrección de errores de codificación en los nombres de las escuelas profesionales.
- Validación de los tipos de datos de cada variable.
- Organización del conjunto de datos para su utilización en tablas dinámicas y visualizaciones.

---

##  Análisis realizado

El dashboard responde, entre otras, las siguientes preguntas:

- ¿Cuántos ingresantes participaron en el proceso de admisión?
- ¿Qué escuelas profesionales registraron mayor número de ingresantes?
- ¿Cuál fue la modalidad de admisión predominante?
- ¿Cómo se distribuyen los ingresantes según sexo?
- ¿De qué departamentos provienen los ingresantes?

---

## 📊 Dashboard

El dashboard incluye:

- Indicadores clave (KPIs)
  - Total de ingresantes
  - Número de escuelas profesionales
  - Número de modalidades de admisión
  - Número de departamentos de procedencia

- Visualizaciones
  - Ingresantes por escuela profesional
  - Distribución por sexo
  - Ingresantes por modalidad de admisión
  - Procedencia por departamento
  - Comparación entre escuela profesional y sexo

- Segmentadores interactivos
  - Sexo
  - Departamento
  - Modalidad de admisión

---

##  Herramientas utilizadas

- Microsoft Excel
- Power Query
- Tablas dinámicas
- Gráficos dinámicos
- Segmentadores de datos

---

##  Capturas
- 1) Base de Datos
     <img width="1597" height="858" alt="image" src="https://github.com/user-attachments/assets/923b7ddc-b168-4081-a5a7-a650fc104e45" />
- 2) Base de Datos Limpia
     <img width="1480" height="922" alt="image" src="https://github.com/user-attachments/assets/023468b6-dc30-43af-b770-fd5fd8f42f83" />


### Dashboard

```
```
<img width="1282" height="617" alt="image" src="https://github.com/user-attachments/assets/6e71e376-79ec-41b2-9ff7-4a8e3192d891" />

---

## 📌 Principales hallazgos

- La modalidad **Normal Ordinario** concentra la mayor cantidad de 586 ingresantes.
- La procedencia de los estudiantes muestra una mayor concentración en Junin (788) , Huancavelica     (54) y Lima (19).
- Existen diferencias en la distribución por sexo entre algunas escuelas profesionales, existe una    cierta preferencia por la carrera de trabajo social, enfermeria y economia por el sexo femenino y   una preferencia de las carreras de ingenieria de minas, ingenieria electrica, ingeneria             metalurgica y minerales e ingenieria mecanica por el sexo masculino.
- El dashboard permite explorar los datos mediante filtros interactivos para facilitar el análisis.

---

##  Posibles mejoras

- Incorporar Power Pivot y modelo de datos.
- Automatizar la actualización mediante VBA.
- Integrar mapas para visualizar la procedencia geográfica.
- Publicar el dashboard en Power BI para acceso web.

---

## Autor

**Rosa María Dávila Ponce**

Estudiante de Ingeniería interesada en análisis de datos, Business Intelligence y automatización de procesos con Excel.

---

## 📄 Licencia

Este proyecto tiene fines educativos y utiliza datos públicos de la Universidad Nacional del Centro del Perú (UNCP) disponibles en el portal de datos abiertos.
