## Análisis de Datos para Alura Store
Este repositorio contiene la solución al primer desafío de Data Science de Alura Latam. El objetivo es realizar un análisis exploratorio de datos (EDA) para la cadena de tiendas "Alura Store" y proporcionar una recomendación de negocio basada en datos.

📝 Descripción del Proyecto
El Sr. Juan, dueño de la cadena Alura Store, planea iniciar un nuevo emprendimiento y necesita vender una de sus cuatro tiendas para financiarlo. Nuestra misión como analistas de datos es examinar los datos de ventas, rendimiento y reseñas de las tiendas para identificar la candidata menos eficiente y presentar una recomendación final sobre cuál tienda debería vender.

🎯 Objetivos del Desafío
Cargar y manipular datos desde archivos CSV utilizando la biblioteca Pandas.

Crear visualizaciones de datos claras e informativas con la biblioteca Matplotlib.

Analizar métricas de negocio clave como ingresos, rendimiento de ventas por categoría, satisfacción del cliente y costos operativos.

Sintetizar los hallazgos en un informe ejecutivo para la toma de decisiones.

🛠️ Tecnologías Utilizadas
Python 3

Pandas: Para la manipulación y análisis de los DataFrames.

Matplotlib: Para la generación de visualizaciones estáticas.

Google Colab / Jupyter Notebook: Como entorno de desarrollo interactivo.

🚀 Cómo ejecutar el proyecto
Clona o descarga este repositorio en tu máquina local.

Abre el archivo challenge_latam.ipynb en un entorno como Jupyter Notebook o Google Colab (recomendado).

Ejecuta las celdas en orden. El cuaderno está diseñado para cargar los datos directamente desde el repositorio original de Alura, por lo que no es necesario descargar los archivos CSV por separado.

📊 Informe Final: Recomendación para el Sr. Juan
1. Introducción
El presente informe detalla el análisis de rendimiento de las cuatro tiendas de la cadena Alura Store. El objetivo principal es evaluar métricas de ingresos, satisfacción del cliente y costos operativos para determinar qué tienda representa la mejor opción para ser vendida, asegurando que la decisión esté fundamentada en evidencia cuantitativa.

2. Desarrollo y Hallazgos Clave
Se analizaron datos correspondientes a ventas individuales, cubriendo información sobre productos, precios, costos de envío y calificaciones de los clientes. Los hallazgos más relevantes se resumen a continuación:

Ingresos Totales: El análisis de facturación, visualizado en el Gráfico 1, demuestra que existe una clara jerarquía en la generación de ingresos. La Tienda 1 es la líder indiscutible en ventas, mientras que la Tienda 4 se posiciona como la que genera la menor cantidad de ingresos de las cuatro.

Satisfacción del Cliente: Un hallazgo sorprendente se revela al analizar las calificaciones promedio. A pesar de las diferencias en ingresos, las cuatro tiendas gozan de una satisfacción del cliente muy similar y positiva, con calificaciones promedio cercanas a las 4.0 de 5 estrellas. Notablemente, la Tienda 4, a pesar de ser la de menores ingresos, mantiene a sus clientes tan satisfechos como la tienda de mayor rendimiento. Esto sugiere que el problema de la Tienda 4 no es la calidad del servicio o del producto, sino probablemente un menor volumen de ventas o alcance de mercado.

Eficiencia Operativa (Costos de Envío): Al analizar los costos de envío promedio, se observó que la Tienda 1, si bien es la que más vende, también presenta uno de los costos de envío promedio más altos. Por otro lado, la Tienda 4 demostró ser una de las más eficientes en este aspecto, con costos de envío promedio más bajos.

3. Conclusión y Recomendación Final
Tras evaluar los factores clave de rendimiento, la recomendación es vender la Tienda 4.

Justificación:

La decisión se basa principalmente en el criterio de ingresos totales, que es el indicador más directo del rendimiento financiero y el potencial de un negocio. La Tienda 4 genera consistentemente la menor facturación, lo que la convierte en el activo menos productivo de la cadena.

Aunque su alta calificación de clientes es un punto muy favorable, esto no ha logrado traducirse en un volumen de ventas que compita con las otras sucursales. Vender la tienda con el menor impacto en los ingresos totales es la estrategia más segura y lógica para que el Sr. Juan pueda liberar capital para su nuevo emprendimiento sin afectar significativamente el rendimiento global de Alura Store.
