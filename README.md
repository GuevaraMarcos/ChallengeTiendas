# Análisis de Rendimiento de Tiendas
Este proyecto tiene como objetivo realizar un análisis comparativo entre cuatro tiendas a partir de un conjunto de datos con información sobre ventas, calificaciones, categorías de productos, unidades vendidas y costos de envío. La finalidad es identificar la tienda con mejor rendimiento global y la que debería ser considerada para venta. 

## Descripción General
Utilizando Python en Google Colab, se desarrollaron diversas funciones para analizar los siguientes aspectos clave por tienda:

Facturación total.

Categoría más vendida.

Calificación promedio.

Producto más y menos vendido.

Costo promedio de envío.

Se emplearon estructuras de datos como listas y diccionarios, junto con visualizaciones generadas con Matplotlib. El análisis facilita la toma de decisiones estratégicas respecto al rendimiento y viabilidad de cada tienda.

## Estructura del Proyecto
datos_ventas: Diccionario con los registros de ventas por tienda.

facturacion_total: Función para calcular el monto total vendido por tienda.

categoria_popular: Función que determina la categoría de productos más vendida.

calificacion_promedio: Calcula la media de calificaciones de productos vendidos.

producto_mas_menos_vendido: Identifica los productos con más y menos unidades vendidas.

costo_envio_promedio: Calcula el costo medio de envío por tienda.

visualizaciones: Funciones para generar gráficos de barras, líneas y pastel.

ranking: Sistema básico de puntuación para determinar la mejor y peor tienda en cada aspecto.

## Resultados Destacados
Mejor tienda: La tienda con mayor puntuación en la mayoría de los aspectos analizados.

Peor tienda: Aquella con menores indicadores de rendimiento o mayor variabilidad en resultados clave.

Justificación de decisión: Se proveen explicaciones técnicas para respaldar la elección de qué tienda conservar y cuál vender, considerando datos cuantitativos y patrones observados.

## Tecnologías Utilizadas
Python 3

Google Colab

Matplotlib

Estructuras de control: condicionales, bucles y funciones

Manejo de diccionarios y listas anidadas

## Requisitos
Este proyecto fue ejecutado en Google Colab, por lo tanto no requiere instalación local. Si se desea ejecutar localmente, se recomienda instalar las siguientes bibliotecas:

pip install matplotlib

## Ejecución
Para utilizar este análisis:

Abre el archivo en Google Colab.

Ejecuta cada celda en orden.

Consulta las gráficas y resultados numéricos.

Revisa la sección de conclusiones para conocer la tienda sugerida para venta.

## Contribución
Este proyecto fue desarrollado con fines educativos, para fortalecer habilidades de análisis de datos y visualización en Python. Se aceptan sugerencias y mejoras vía Pull Requests.
