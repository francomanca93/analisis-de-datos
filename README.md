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
- [Funcionalidades básicas y esenciales de pandas](#Funcionalidades-básicas-y-esenciales-de-pandas)
- [Aplicando pandas](#Aplicando-pandas)
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

### Funcionalidades básicas y esenciales de pandas
### Aplicando pandas
### Contenido extra