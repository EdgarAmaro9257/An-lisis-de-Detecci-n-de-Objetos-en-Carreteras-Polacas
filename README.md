# Análisis de Detección de Objetos en Carreteras Polacas

# Descripción del Proyecto
Este proyecto realiza un análisis exhaustivo de datos utilizando Python, Spark, Excel y SQL para explorar y analizar un conjunto de datos relacionado con la detección de objetos en carreteras polacas. El objetivo principal del proyecto es comprender mejor las distribuciones de los objetos detectados y las relaciones entre las diferentes variables mediante técnicas de análisis de datos y visualización.

# Estructura del Proyecto
1. Carga de Datos
Archivo CSV: Se carga el archivo de datos utilizando la función google.colab.files.upload() en Google Colab.
2. Exploración Inicial de Datos
Revisión del DataFrame: Se examinan las primeras filas del DataFrame.
Descripción de los Datos: Se presenta información básica y una descripción estadística de las variables.
3. Limpieza y Preprocesamiento de Datos
Limpieza de Datos: Se eliminan filas con valores nulos y duplicados.
Verificación de Valores: Se verifican los valores únicos en la columna object_type.
Conversión de Tipos: Se convierten columnas a tipos de datos apropiados.
4. Análisis Exploratorio de Datos (EDA)
Visualización: Se utiliza Seaborn para visualizar la distribución de los tipos de objetos detectados.
Correlaciones: Se genera un mapa de calor para visualizar correlaciones entre variables numéricas.
5. Almacenamiento y Consulta de Datos con SQL
Base de Datos: Se guarda el DataFrame resultante en una base de datos SQLite.
Consultas SQL: Se ejecutan consultas para agrupar y contar los tipos de objetos detectados.
6. Preprocesamiento con Spark
Procesamiento Distribuido: Se convierte el DataFrame de pandas a un DataFrame de Spark para manejar grandes volúmenes de datos.
7. Visualización y Presentación de Resultados
Gráficos: Se generan gráficos que muestran la distribución de los tipos de objetos y las correlaciones.
Exportación: Los resultados se exportan a un archivo Excel.

# Requisitos
1. Python 3.7+
2. Jupyter Notebook (opcional si se usa Google Colab)
3. Bibliotecas de Python: pandas, numpy, matplotlib, seaborn, sqlite3, pyspark
4. Google Colab (opcional)
5. Archivo CSV del conjunto de datos

# Instrucciones de Uso

1. Carga de Datos:
  Ejecuta el notebook en Google Colab.
  Sube el archivo CSV cuando se te solicite.

2. Exploración de Datos:
  Revisa las primeras filas y la información básica del DataFrame.
  Asegúrate de que los datos estén limpios y en el formato correcto.

3. Análisis Exploratorio:
  Ejecuta las celdas de visualización para analizar distribuciones y correlaciones.

4. Consulta y Almacenamiento:
  Utiliza consultas SQL para profundizar en los datos y extraer información relevante.

5. Exportación de Resultados:
  Exporta los resultados finales a un archivo Excel para su presentación o análisis adicional.
