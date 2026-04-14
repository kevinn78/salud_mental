# salud_mental
Análisis y limpieza de datos para descubrir cómo los hábitos de sueño y el entorno de trabajo afectan la salud mental."

# Evaluación Parcial 1: Programación para la Ciencia de Datos

### Integrantes:
* [Kevin  Hidalgo]
* [Diego Sepúlveda]
* [Martin Arroyoz]

---

### 1. Origen y Descripción de los Datos
Los datos provienen de un dataset de **Salud Mental en Entornos Laborales**. El archivo original (`Dataset_salud_mental.zip`) contiene registros sobre niveles de estrés, horas de sueño y variables demográficas como país y género.

**Objetivo:** Limpiar y transformar estos datos para que sean aptos para un modelo de Machine Learning mediante el uso de Pipelines.

---

### 2. Justificación del Entorno
Hemos preferido utilizar **Google Colab** por las siguientes razones:
* **Colaboración en la nube:** Permite el acceso simultáneo y no depende de la potencia de hardware local.
* **Integración con Drive:** Facilita la gestión de archivos crudos y procesados de manera directa.
* **Facilidad con GitHub:** Google Colab permite realizar "commits" y guardar copias directamente en repositorios de GitHub, agilizando el control de versiones sin configurar entornos locales complejos.

---

### 3. Fases del Proyecto
1. **Diagnóstico:** Identificación de nulos y errores geográficos.
2. **Limpieza Artesanal:** Tratamiento de NaNs, Duplicados y Outliers (Sueño 2-14 hrs).
3. **Ingeniería de Características:** Creación de alertas de salud mental.
4. **Pipeline:** Transformación industrial con `StandardScaler` y `OneHotEncoder`.
5. **Visualización:** Análisis exploratorio (EDA).

---

## Cómo ejecutar el proyecto
1. Abrir el archivo `Proyecto.ipynb` en Google Colab.
2. Ejecutar todas las celdas en orden (`Ctrl + F9`).
3. El dataset se cargará automáticamente desde este repositorio.
4. El archivo final procesado se generará en la carpeta `data/`.
