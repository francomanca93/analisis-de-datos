<div align="center">
  <h1>Manipulación y Análisis de datos con Pandas y Python</h1>
</div>

<div align="center"> 
  <img src="readme_img/analisis-datos-pandas.png" width="">
</div>

## Introducción al documento

El contenido de este documento son **apuntes teoricos** del [Curso de Manipulación y Análisis de Datos con Pandas y Python](https://platzi.com/cursos/pandas/) y busca ser una guía para futuros trabajos personales. El mismo está dictado por [David Torres](https://twitter.com/davinci137), Data Scientist en [Platzi](https://platzi.com).

Pandas es la librería de software libre para manipulación de datos con Python más usada en Data Science. Manipula grandes sets de datos numericos, tablas y series de tiempo. Trabaja con múltiples formatos de archivos de datos como csv o xls.

## Objetivos del documento

- Ejecutar operaciones básicas de Pandas.
- Comprender el significado y uso de los DataFrames en Ciencia de Datos.
- Usar Computational Tools de Pandas para realizar cálculos básicos.
- Trabajar con Statisticals tools.
- Hacer preprocesamiento de datos para crear modelos. 
- Extraer información de Data Sets usando Time Series y Date Functionality.

## Tabla de contenido
- [Comenzando con pandas](#Comenzando-con-pandas)
  - [¿Qué es pandas?](#¿Qué-es-pandas?)
  - [Configurando Google Colab](#Configurando-Google-Colab)
  - [Series e Indexación y selección de datos](#Series-e-Indexación-y-selección-de-datos)
  - [DataFrames](#DataFrames)
  - [Indexado y manejo de archivos CSV](#Indexado-y-manejo-de-archivos-CSV)
  - [Conexión con bases de datos tipo SQL](#Conexión-con-bases-de-datos-tipo-SQL)
  - [Diferentes formatos para datasets](#Diferentes-formatos-para-datasets)
- [Funcionalidades básicas y esenciales de pandas](#Funcionalidades-básicas-y-esenciales-de-pandas)
  - [Formatos de lectura para cargar y guardar DataFrames](#Formatos-de-lectura-para-cargar-y-guardar-DataFrames)
  - [Tipos de Variables que componen un data frame](#Tipos-de-variables-que-componen-un-data-frame)
  - [Estructuras de dataframes en detalle](#Estructuras-de-dataframes-en-detalle)
  - [Borrar filas, columnas y copiar información](#Borrar-filas-columnas-y-copiar-información)
- [Aplicando pandas](#Aplicando-pandas)
  - [Funciones matemáticas](#Funciones-matemáticas)
  - [Funciones más complejas y lambdas](#Funciones-más-complejas-y-lambdas)
- [Contenido extra](#Contenido-extra)


## Comenzando con pandas
### ¿Qué es pandas?

[Pandas](https://pandas.pydata.org/) es una herramienta de análisis y manipulación de datos de código abierto rápida, potente, flexible y fácil de usar, construida sobre Python.
 
<div align="center"> 
  <img src="readme_img/pandas.png" width="">
</div>

Pandas significa **Pan**el **Da**ta. Los paneles de datos son estructuras simples donde se puede organizar por categorias los datos en donde podemos tener variables tipo texto, numericos o booleanos. Cuenta con un eje de filas donde los datos pueden estar organizados temporalmente. 

Fue inventada en 2008 por [Wes McKinney](https://en.wikipedia.org/wiki/Wes_McKinney) como una necesidad para analizar grandes volumenes de datos en los mercados financieros.

#### Ventajas

- Reduce lineas de código
- Diseñada especialmente para análisis
- API fácil y concisa
- Multiples funciones

#### Desventajas

- Compatibilidad con matrices 3 (numpy)
- Curva de aprendizaje lenta

### Configurando Google Colab

[Notebook de contenido](https://github.com/francomanca93/analisis-de-datos/blob/comienzo/1-Comenzando-con-pandas/1_Configurando_Google.ipynb)


En esta sección se ve como configurar **Google Colaboratoty**, tambien se trabaja con operaciones básicas, variables, listas y numpy para experimentar con Colab. 

**Colab** el cuál se basa en los cuadernos de Jupyter Notebook, por lo tanto la forma de trabajar es muy similar. 

**Google Colab** te brinda una maquina virtual con 100 GB y 12 GB de RAM, estas especificaciones te permiten ejecutar codigos mas complejos en la nube. Ademas colab viene con la mayoria de librerias para el uso en ciencia de datos y machine learning.

### Series e Indexación y selección de datos

[Notebook de contenido](https://github.com/francomanca93/analisis-de-datos/blob/comienzo/1-Comenzando-con-pandas/2_Series.ipynb)

En esta sección vemos las ventajas que tiene Pandas con series. Vemos como crear series simples y definir ciertas caracteristicas como labels, etc. 

Tambien se estudia como obtener los valores de esta, como crear series con diccionarios de Python.

Se finaliza la sección como trabajar con valores nulos, filtrar datos, y crear nuevas series con estos filtros. 

### DataFrames

[Notebook de contenido](https://github.com/francomanca93/analisis-de-datos/blob/comienzo/1-Comenzando-con-pandas/3_Dataframes.ipynb)

En esta sección se estudian como trabajar con Dataframes en Pandas. Se crean dataframs a través de diccionarios de Python. Luego se estudian **métodos** que nos permite **analizar el set de datos inicialmente**. Esto nos permite conocer a nuestro DataFrame.

Seguido a lo anterior se aprende como **extraer datos** del dataframe una vez lo conocemos. 

Se finaliza conociendo como **filtrar nuestros datos** gracias a metodos de Pandas y operadores relacionales. Con esto podemos crear dataframe personalizados especificando que es lo que queremos del inicial.

### Indexado y manejo de archivos CSV

[Notebook de contenido](https://github.com/francomanca93/analisis-de-datos/blob/comienzo/1-Comenzando-con-pandas/4_Guardar_y_cargar.ipynb)


Los que aprenderemos en esta notebook será **como conectar** nuestro ambiente de trabajo **con nuestro nube personal** de google drive, **generar** nuestro primeros **archivos en csv** y aprender a **leerlos**.

Nota: **csv** es el formato universal mas simple que se usa para compartir informacion.

### Conexión con bases de datos tipo SQL

[Notebook de contenido](https://github.com/francomanca93/analisis-de-datos/blob/comienzo/1-Comenzando-con-pandas/5_Conexi%C3%B3n_con_bases_de_datos_tipo_SQL.ipynb)

En esta sección se estudia cómo usar Pandas y Python para conectarte con tu base de datos SQL. Pandas cuenta con una funcionalidad que facilita el acceso a tus bases de datos tipo SQL.

Tenemos diferentes formas para conectarnos  tanto a **PostgreSQL**, **SQL Server**, **MySQL**, **Oracle**, otras.


### Diferentes formatos para datasets

[Notebook de contenido](https://github.com/francomanca93/analisis-de-datos/blob/comienzo/1-Comenzando-con-pandas/6_Diferentes_formatos_para_datasets.ipynb)

En este notebook se estudia las ventajas y desventajas de trabajar con otros formatos para datasets. Como guardar nuestro dataframe utilizando otros tipos de formatos.

Existen diferentes formatos, entre estos estan los siguientes:

- **CSV** - Es muy versatil ya que solo tiene comas y saltos de linea.
- **JSON** - Tiene un formato muy similar al de un diccionario de Python.
- **Excel** - Permite guardar el archivo en formato .xls para trabajar con el en Excel o Spreadsheets.
- **Pickle** - Permite comprimir la información, es util cuando se tienen tablas grandes.
- **Parquet** - Permite darle un formato que puede usarse en ambientes de Big Data como Hadoop.


## Funcionalidades básicas y esenciales de pandas

### Formatos de lectura para cargar y guardar DataFrames

En este notebook estudiamos sobre diversos formatos de almacenamiento de datos y cómo elegir el formato eficiente que se adapte a nuestras necesidades.

En la clase se preparo un [script para generar un DataFrame](https://github.com/francomanca93/analisis-de-datos/blob/funcionalidades-basicas/2-Funcionalidades-basicas-de-pandas/3_1_Save_Load_formats.ipynb) de mas de **100 mil registros** y **30 columnas** (las primeras 15 con formato numérico,las restantes tipo texto).

Conclusiones:

**CSV y formatos String** : Son simples, requieren alto costo computacional y algo lentos.

**HDF** : Gran soporte, adecuado para grandes cantidades de datos, rápido a costo de alto costo computacional.

**Parquet** : Puede igualar a hdf e inclusive trabajar por chunks y en paralelo.

**Pickle** : Es práctico pero lento con grandes cantidades de datos.

### Tipos de Variables que componen un data frame

[Notebook del contenido](https://github.com/francomanca93/analisis-de-datos/blob/funcionalidades-basicas/2-Funcionalidades-basicas-de-pandas/7_Tipos_de_datos.ipynb)

En esta sección se estudia cual es la **rutina de preprocesamiento de datos** con la que debemos comenzar a analizar un dataframe. Vamos a estudiar la composicion de las diferentes formatos de variables que podemos encontrar en un dataframe. 

Vamos a utiilzar [Google DataSearch](https://datasetsearch.research.google.com/) para buscar datasets.

### Estructuras de dataframes en detalle

[Notebook del contenido](https://github.com/francomanca93/analisis-de-datos/blob/funcionalidades-basicas/2-Funcionalidades-basicas-de-pandas/7_Tipos_de_datos.ipynb)

En esta sección estudiamos en detalle las diferentes variables que podemos encontrar en un mismo dataframe. Estas pueden ser categoricas, de tiempo, tipo texto, numericos (float e int).

**Una ventaja de trabajar con variables categoricas es que reducimos el tamaño de uso de la memoria RAM y el tamaño del archivo en si.**

### Borrar filas, columnas y copiar información

[Notebook del contenido](https://github.com/francomanca93/analisis-de-datos/blob/funcionalidades-basicas/2-Funcionalidades-basicas-de-pandas/7_Tipos_de_datos.ipynb)

En esta sección estudiamos como borrar los registros de un dataframe usando la función drop. 

Tambien aprenderemos como copiar correctamete un dataframe para trabajar con él. En la rutina de preprocesamiento de datos es muy importante que se mantenga la fuente de datos original.

## Aplicando pandas

### Funciones matemáticas

[Notebook de contenido](https://github.com/francomanca93/analisis-de-datos/blob/aplicaciones/3-Aplicando-pandas/8_Funciones_matem%C3%A1ticas.ipynb)

En esta sección se estudia como hacer **operaciones matematicas** en un dataframe, tambien a realizar **operaciones entre diferentes columnas** de un mismo dataframe y utilizar funciones matematicas de otra libreria como **numpy**.

Utilizamos un dataframe descargado de [kaggle](https://www.kaggle.com/), el mismo se llama [London bike sharing dataset](https://www.kaggle.com/hmavrodiev/london-bike-sharing-dataset).

### Funciones más complejas y lambdas

[Notebook de contenido](https://github.com/francomanca93/analisis-de-datos/blob/aplicaciones/3-Aplicando-pandas/8_Funciones_matem%C3%A1ticas.ipynb)

En esat sección el objetivo es aprender a usar **funciones** mucho mas **avanzadas** (**creandolas**) en el dataframe utilizando **.apply()** y **lambda**. 

En esta sección seguimos utilizando el dataset [London bike sharing dataset](https://www.kaggle.com/hmavrodiev/london-bike-sharing-dataset).

### Contenido extra