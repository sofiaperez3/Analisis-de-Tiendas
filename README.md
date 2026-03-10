## Análisis de Desempeño de Tiendas - Proyecto Señor Juan ##

Este proyecto tiene como objetivo principal ayudar al señor Juan a tomar una decisión estratégica sobre cuál de sus cuatro tiendas debe vender para reinvertir en un nuevo negocio. A través de un análisis de datos exhaustivo utilizando Python, evaluamos el rendimiento financiero, operativo y la satisfacción del cliente de cada sucursal.

## 📋 Descripción del Desafío

Se nos ha encomendado la tarea de identificar la tienda con el desempeño más bajo basándonos en cinco pilares fundamentales:

**1. Facturación Total:** Identificar qué tienda genera el mayor volumen de ingresos.

**2. Categorías Populares:** Determinar qué tipos de productos tienen mayor rotación en cada ubicación.

**3. Satisfacción del Cliente:** Calcular el promedio de las evaluaciones otorgadas por los compradores.

**4. Inventario Crítico:** Listar los productos más vendidos (estrellas) y los menos vendidos (rezagados).

**5. Eficiencia Logística:** Analizar el costo promedio de envío desde cada tienda hasta el cliente final.

## 🛠️ Tecnologías Utilizadas

El análisis se desarrolló íntegramente en Python, aprovechando las siguientes bibliotecas:

**Pandas:** Para la manipulación, limpieza y procesamiento de los datasets (.csv).

**Matplotlib:** Para la generación de gráficos base y visualización de tendencias.

**Seaborn:** Para crear reportes visuales estadísticos estéticamente atractivos y fáciles de interpretar.

## 📂 Estructura de los Datos

El sistema procesa cuatro archivos fuente con la siguiente estructura de columnas:

**Producto:** Nombre del artículo.

**Categoría del Producto:** Clasificación del artículo.

**Precio:** Valor de venta.

**Costo de envío:** Gasto logístico asociado.

**Calificación:** Evaluación del cliente (escala 1-5).

(Otras columnas de contexto: Fecha, Vendedor, Lugar, Método de pago).

## 🚀 Cómo Ejecutar el Proyecto

Asegúrate de tener instaladas las dependencias necesarias:

pip install pandas matplotlib seaborn


Coloca los archivos tienda_1 .csv, tienda_2.csv, tienda_3.csv y tienda_4.csv en el mismo directorio que el script.

Ejecuta el script principal:

python analisis_tiendas_juan.py


## 📊 Interpretación del Informe

El script genera un Dashboard Visual y un Resumen Ejecutivo por consola. La decisión final de venta se basa en un "Índice de Desempeño Negativo", que pondera:

Bajos ingresos.

Baja satisfacción del cliente.

Altos costos operativos (envíos).

Este análisis es una herramienta de apoyo a la toma de decisiones basada en datos.
