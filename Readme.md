# Data Anlytics - Data Visualization

## Individual Project: MOOCs
The objective of the project is to perform a market analysis of online courses using an EDA (Exploratory Data Analysis), generate interactive visualizations and present relevant conclusions based on the data, including the tracking of KPIs that allow to evaluate the company's performance compared to its objectives.

## Description of the problem
The company's problem in this context is to enter the online course market efficiently and competitively. While there is a high demand in the sector, there is also strong competition among the various platforms and universities offering online courses.
You need to adjust your business model, courses and content offered to attract and retain as many customers as possible. Therefore, it is essential to understand what factors influence course sales. In this case, the specific problem is to analyze and determine the influence of price, language, level and rating of the courses on the demand for the product sold.
In addition, the objective is to increase the conversion rate from free to paid enrollees by 15% compared to the previous year. To achieve this, a thorough analysis of the data and the identification of effective strategies to increase conversion is required.

In summary, the company's problem is to compete in the online course market effectively by adjusting its offerings and business strategies based on data analysis and understanding the factors that influence sales and user conversion.

## Work proposal
The project is divided into the following tasks:

 1. DATA COLLECTION AND EXPLORATION: Obtain datasets of competitors in the online course market, including relevant information such as price, language, level, rating and sales data. Perform an exploratory analysis of the data to understand its structure, quality and characteristics.
    
2. SALES SEGMENTATION: Perform a sales segmentation analysis based on the variables available in the datasets. Group courses according to price, language, level and rating, and analyze how they relate to sales. Use visualizations and descriptive metrics to identify patterns and trends.
    
3.  VARIABLES INFLUENCE ANALYSIS: Evaluate the influence of variables (price, language, level, rating) on course demand. Use statistical techniques such as correlation analysis, hypothesis testing or other predictive models to determine the relationship between variables and sales.
    
4.  CREATE A WORD CLOUD: Process course titles and generate a Word Cloud showing the most frequent keywords. This will identify popular topics and relevant approaches to course offerings.
    
5.  ESTABLISH KPIs: Define a set of Key Performance Indicators (KPIs) related to course demand and conversion. One of the proposed KPIs is the conversion rate from free to paid subscribers.Look for complementary datasets and evaluate this KPI on the different platforms to get a broader view.

6.  DASHBOARD DEVELOPMENT: Create an interactive dashboard showing the data, visualizations and analysis obtained.The dashboard should include filters and selection options to explore the data in detail.Design a clear and coherent presentation of the information, using relevant graphics and an aesthetic layout that facilitates the interpretation of the data.

7.ANALYSIS AND CONCLUSIONS: Perform an in-depth analysis of the data and visualizations obtained.Draw relevant conclusions about the influence of variables on sales, identify interesting patterns and propose strategies to increase user conversion. Present the results in a detailed report and interactive dashboard.
    
8.  ADDITIONAL CHALLENGES (optional): As an additional challenge, it is suggested to perform data crosswalks with complementary datasets to obtain additional information or compare performance on different platforms. The creation of a database in a SQL engine and the execution of Python scripts in the selected visualization tool can also be considered.
    
9.  DOCUMENTATION AND FINAL PRESENTATION: Prepare a GitHub repository containing a Readme with an overview of the project, the file structure and an analysis report based on the dashboard and suggested KPIs. 

10. PRESENTATION: Prepare a presentation of no more than 10 minutes that includes a demonstration of the dashboard and a presentation of the analysis and conclusions made.

## Files contained in the project
* Datasets folder: csv files from which the data were obtained to start the Data Analytics process and the csv file created to create the dashboard.
		* Coursera_courses.csv: dataset with data from the Coursera platform.
		* Coursera.csv: dataset that gathers relevant characteristics and clean data from the two Coursera datasets.
		* edx_courses.csv: dataset with data from the edX platform
		* edx.csv: dataset that gathers relevant features and clean data from the previous csv
		* udemy_courses.csv: dataset with data from the Udemy platform.
  		* Note: the second coursera dataset is not loaded because it exceeds the size allowed by GitHub.
* EDA.ipynb: notebook with the procedure performed for the Exploratory Data Analysis. In it there are imported libraries that I used when doing some tests and that I did not remove later. 
* Dashboard: PowerBI file with the interactive dashboard.


## Analysis report
* Dashboard analysis
* KPI analysis and functionality

From the EDA analysis performed on the 3 datasets provided, I obtained the following conclusions:

*Udemy
* The number of enrollees increased overall until 2015 and started to decline until 2020, where it increased again. These declines may be due to several reasons, which I infer as hypotheses, among them:
	- Changes in the supply of courses, both in quantity or types. 
    - Changes in the marketing strategies used to promote the courses.
    - Economic changes, such as the general economic situation or the availability of students' financial resources.
    - Competencia en el mercado de cursos en línea, que posee alta competencia, por lo que, si los estudiantes tuvieron más opciones disponibles en el mercado pueden optar por cursos de otros proveedores
    - Competition in the market of online courses, which has high competition, so if students had more options available in the market they can opt for courses from other providers.
* The most popular course is free, for all levels, lasts approximately 10 hours, is within the subject Web Development and was taught in 2013. Of those that follow 50% are free and 50% paid, 70% are for all levels, last on average 13 hours approximately, 80% are within the category. Web Development and 20% in Musical Instruments, are almost equally distributed between the years 2013, 2014 and 2015. On the other hand, the least popular courses are all paid 20% are for all levels, 40% beginner level and the remaining 40% intermediate level. the topic that generates less subscribers is Business Finance.
* In terms of duration in relation to the levels, those that are for all levels have the longest average duration of approximately 5 hours.
* The majority of subscribers are between the highest price and the free courses. Unlike those who leave reviews who are mostly those who paid the highest price But it is not a very high correlation.
* The subjects with the most courses are 'Business Finance' and 'Web Development'. The enrolments are mostly distributed within these two categories, followed by Musical Instruments and Graphic Design.
* The maximum price paid for courses in any of the subjects is $200. The most expensive average is Web Development at $77, followed by Business Finance at $69.
* Business Finance is the subject with the highest number of enrolments, 696. The most common course level in this topic is "All Levels", followed by "Beginner Level" and "Intermediate Level". There are a limited number of registrants at the "Expert Level" level. Graphic Design is the second most common subject, with 298 total registrants. As in Business Finance, the most common course level in Graphic Design is "All Levels". However, there is also a significant proportion of courses at "Beginner Level" and "Intermediate Level". Musical Instruments has 276 total enrolments, and again, "All Levels" is the most common course level in this subject. There are also a considerable number of courses at "Beginner Level" and "Intermediate Level". Web Development is the subject with the smallest number of courses, with 659 courses in total. The most common course level in this topic is "All Levels", followed by "Beginner Level" and "Intermediate Level". There are a very limited number of courses at the Expert Level.
* Web Development courses tend to have higher prices compared to the other topics, and also have a higher average number of subscribers. On the other hand, Musical Instruments courses have lower prices and a lower average number of subscribers compared to the other topics. These differences may reflect the demand and perceived value of the courses in each topic.
* At Udemy they held the same subjects between 2012 and 2017, but in different amounts of courses. For example, between 2015 and 2017, they reduced the number by 1014.
* A significant increase in the number of enrollees is observed from 2011 to 2015, with a peak of enrollees in 2015. From 2016 onwards, a decrease in the number of enrollees is observed. 
* Distribution of subscribers by topic:
	- "Web Development" topic has the highest number of subscribers in all years.
	* "Business Finance" and "Graphic Design" also show a significant number of subscribers, although to a lesser extent.
	* "Musical Instruments" has the least amount of subscribers compared to other topics.
* General trends:
	* "Web Development" shows a steady growth in the number of subscribers over the years.
	* "Business Finance" and "Graphic Design" had an initial increase in subscribers, followed by some stabilization or decline in later years.
	* "Musical Instruments" experienced initial growth, but its number of subscribers has remained relatively stable or declined in recent years.

*Coursera*
* The popularity of MOOCs grew from 2020 onwards.
* There may be students who have taken several courses, as their names/users are repeated.
* Reviewing the review cells, there are comments that are exactly the same. For example 'great course'.
* The coursera courses have majority rating = 5.
* The months when most people start courses are between April and September, i.e. the second to third quarter.
* There are 1431064 duplicate reviewers, which may imply that one person left reviews on more than 1 course. According to research on the internet, a person can leave a comment/review on a Coursera course without necessarily having completed the course, but must have enrolled. 
* As for the comments, there are 1411528 duplicates. For example 'Great course'. But I decide not to remove the duplicates and also not to remove the missing ones from this variable, as they may be rows that are useful for another analysis. 
* According to the categorization made with the course ids, there is no relationship between them and the rating, since they all have a higher frequency of rating = 5. 
* The number of reviews for each id is directly proportional to the number of courses within each category.
* In most courses the titles consist of: Introduction, Management, Programming, Fundamental, Machine Learning, Data, Design, Data Science, Python, business, Understanding, International, Excel.
* While, taking into account that the total list of titles has to do with the number of registrants who left their reviews, the most predominant words are: Machine Learning, Data Science, Neural Networks, Python Programming, Getting Started, Deep Learning, Google CloudLearning Machine.
* The top 10 courses with the best rating differ from the number of enrollees. There is no relationship, therefore, between the rating and the number of enrollees.

*edX*
* There is no information about whether there were registrants who paid for the verified certification of the courses that have them. 
* From the Word Clouds of 'summary' of the courses with enrolments vs. courses without enrolments, it is obtained that the words that the courses of the second category have and not the first are: 'concept', 'language', 'project', 'build' and on the other hand the first has: 'Explore', 'business', 'use', 'design', 'world', 'basic', 'system', 'using', 'skill', 'skill', 'system', 'using', 'skill', 'basic', 'system', 'system', 'using', 'skill', 'skill', 'skill', 'skill', 'skill', 'skill', 'skill', 'skill', 'skill', 'skill'.
* There is no correlation between the length of the descriptions and the number of registrants.
* Whether courses have enrolments or not does not depend on whether the course has a description or not.
* The number of enrollees has a very weak correlation with the price of certificates, it is not significant.
* 95% of enrollees enrolled in self-paced courses.
* Harvard University has the largest number of enrollees, and as in Coursera, the largest number of enrollees is not only in courses taught by universities.
* The subjects with the most enrolments are: Computer Science, Business & Management, Communication, Data Analytics & Statistics, Humanities, Biology & Life Sciences, Engineering, Language, Medicine.
* The predominant language, both in the original language and in the subtitles, at the time of registration is English, followed by Spanish.
* From the chi-square analysis, it is inferred that there is a significant association between the original language, subtitles and the number of course enrollments. It also makes a significant difference if the courses have subtitles.
* Although there is a weak positive correlation between the minimum and maximum weekly course hours and the number of students enrolled, it does not seem to be a determining factor in the number of people who enroll in the courses.
* The correlation coefficient between the duration of the courses and the number of enrolments is weak.  

Analyzing the KPIs and their functionality, I conclude that:
* Conversion rate: this KPI gives a value of the number of people who entered the courses for free vs. those who enrolled in the paid courses. The value indicates that on average 2.89 conversions are made, i.e. 2.89 paid enrollees are obtained for each free enrollee. With this indicator you can measure the company's progress towards its goal of increasing the conversion rate by 15% in one year. 

In addition, I suggest using the following KPIs:
* Average Rating per Month and Year: I propose to obtain this KPI to calculate the average rating (rating: from 1 to 5) in relation to the months and years in which they were delivered to evaluate the quality offered to students in different periods of time. 
* Average number of units per course: it is useful to understand the structure and content of the courses, in terms of length and depth of content. For the company it will also be useful to have a comparison with courses offered by other competitors, to plan the necessary study time and to design and structure new courses, adjusting the value according to the objectives. 
* Proportion/Ratio of courses with subtitles: I suggest performing this performance measurement since it allows covering a larger market of people, offers an inclusive learning experience (example: preferences for learning by reading and not listening), shows that the company is interested in these situations, allows extending the reach to other areas, comparing its own offer with that of other platforms, if effort is put in implementing subtitles, it can be perceived how the quality of the course is. 

-----------------------------------------------------------------------------------------------------
 
# Data Analytics - Data Visualization

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
		* Coursera.csv: dataset que reúne características relevantes y datos limpios de los dos datasets de coursera
		* edx_courses.csv: dataset con los datos de la plataforma edX
		* edx.csv: dataset que reúne características relevantes y datos limpios del csv anterior
		* udemy_courses.csv: dataset con los datos de la plataforma Udemy
  		* Aclaración: el segundo dataset de coursera no se carga porque excede el tamaño permitido por GitHub
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
