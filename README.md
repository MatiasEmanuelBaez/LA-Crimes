# Análisis de crimenes en Los Ángeles

## 📋 Descripción del Proyecto

Análisis exploratorio y limpieza de datos sobre reportes criminales en Los Ángeles.
El dataset contiene información detallada de crímenes reportados, con el desafío adicional de posibles errores de transcripción ya que los datos fueron transcritos de formatos físicos originales.

## 🎯 Objetivos del Análisis

### 🔍 **Exploración Inicial**

- Revisar la estructura del dataset y comprender las variables disponibles
- Identificar patrones y tendencias en la criminalidad
- Analizar distribuciones temporales y geográficas

### 🧹 **Limpieza de Datos**

- Detectar y corregir errores de transcripción
- Identificar valores duplicados, nulos o inconsistentes
- Validar la consistencia de los datos categóricos

### 📊 **Visualización**

- Crear visualizaciones claras e informativas
- Comunicar hallazgos de manera efectiva
- Identificar insights relevantes

## 📁 Dataset

**Fuente:** [Kaggle - Crimes in Los Angeles](https://www.kaggle.com/datasets/sudhanvahg/crimes-in-las-angeles/data)

⚠️ Los datos fueron transcritos de reportes en papel, por lo que pueden contener errores de transcripción que requieren validación.

## 🗂️ Diccionario de Datos

### Identificadores y Fechas

| Columna | Descripción |
|---------|-------------|
| **`DR_NO`** | Número oficial de archivo (Año + Área ID + 5 dígitos) |
| **`DATE OCC`** | Fecha de ocurrencia del crimen (YYYY-MM-DD) |

### Ubicación Geográfica

| Columna | Descripción |
|---------|-------------|
| **`AREA`** | ID de estación de policía (1-21) |
| **`AREA NAME`** | Nombre del área geográfica |
| **`Rpt Dist No`** | Código de sub-área |
| **`LOCATION`** | Dirección aproximada (anonimizada) |
| **`LAT` / `LON`** | Coordenadas geográficas |

### Información de la Víctima

| Columna | Descripción |
|---------|-------------|
| **`Vict Age`** | Edad de la víctima |
| **`Vict Sex`** | Sexo (F: Mujer, M: Hombre, X: Desconocido) |
| **`Vict Descent`** | Descendencia/Etnia (Códigos específicos) |

### Detalles del Crimen

| Columna | Descripción |
|---------|-------------|
| **`Crm Cd`** | Código del tipo de crimen |
| **`Crm Cd Desc`** | Descripción del crimen cometido |
| **`Premis Cd`** | Código del lugar donde ocurrió |
| **`Premis Desc`** | Descripción del lugar del crimen |
| **`Weapon Used Cd`** | Código del arma utilizada |
| **`Weapon Desc`** | Descripción del arma |

## 🏛️ Códigos de Descendencia (Vict Descent)

| Código | Descripción |
|--------|-------------|
| **A** | Asiático |
| **B** | Negro |
| **C** | Chino |
| **D** | Camboyano |
| **F** | Filipino |
| **G** | Guamanian |
| **H** | Hispano/Latino/Mexicano |
| **I** | Indio Americano/Nativo |
| **J** | Japonés |
| **K** | Coreano |
| **L** | Laosiano |
| **O** | Otros |
| **P** | Isleño del Pacífico |
| **S** | Samoano |
| **U** | Hawaiiano |
| **V** | Vietnamita |
| **W** | Blanco |
| **X** | Desconocido |
| **Z** | Indio Asiático |

## 🛠️ Metodología de Análisis

### Limpieza de Datos

* Validación de formatos de fecha
* Verificación de rangos de edad lógicos
* Corrección de categorías inconsistentes
* Manejo de valores nulos y duplicados

### Análisis Exploratorio

* Distribución temporal de crímenes
* Patrones geográficos por área
* Tipos de crímenes más frecuentes
* Características demográficas de víctimas

### Visualización

* Mapas de calor geográficos
* Series temporales
* Gráficos de distribución
* Análisis de correlaciones

### Tecnologías Utilizadas

* **Python**: Lenguaje principal de análisis
* **Pandas**: Manipulación y limpieza de datos
* **NumPy**: Cálculos numéricos
* **Matplotlib**: Visualizaciones básicas
* **Seaborn**: Visualizaciones estadísticas
* **Plotly**: Gráficos interactivos
* **Jupyter**: Notebooks de análisis

<br>

*`Proyecto desarrollado como parte de un challenge individual de analisis y presentacion de resultados`*
