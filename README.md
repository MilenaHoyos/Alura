# Análisis de Rendimiento de Tiendas - Proyecto de Data Science

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar el desempeño de cuatro tiendas utilizando técnicas de análisis de datos con Python. A partir de los datos de ventas se busca identificar cuál tienda presenta el menor rendimiento comercial, con el fin de recomendar cuál podría ser vendida.

El análisis se basa en diferentes indicadores como:

* Facturación total
* Ventas por categoría de producto
* Calificación promedio de los clientes
* Productos más y menos vendidos
* Costo promedio de envío

Este tipo de análisis permite tomar decisiones basadas en datos, lo cual es fundamental en proyectos de ciencia de datos y analítica de negocios.

---

## Tecnologías Utilizadas

* Python
* Pandas – Manipulación y análisis de datos
* Matplotlib – Visualización de datos
* Jupyter Notebook / Google Colab

---

## Fuente de Datos

Los datos utilizados provienen de un repositorio público utilizado en un challenge de Data Science.

Cada dataset representa las ventas de una tienda distinta:

* Tienda 1
* Tienda 2
* Tienda 3
* Tienda 4

Cada base de datos incluye información como:

* Producto
* Categoría del producto
* Precio
* Costo de envío
* Calificación del cliente

---

## Análisis Realizados

### 1. Análisis Exploratorio de Datos

En esta etapa se revisa la estructura de los datasets para comprender:

* número de registros
* tipos de variables
* valores faltantes
* estadísticas descriptivas

Este paso permite tener una visión general del comportamiento de los datos antes de realizar los análisis principales.

---

### 2. Análisis de Facturación

Se calcula la facturación total de cada tienda sumando los precios de los productos vendidos.

Este análisis permite identificar:

* qué tienda genera más ingresos
* qué tienda presenta menor rendimiento comercial

Los resultados se visualizan mediante gráficos de barras para facilitar la comparación entre tiendas.

---

### 3. Ventas por Categoría

Se analizan las ventas agrupadas por categoría de producto para cada tienda.

Este análisis permite identificar:

* categorías con mayor demanda
* categorías con menor desempeño
* posibles patrones de consumo en cada tienda

---

### 4. Calificación Promedio de la Tienda

Se calcula la calificación promedio de los clientes para cada tienda.

Este indicador refleja el nivel de satisfacción de los clientes y permite comparar la calidad del servicio ofrecido por cada tienda.

---

### 5. Productos Más y Menos Vendidos

Se analizan los productos según su frecuencia de venta para identificar:

* productos más populares
* productos con menor rotación

Esta información puede utilizarse para mejorar la gestión de inventario y las estrategias comerciales.

---

### 6. Costo Promedio de Envío

Se calcula el costo promedio de envío para cada tienda.

Este análisis permite evaluar la eficiencia logística, ya que costos de envío elevados pueden afectar la competitividad de una tienda.

---

## Resultados

A partir de los análisis realizados se pueden comparar las cuatro tiendas considerando varios indicadores clave:

* ingresos generados
* satisfacción del cliente
* desempeño de productos
* costos logísticos

La combinación de estos factores permite evaluar el rendimiento general de cada tienda.

---

## Conclusión

Después de analizar las cuatro tiendas utilizando los diferentes indicadores de desempeño, se identificaron diferencias importantes en su rendimiento comercial.

En primer lugar, al analizar la **facturación total**, se observa que la **Tienda 4 presenta el menor volumen de ingresos** en comparación con las demás tiendas. Esto indica que genera menos ventas y tiene menor impacto comercial dentro del conjunto de tiendas.

En segundo lugar, el análisis de **ventas por categoría** muestra que, aunque todas las tiendas comercializan productos similares, la Tienda 4 presenta un menor desempeño en varias categorías, lo que reduce su competitividad frente a las otras tiendas.

En cuanto a la **calificación promedio de los clientes**, se observa que la Tienda 4 no presenta una ventaja significativa en términos de satisfacción del cliente que pueda compensar su menor facturación.

El análisis de **productos más y menos vendidos** también muestra que el volumen de ventas de la Tienda 4 es inferior al de las demás tiendas, lo que sugiere una menor demanda o menor posicionamiento en el mercado.

Finalmente, el análisis del **costo promedio de envío** indica que la Tienda 4 no presenta ventajas logísticas que puedan mejorar su competitividad frente a las otras tiendas.

Considerando todos estos factores —facturación total, volumen de ventas, desempeño por categoría, calificación de clientes y costos logísticos— se concluye que **la Tienda 4 presenta el rendimiento general más bajo**.

Por esta razón, la recomendación basada en el análisis de datos es **vender la Tienda 4**, ya que su desempeño es inferior en comparación con las demás tiendas.

---

## Posibles Mejoras Futuras

Algunas mejoras que podrían implementarse en futuras versiones del proyecto incluyen:

* análisis de tendencias de ventas
* visualizaciones más avanzadas
* modelos predictivos de ventas
* análisis de rentabilidad por producto

---
