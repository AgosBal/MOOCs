# Henry Labs - Data Anlytics (DA)

## Proyecto Individual: MOOCs
El objetivo del proyecto es realizar un análisis de mercado de cursos online mediante un EDA (Análisis Exploratorio de Datos), generar visualizaciones interactivas y presentar conclusiones relevantes basadas en los datos, incluyendo el seguimiento de KPIs que permitan evaluar el rendimiento de la empresa en comparación con sus objetivos.

## Descripción del problema
El problema de la empresa en este contexto es ingresar al mercado de cursos online de manera eficiente y competitiva. Si bien existe una gran demanda en el sector, también hay una fuerte competencia entre las diversas plataformas y universidades que ofrecen cursos en línea.
Necesita ajustar su modelo de negocio, los cursos y el contenido ofrecido para captar y retener a la mayor cantidad de clientes posible. Por lo tanto, es fundamental comprender qué factores influyen en las ventas de los cursos. En este caso, el problema específico es analizar y determinar la influencia del precio, idioma, nivel y rating de los cursos en la demanda del producto vendido.
Además, se plantea como objetivo incrementar la tasa de conversión de inscriptos gratuitos a inscriptos pagados en un 15% en comparación con el año anterior. Para lograrlo, se requiere un análisis exhaustivo de los datos y la identificación de estrategias efectivas para aumentar la conversión.

En resumen, el problema de la empresa es competir en el mercado de cursos online de manera efectiva, ajustando su oferta y estrategias de negocio en base al análisis de datos y la comprensión de los factores que influyen en las ventas y la conversión de usuarios.

## Propuesta de trabajo
El proyecto se divide en las siguientes tareas:

 1. RECOPILACIÓN Y EXPLORACIÓN DE DATOS: Obtener los datasets de competidores en el mercado de cursos online, incluyendo información relevante como precio, idioma, nivel, rating y datos de ventas. Realizar un análisis exploratorio de los datos para comprender su estructura, calidad y características.
    
2.  SEGMENTACIÓN DE VENTAS: Realizar un análisis de segmentación de ventas en base a las variables disponibles en los datasets. Agrupar los cursos según su precio, idioma, nivel y rating, y analizar cómo se relacionan con las ventas. Utilizar visualizaciones y métricas descriptivas para identificar patrones y tendencias.
    
3.  ANÁLISIS DE INFLUENCIA DE VARIABLES: Evaluar la influencia de las variables (precio, idioma, nivel, rating) en la demanda de los cursos. Utilizar técnicas estadísticas como análisis de correlación, pruebas de hipótesis u otros modelos predictivos para determinar la relación entre las variables y las ventas.
    
4.  CREACIÓN DE UN WORD CLOUD: Procesar los títulos de los cursos y generar un Word Cloud que muestre las palabras clave más frecuentes. Esto permitirá identificar temas populares y enfoques relevantes en la oferta de cursos.
    
5.  ESTABLECIMIENTO DE KPIs: Definir un conjunto de Key Performance Indicators (KPIs) relacionados con la demanda y conversión de los cursos. Uno de los KPIs propuestos es la tasa de conversión de inscriptos gratuitos a inscriptos pagados. Buscar datasets complementarios y evaluar este KPI en las distintas plataformas para obtener una visión más amplia.
    
6.  DESARROLLO DEL DASHBOARD: Crear un dashboard interactivo que muestre los datos, visualizaciones y análisis obtenidos. El dashboard debe incluir filtros y opciones de selección para explorar los datos en detalle. Diseñar una presentación clara y coherente de la información, utilizando gráficos pertinentes y una disposición estética que facilite la interpretación de los datos.
    
7.  ANÁLISIS Y CONCLUSIONES: Realizar un análisis profundo de los datos y las visualizaciones obtenidas. Extraer conclusiones relevantes sobre la influencia de las variables en las ventas, identificar patrones interesantes y proponer estrategias para aumentar la conversión de usuarios. Presentar los resultados en un informe detallado y en el dashboard interactivo.
    
8.  DESAFÍOS ADICIONALES (opcional): Como desafío adicional, se sugiere realizar cruces de datos con datasets complementarios para obtener información adicional o comparar el desempeño en distintas plataformas. También se puede considerar la creación de una base de datos en un motor SQL y la ejecución de scripts de Python en la herramienta de visualización seleccionada.
    
9.  DOCUMENTACIÓN Y PRESENTACIÓN FINAL: Elaborar un repositorio de GitHub que contenga un Readme con una descripción general del proyecto, la estructura de los archivos y un reporte de análisis con base en el dashboard y los KPIs sugeridos. 

10. PRESENTACIÓN: Preparar una presentación de no más de 10 minutos que incluya la demostración del dashboard y la exposición de los análisis y conclusiones realizados.

## Archivos contenidos en el proyecto
* Carpeta Datasets: archivos csv de los cuales se obtuvieron los datos para iniciar el proceso de Data Analytics y el archivo csv creado para realizar el dashboard.
		* Coursera_courses.csv: dataset con los datos de la plataforma Coursera
		* Coursera_reviews.csv: dataset complementario de la plataforma Coursera
		* Coursera.csv: dataset que reúne características relevantes y datos limpios de los dos primeros
		* edx_courses.csv: dataset con los datos de la plataforma edX
		* edx.csv: dataset que reúne características relevantes y datos limpios del csv anterior
		* udemy_courses.csv: dataset con los datos de la plataforma Udemy
* EDA.ipynb: notebook con el procedimiento realizado para el Análisis Exploratorio de Datos. En el mismo hay importadas librerías que utilicé al hacer algunas pruebas y que luego no eliminé. 
* Dashboard: archivo de PowerBI con el dashboard interactivo


## Reporte de análisis
* Análisis de dashboards
* Análisis y funcionalidad de KPIs

A partir del análisis EDA realizado en los 3 datasets proporcionados, obtuve las siguientes conclusiones:

*Udemy*
* La cantidad de inscriptos incrementó en general hasta el año 2015 y empezó a descender hasta 2020, dónde aumentó nuevamente. Estos descensos pueden deberse a varios motivos, que infiero cómo hipótesis, entre ellos:
	- Cambios en la oferta de cursos, tanto en cantidad o tipos. 
    - Cambios en las estrategias de marketing utilizadas para promocionar los cursos
    - Cambios económicos, como la situación económica general o la disponibilidad de recursos financieros de los estudiantes
    - Competencia en el mercado de cursos en línea, que posee alta competencia, por lo que, si los estudiantes tuvieron más opciones disponibles en el mercado pueden optar por cursos de otros proveedores
* El curso más popular es gratuito, para todos los niveles, dura aproximadamente 10 hs, está dentro de la temática Web Development y se dictó en el año 2013. De los que le siguen 50% son gratuitos y 50% pagos, 70% son para todos los niveles, duran en promedio 13 hs aproximadamente, el 80% están dentro de la categoría. Web Development y el 20% en Musical Instruments, están repartidos casi equitativamente entre los años 2013, 2014 y 2015. Por otro lado, los cursos menos populares son todos pagos un 20% son para todos los niveles, 40% nivel principiante y el restante 40% nivel intermedio. el tema que genera menos suscriptors es Business Finance
* En cuanto a la duración en relación a los niveles, aquellos que son para todos los niveles tienen la mayor duración promedio de 5 hs aproximadamente	
* La mayoría de los suscritpores se encuentra entre el mayor precio y los cursos gratuitos. A diferencia de quienes dejan sus reseñas que en mayor parte son quienes pagaron el precio más elevado Pero no es una correlación muy elevada
* Los temas con mayoría de cursos son 'Business Finance' y 'Web Development'. Los inscritpos se distribuyen dentro de esas dos categorías mayoritariamente, seguidos por Musical Instruments y Graphic Design
* El precio máximo que se paga por cursos en cualquiera de los temas, es $200. El promedio más caro se lo lleva Web Development con $77, seguido de Business Finance con $69
* Business Finance es el tema con la mayor cantidad de inscriptos, 696. El nivel de cursos más común en este tema es "All Levels", seguido de "Beginner Level" y "Intermediate Level". Hay un número limitado de inscriptos en el nivel "Expert Level". Graphic Design es el segundo tema más común, con 298 inscriptos en total. Al igual que en Business Finance, el nivel de cursos más común en Graphic Design es "All Levels". Sin embargo, también hay una proporción significativa de cursos en "Beginner Level" y "Intermediate Level". Musical Instruments tiene 276 inscriptos en total, y nuevamente, "All Levels" es el nivel de cursos más común en este tema. También hay una cantidad considerable de cursos en "Beginner Level" e "Intermediate Level". Web Development es el tema con la menor cantidad de cursos, con 659 cursos en total. El nivel de cursos más común en este tema es "All Levels", seguido de "Beginner Level" y "Intermediate Level". Hay un número muy limitado de cursos en el nivel "Expert Level".
* Los cursos de Web Development tienden a tener precios más altos en comparación con los otros temas, y también tienen un mayor número promedio de suscriptores. Por otro lado, los cursos de Musical Instruments tienen precios más bajos y un número promedio de suscriptores menor en comparación con los otros temas. Estas diferencias pueden reflejar la demanda y el valor percibido de los cursos en cada tema.
* Los cursos de Web Development tienden a tener una duración de contenido más larga en comparación con los otros temas, y también tienen un mayor número promedio de suscriptores. Por otro lado, los cursos de Musical Instruments tienen una duración de contenido más corta y un número promedio de suscriptores menor en comparación con los otros temas. Estas diferencias pueden reflejar las preferencias de los estudiantes en términos de la duración del contenido y la temática de los cursos.
* En Udemy sostuvieron los mismos subjects entre el año 2012 y 2017, pero en distintas cantidades de cursos. Por ejemplo, entre 2015 y 2017, redujeron en 1014 la cantidad.
* Se observa un aumento significativo en la cantidad de inscritos desde el año 2011 hasta el año 2015, con un pico de inscritos en 2015. A partir de 2016, se observa una disminución en el número de inscritos. 
* Distribución de suscriptores por tema:
	- El tema de "Web Development" tiene la mayor cantidad de suscriptores en todos los años.
	* "Business Finance" y "Graphic Design" también muestran una cantidad significativa de suscriptores, aunque en menor medida.
	* "Musical Instruments" tiene la menor cantidad de suscriptores en comparación con otros temas.
* Tendencias generales:
	* "Web Development" muestra un crecimiento constante en el número de suscriptores a lo largo de los años.
	* "Business Finance" y "Graphic Design" tuvieron un aumento inicial en los suscriptores, seguido de cierta estabilización o disminución en años posteriores.
	* "Musical Instruments" experimentó un crecimiento inicial, pero su número de suscriptores se ha mantenido relativamente estable o ha disminuido en los últimos años.

*Coursera*
* La popularidad de los MOOCs creció a partir del año 2020
* Puede que hayan alumnos que han cursado en varios cursos, dado que se repiten sus nombres/usuarios
* Revisando las celdas de reviews, hay comentarios que son exactamente iguales. Por ejemplo 'great course'.
* Los cursos de coursera tienen mayoria de rating = 5
* Los meses en los que la mayoría de las personas inician cursos son entre Abril y Septiembre, es decir, del segundo al tercer trimestre.
* Hay 1431064 reviewers duplicados, lo que puede implicar que una persona dejó comentarios en más de 1 curso. Según lo investigado en internet, una persona puede dejar su comentario/review en un curso de Coursera sin necesariamente haber terminado el curso, pero si debe haberse inscripto. 
* En cuanto a los comentarios, hay 1411528 duplicados. Por ejemplo 'Great course'. Pero decido no eliminar los duplicados y tampoco los faltantes de esta variable, ya que pueden ser filas que sean útiles para otro análisis. 
* De acuerdo a la categorización realizada con los id de los cursos, no hay relación entre los mismos y el rating, dado que todos tienen mayor frecuencia de rating = 5. 
* La cantidad de reviews por cada id, es directamente proporcional a la cantidad de cursos dentro de cada categoría.
* En la mayoría de los cursos los títulos están conformados por: Introduction, Management, Programming, Fundamental, Machine Learning, Data, Design, Data Science, Python, business, Understanding, International, Excel
* Mientras que, teniendo en cuenta que el listado total de títulos tiene que ver con la cantidad de inscriptos que dejaron sus reviews, las palabras que más predominan son: Machine Learning, Data Science, Neural Networks, Python Programming, Getting Started, Deep Learning, Google CloudLearning Machine.
* El top 10 de cursos con el mejor rating difiere de la cantidad de inscriptos. No hay relación, por ende, entre el rating y el número de inscriptos.

*edX*
* No se tiene información acerca de si hubo inscriptos que pagaran la certificación verificada de los cursos que las poseen. 
* A partir de las Word Clouds de 'summary' de los cursos con inscriptos vs los cursos sin inscriptos, se obtiene que las palabras que tienen los cursos de la segunda categoría y no la primera son: 'concept', 'language', 'project', 'build' y en cambio la primera tiene: 'Explore', 'business', 'use', 'design', 'world', 'basic', 'system', 'using', 'skill'
* No hay correlación entre la longitud de las descripciones y la cantidad de inscriptos
* Que los cursos tengan inscriptos o no, no depende si el curso tiene descripción o no.
* La cantidad de enrolados tiene una correlación muy débil con el precio de los certificados, no es significativa
* El 95% de inscriptos se anotó en cursos Self-paced
* La Universidad de Harvard se lleva la mayor cantidad de inscriptos, y al igual que en Coursera, la mayor cantidad de inscriptos no está sólo en cursos que dictan universidades.
* Los temas con mayoría de inscriptos son: Computer Science, Business & Management, Communication, Data Analytics & Statistics, Humanities, Biology & Life Sciences, Engineering, Language, Medicine
* El idioma predominante, tanto en el lenguaje original cómo en los subtítulos, a la hora de inscribirse es Inglés, seguido de Español.
* A partir del análisis de chi-cuadrado, se infiere que existe una asociación significativa entre el lenguaje original, los subtítulos y la cantidad de inscriptos en los cursos. Además resulta de amplia diferencia si los cursos tienen subtítulos
* Aunque existe una correlación positiva débil entre las horas mínimas y máximas semanales que duran las cursadas,  con la cantidad de inscriptos, no parece ser un factor determinante en la cantidad de personas que se inscriben en los cursos
* El coeficiente de correlación entre la duración de los cursos y la cantidad de inscriptos es débil.  

Analizando los KPI y su funcionalidad, concluyo que:
* Tasa de conversión: Este KPI da un valor de la cantidad de personas que ingresaron a los cursos de forma gratuita vs quienes se inscribieron a los cursos pagos. El valor indica que en promedio se realizan 2,89 conversiones, es decir que se obtienen 2,89 inscriptos pagados por cada inscripto gratuito. Con este indicador se puede medir el progreso de la empresa hacia su objetivo de incrementar un 15% la tasa de conversión en un año. 

Además sugiero utilizar los siguientes KPIs:
* Promedio de Calificación por Mes y Año: propongo obtener este KPI para calcular el promedio de calificación (rating: del 1 al 5) en relación a los meses y años en los que se dictaron para evaluar la calidad ofrecida a los estudiantes en diferentes períodos de tiempo. 
* Promedio de unidades por curso: es útil para comprender la estructura y el contenido de los cursos, en cuanto a extensión y profundidad del contenido. Para la empresa además será útil para tener una comparativa frente a los cursos que dictan otros competidores, para planificar los tiempos de estudio necesarios y para diseñar y estructurar nuevos cursos, ajustando el valor de acuerdo a los objetivos. 
* Proporción/Ratio de cursos con subtítulos: sugiero realizar esta medición de performance ya que permite abarcar un mercado mayor de personas, ofrece una experiencia de aprendizaje inclusiva (ejemplo: preferencias por aprender leyendo y no escuchando), demuestra que la empresa tiene interés por estas situaciones, permite ampliar el alcance a otras zonas, comparar la oferta propia con la de otras plataformas, si se pone esfuerzo en implementar los subtítulos se puede percibir cómo calidad del curso. 
