[![Aspose-Words-f708d298-ce78-40fa-86e4-14de3b3fa0d4-001.png](https://i.postimg.cc/pLGQ8ypp/Aspose-Words-f708d298-ce78-40fa-86e4-14de3b3fa0d4-001.png)](https://postimg.cc/5XzFW45V)


 Facultad de Ingeniería Civil<br>Ingeniero Topográfo Geomatico<br>Programacion II<br>Mtro. Sebastián Gonzales Zepeda<br>Lectura de datos GPS en python<br>Ubicación: Campus Coquimatlan, Facultad de Ingeniería Civil<br>Integrantes:<br>Manuel Cisneros Castillo 3°B<br>Martha Julia De la Torre Venegas 3°B<br>Raul Said Mancilla Vargas 3°B<br>13 de diciembre del 2022


# **Lectura de datos GPS con Python**
*Reading GPS data with Python*

` `**Cisneros Castillo Manuel Guadalupe (1), De la Torre Venegas Martha Julia (2), Mancilla Vargas Raul  Said (3)**

` `(1) Facultad de Ingeniería Civil, 1604, (1) 20186438, mdelatorre2@ucol.mx, (2) 20186904, rmancilla@ucol.mx

Cisneros Castillo, Manuel Guadalupe; De la torre Venegas, Martha Julia; Mancilla Vargas, Raul Said. *Librerías. //* Ibersid. (2008) p1-pn. ISSN 1888-0967.
5**

**Resumen:**

Se realiza un programa en la plataforma Colab con base a lo aprendido durante las clases de Programación ll, el cual es capaz de leer datos de coordenadas de un punto sobre la superficie terrestre y poder representarlas en un mapa didáctico lo cual muestre los puntos que fueron importados desde un archivo csv.
**Palabras clave**: 
Python, proyecto, datos,   colab,  superficie terrestre, programación  II.

**Abstract:**

A program is made on the Colab platform based on what has been learned during Programming II classes, which is capable of reading coordinate data from a point on the earth's surface and being able to represent them on a didactic map which shows the points that were imported from a csv file.
**Keywords:** 
Python, project, data, colab, terrestrial surface,  programming  II.

## **Introducción**
En el presente reporte se redacta cada uno de los pasos que fueron necesarios para la elaboración del producto final, que parte de los conocimientos básicos adquiridos durante el transcurso de la materia de Programación de Computadoras ll, así como también de la rigurosa búsqueda necesaria de información individual.

Se plasma el proceso de elaboración en conjunto del objetivo general que abarca ampliamente a lo que se busca llegar con el resultado final, así como de los objetivos específicos que fueron necesarios para la conformación del producto final. 

Una vez explicado todo el proceso mediante hipótesis, criterios basados en información existente y con base a los resultados obtenidos se recata un apartado de conclusiones en el que cada integrante redacta su experiencia tanto individual como de equipo durante el desarrollo del mismo.

[![Aspose-Words-201be7f2-5c67-4fde-b0ac-ffc944e8e01a-001.png](https://i.postimg.cc/PJyyD5yH/Aspose-Words-201be7f2-5c67-4fde-b0ac-ffc944e8e01a-001.png)](https://postimg.cc/D4W1kFRp)

## **Desarrollo**
Python es un lenguaje de programación ampliamente utilizado en las aplicaciones web, el desarrollo de software, la ciencia de datos y el machine learning (ML). Los desarrolladores utilizan Python porque es eficiente y fácil de aprender, además de que se puede ejecutar en muchas plataformas diferentes. Python permite que los desarrolladores sean más productivos, ya que pueden escribir un programa de Python con menos líneas de código en comparación con muchos otros lenguajes.

La geo localización consiste en obtener la ubicación geográfica de un objeto como puede ser un teléfono móvil, un coche o un una calle. Para ello se puede utilizar diferentes métodos como por ejemplo comprobar el código postal de una carta, la dirección IP de un equipo o el sistema GPS de nuestro teléfono móvil.

Los cual para el desarrollo de este programa que estamos creando se utilizan cierto tipos de librerías como lo son matplotlib, importar un archivo desde drive y pandas, además del módulo os.

Pandas es una librería de Python especializada en la manipulación y el análisis de datos. Ofrece estructuras de datos y operaciones para manipular tablas numéricas y series temporales, es como el Excel de Python. Las principales características de esta librería son:

- Define nuevas estructuras de datos basadas en los arrays de la librería NumPy pero con nuevas funcionalidades.
- Permite leer y escribir fácilmente ficheros en formato CSV, Excel y bases de datos SQL.
- Permite acceder a los datos mediante índices o nombres para filas y columnas.
- Ofrece métodos para reordenar, dividir y combinar conjuntos de datos.

Matplotlib es una librería de trazado utilizada para gráficos 2D en lenguaje de programación [Python](https://aprendeia.com/por-que-python-para-machine-learning/), es muy flexible y tiene muchos valores predeterminados incorporados que te ayudarán muchísimo en tú trabajo. Produce figuras de calidad de publicación en una variedad de formatos impresos y entornos interactivos. Como tal, no necesitas mucho para comenzar, solamente tienes que hacer las importaciones necesarias, preparar algunos datos y con esto puedes comenzar a trazar tu función con la ayuda de la instrucción plot. ()

El módulo os nos permite acceder a funcionalidades dependientes del Sistema Operativo. Sobre todo, aquellas que nos refieren información sobre el entorno del mismo y nos permiten manipular la estructura de directorios (para leer y escribir archivos

Para la creación del programa el propósito que se tiene en mente es la realización del programa que mediante un archivo .csv lo puedo graficar, lo cual los datos que se utilizaron para crear el archivo fueron las coordenadas de puntos geo localizados por teléfonos móviles, los cuales se registraron las coordenadas de cada uno al igual que su altitud y se registraron en Excel en un archivo delimitado por comas.

[![Aspose-Words-201be7f2-5c67-4fde-b0ac-ffc944e8e01a-002.jpg](https://i.postimg.cc/ZRKCRYWp/Aspose-Words-201be7f2-5c67-4fde-b0ac-ffc944e8e01a-002.jpg)](https://postimg.cc/R3yMpBQZ)

Los materiales que se utilizaron para poder llevar a cabo este proyecto, se hicieron uso de distintos materiales o programas:

- Computadora
- Google colab
- Internet
- Excel (csv)
- Coordenadas (Latitud, Longitud y Altitud)
- Información proporcionada

[![Aspose-Words-201be7f2-5c67-4fde-b0ac-ffc944e8e01a-003.png](https://i.postimg.cc/x12HQ23y/Aspose-Words-201be7f2-5c67-4fde-b0ac-ffc944e8e01a-003.png)](https://postimg.cc/fJ8k71FJ)

Lo cual para ellos eso es lo que se pretende buscar con dicho programa aplicando los conocimientos que adquirimos durante el semestre en la materia de programación II.

Los métodos o maneras que se realizaron para la creación del código fue primeramente importar las librerías necesarias para poder leer el archivo .csv y para poder graficarlo mediante un mapa donde los ubique con puntos, junto con su descripción, al igual que importar o poner from. Google drive para poder abrir el archivo que necesitemos desde drive para más facilidad operarlo.

[![Aspose-Words-201be7f2-5c67-4fde-b0ac-ffc944e8e01a-004.png](https://i.postimg.cc/4Nz7B0RK/Aspose-Words-201be7f2-5c67-4fde-b0ac-ffc944e8e01a-004.png)](https://postimg.cc/ZC55qVRZ)

Después de importar todas librerías necesarias, ahora solo importamos o enlazamos a google drive desde colab, para que así nos dé acceso a drive dependiendo la cuenta, pero el problema es que debes de tener el archivo en un carpeta en drive para que se puede realizar la lectura del archivo, así ya importado desde drive, se copia la ruta de donde esta para que así pueda leerlo.

[![Aspose-Words-201be7f2-5c67-4fde-b0ac-ffc944e8e01a-005.png](https://i.postimg.cc/2Sk6T8xJ/Aspose-Words-201be7f2-5c67-4fde-b0ac-ffc944e8e01a-005.png)](https://postimg.cc/crz0LW2M)

Ya importado el archivo solo indicamos que debe de leerlo por sus columnas para asi registralas y poder graficarlas, ya leido el archivo y que lo haya encontrado en drive, ahora lo indicamos que lo grafique desde un mapa y los ubique mediante unos puntos ¿, junto con su descripcion y ID, lo cual para ello tambien indicamos como un titulo representatico al mapa de lo cual esta asignado como coordendas puntos locales.

[![Aspose-Words-201be7f2-5c67-4fde-b0ac-ffc944e8e01a-006.png](https://i.postimg.cc/bvKqXzQq/Aspose-Words-201be7f2-5c67-4fde-b0ac-ffc944e8e01a-006.png)](https://postimg.cc/xkywMVxZ)

Para un mejor entendimiento a la hora de ejecutar el programa, además de representar las coordenadas en un mapa, el programa nos muestra la tabla con los datos que contiene nuestro archivo .csv

[![Aspose-Words-ac24bb84-5e37-4b74-aa54-0a8ca72c5e17-007.png](https://i.postimg.cc/m2vNrkyb/Aspose-Words-ac24bb84-5e37-4b74-aa54-0a8ca72c5e17-007.png)](https://postimg.cc/N5xrJgnV)

Finalmente pues al crear todo el programa, lo hacemos correr y checamos correctamente que no haya falla a la hora de ller el archvio desde drive para poder seguirlo, y asi finalmente grafica los puntos que estan el archivo .csv generando un mapa con sus coordenadas que hayamos capturado.
## **Manejo de datos**
El programa presentado funciona con base a una serie de datos recopilados a partir de un censo. Estos datos contienen características que nos permiten poder ubicarlos como datos geoespaciales con ayuda de un programa. Cuentan con un código de identificación y las coordenadas dadas en x, y, z.

Para hacer la correcta función de estos datos se ha generado un archivo con características de .csv que posteriormente fue guardado en drive con la intención de que al ejecutar el programa este lo llame mediante un código y de esta manera nos permita conocer su componente geoespacial. 

[![Aspose-Words-201be7f2-5c67-4fde-b0ac-ffc944e8e01a-008.png](https://i.postimg.cc/wjCrg3b4/Aspose-Words-201be7f2-5c67-4fde-b0ac-ffc944e8e01a-008.png)](https://postimg.cc/9DBbBX2y)

Si observamos los datos a importar podemos darnos cuenta de que en la columna de norte todos los valores son negativos, esto porque de acuerdo a las características geoespaciales indica que cuando los valores con negativos son porque representan el Este desde el meridiano de Greenwich y los valores positivos representan el Oeste. Las líneas de latitud (coordenadas Y) van desde -90º hasta +90º. Siendo **l**os valores negativos los que representan el Sur desde el ecuador y los valores positivos los representa el Norte.

Cada uno de los datos registrados en el csv son leídos por el programa y ubicados en la coordenada que les corresponde con ayuda de un mapa que a su vez el programa se encarga de graficar. 

[![Aspose-Words-201be7f2-5c67-4fde-b0ac-ffc944e8e01a-009.png](https://i.postimg.cc/xjXFJvDp/Aspose-Words-201be7f2-5c67-4fde-b0ac-ffc944e8e01a-009.png)](https://postimg.cc/c6NcP8Jf)

## **Resultados**
Como resultado final presentamos un programa que dadas las características geográficas de ciertos puntos proporciona la ubicación de cada uno de ellos. En este caso y con referencia a los datos brindados para el desarrollo del programa se hace la localización de 18 puntos que se ubican sobre un gráfico proporcionado por el mismo programa en el que al poner el cursor sobre cada uno de los puntos se proporciona la información con la que este fue localizado, es decir: se presenta la descripción del punto y su característica geográfica.

[![Aspose-Words-201be7f2-5c67-4fde-b0ac-ffc944e8e01a-007.png](https://i.postimg.cc/kMSvPfdC/Aspose-Words-201be7f2-5c67-4fde-b0ac-ffc944e8e01a-007.png)](https://postimg.cc/yWVZFhdp)

Entrando en posibles aplicaciones el programa proporcionado podría ser utilizado como una herramienta en distintas áreas en las que se requiera de la ubicación por áreas, regiones, etc., de algunos elementos, por ejemplo; mediante coordenadas se podría hacer una esquematización para poder hacer un análisis adecuado de la información sobre algún tema. De esta manera todo aquel que trabaje con la ubicación geográfica de las cosas podría utilizar el programa para darle mayor énfasis a sus proyectos futuros. En este caso con ayuda del programa realizado se hace la ubicación de los resultados obtenidos en un censo elaborado en el municipio de Colima, es por esta razón que los puntos ubicados se concentran en la región sureste del gráfico. 

## **Conclusión**
Como conclusión final del proyecto queda claro que para la creación de códigos o programas que nos den resultados geoespaciales es demasiado importante saber cómo realizarlo y qué tipo de librerías o módulos tener que instalar para que así nos arroje resultados que esperamos, la parte geoespacial es muy amplia ya que se pueden crear diferentes tipos de programas o proyectos que demuestren resultados como mapas, puntos, gráficas, etc., es por eso que es muy importante conocer todo sobre eso ya que es indispensable para poder crear cual quiero tipo de trabajo que tenga que ver con la programación, así que como enseñanza de este proyecto se logró generar un programa lo cual nos arrojará resultados finales lo cual como objetivo que se tenía en mente era generar un mapa que creará los puntos y los identificará rápidamente importándolo desde un archivo .csv con coordenadas, descripción y su número de punto y al final se logró generar el programa que nos ayude a obtener esos resultados.
## **Referencias**
Alberca, A. S. (2020, 4 octubre). La librería Matplotlib. Aprende con Alf. https://aprendeconalf.es/docencia/python/manual/matplotlib/

Maluenda, R. (2022, 17 agosto). Introducción a Pandas, la librería de Python para trabajar con datos. Profile Software Services. https://profile.es/blog/pandas-python/

uniwebsidad. (s. f.). 10.1. Módulos de sistema (Python para principiantes). https://uniwebsidad.com/libros/python/capitulo-10/modulos-de-sistema
