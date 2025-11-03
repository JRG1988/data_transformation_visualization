# 🧩 Análisis y Transformación de Datos con Python (Instacart)

Este proyecto forma parte de mi portafolio como **Analista de Datos Junior**.
Su objetivo es **analizar, transformar y visualizar información de pedidos de la tienda Instacart**, utilizando herramientas de análisis de datos en Python.

El proyecto se enfoca en **limpieza, unión de datasets y análisis exploratorio** para obtener conclusiones sobre el comportamiento de compra de los usuarios.

---

## 📘 Descripción del proyecto

El análisis se realizó con cinco archivos principales que contienen información sobre pedidos, productos, departamentos y pasillos de la plataforma Instacart.

Durante el proyecto se llevaron a cabo las siguientes etapas:

1. **Importación y carga de datos**

   * Lectura de los cinco archivos CSV.
   * Verificación de tipos de datos y valores nulos.

2. **Transformación y unión de datos**

   * Limpieza de duplicados y datos faltantes.
   * Unión de tablas por claves comunes (`product_id`, `order_id`, etc.).
   * Estandarización de nombres de columnas.

3. **Análisis exploratorio**

   * Identificación de patrones de compra.
   * Categorización de productos por departamentos y frecuencia.
   * Cálculo de métricas relevantes.

4. **Visualización**

   * Creación de gráficos para representar los resultados mediante `matplotlib` y `seaborn`.
   * Visualización de productos más comprados y comportamiento de los usuarios.

---

## 🧠 Habilidades aplicadas

* Análisis exploratorio de datos (EDA)
* Limpieza y transformación de datos con **pandas**
* Unión y manejo de múltiples fuentes de datos
* Visualización de información con **matplotlib** y **seaborn**
* Pensamiento analítico y comunicación de resultados

---

## 🛠️ Herramientas y librerías utilizadas

| Herramienta                | Uso principal                             |
| -------------------------- | ----------------------------------------- |
| **Python**                 | Lenguaje base del análisis                |
| **Pandas**                 | Limpieza, unión y transformación de datos |
| **Matplotlib / Seaborn**   | Visualización y gráficos                  |
| **NumPy**                  | Operaciones numéricas                     |
| **Jupyter / Google Colab** | Ejecución del notebook                    |

---

## 📂 Estructura del repositorio

```
data_transformation_visualization/
│
├── data/
│   ├── aisles.csv
│   ├── departments.csv
│   ├── instacart_orders.csv
│   ├── order_products.csv
│   └── products.csv
│
├── data_transformation_visualization.ipynb
└── README.md
```

---

## ▶️ Cómo ejecutar el proyecto

1. Descarga o clona el repositorio:

   ```bash
   git clone https://github.com/JRG1988/data_transformation_visualization.git
   ```

2. Abre el notebook en **Google Colab** o **Jupyter Notebook**.

3. Si usas Colab, **sube los archivos CSV** de la carpeta `/data` antes de ejecutar.

4. Ejecuta las celdas del notebook en orden para reproducir el análisis y las visualizaciones.

---

## 📊 Resultados destacados

* Se identificaron los **productos y departamentos más comprados**.
* Se analizaron los **hábitos de compra recurrentes** de los usuarios.
* Se desarrollaron **gráficos claros y visuales** que muestran tendencias y categorías con mayor frecuencia de pedidos.

---

## 🧩 Nota técnica

El archivo `order_products.csv` tiene un tamaño considerable.
Por este motivo se utiliza **Git LFS (Large File Storage)** para su manejo eficiente dentro del repositorio.
Esto garantiza que el proyecto se mantenga accesible sin afectar el rendimiento o el peso del repositorio principal.

---

**Autor:** Julián Ritter Gama
**Formación:** Bootcamp TripleTen — Data Analytics
📬 **Contacto:** [LinkedIn](https://www.linkedin.com/in/juli%C3%A1n-ritter-gama/) | [jrittery@gmail.com](mailto:jrittery@gmail.com)
