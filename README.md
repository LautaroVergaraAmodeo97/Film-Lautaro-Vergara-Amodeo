### Proceso de Desarrollo

Antes de aplicar técnicas avanzadas de machine learning, se realizó una exhaustiva limpieza, transformación y normalización de los datos

#### ETL

El proceso de extracción, transformación y carga (ETL) se llevó a cabo en las siguientes libretas:

1. **movies_dataset**: Datasets con películas.
2. **credits**: Dataset con actores y equipo de filmación.


He utilizado estos datos para realizar el trabajo desde el github oficial de Soy Henry: [link_limpieza](https://github.com/soyHenry/fe-ct-pimlops2)


#### EDA
En este proyecto de Data Science, se ha llevado a cabo un exhaustivo Análisis Exploratorio de Datos (EDA) para comprender mejor el dataset de películas. A continuación, se presentan las visualizaciones y los hallazgos clave del análisis:

**Nube de Palabras: Títulos Más Comunes**
Se ha generado una nube de palabras para identificar los títulos más comunes en el dataset. Esta visualización muestra la frecuencia de las palabras en los títulos de las películas, destacando las palabras más recurrentes y proporcionando una visión rápida de los patrones comunes en los títulos.

**Barplots**
  Títulos Más Populares: Se ha creado un barplot para mostrar los títulos de películas con mayor popularidad. Este gráfico permite identificar las películas que han captado la mayor atención del público, ofreciendo una visión clara de las preferencias de los usuarios.

  Compañías Más Famosas: Otro barplot destaca las compañías cinematográficas más destacadas según el número de películas producidas. Este análisis ayuda a entender cuáles son las compañías más influyentes en la industria del cine.

  Géneros Más Populares: Se ha generado un barplot para visualizar los géneros de películas más populares. Este gráfico muestra la distribución de géneros y permite identificar las categorías más prevalentes en el dataset.

  **Histogramas**
  Calificaciones: En este gráfico se puede ver cual es el promedio de calificaciones de nuestras películas que tenenmos en nuestro dataset.

  
# Desarrollo de API
Como parte de este ejercicio, se han desarrollado seis funciones dentro de la API FastAPI para realizar consultas específicas en el conjunto de datos de Steam.

1.def cantidad_filmaciones_mes( Mes ): Se ingresa un mes en idioma Español. Debe devolver la cantidad de películas que fueron estrenadas en el mes consultado en la totalidad del dataset.
                  
2.def cantidad_filmaciones_dia( Dia ): Se ingresa un día en idioma Español. Debe devolver la cantidad de películas que fueron estrenadas en día consultado en la totalidad del dataset.
      
3.def score_titulo( titulo_de_la_filmación ): Se ingresa el título de una filmación esperando como respuesta el título, el año de estreno y el score.
            
4.def votos_titulo( titulo_de_la_filmación ): Se ingresa el título de una filmación esperando como respuesta el título, la cantidad de votos y el valor promedio de las votaciones. La misma variable deberá de contar con al menos 2000 valoraciones, caso contrario, debemos contar con un mensaje avisando que no cumple esta condición y que por ende, no se devuelve ningun valor.
           
5.def get_actor( nombre_actor ): Se ingresa el nombre de un actor que se encuentre dentro de un dataset debiendo devolver el éxito del mismo medido a través del retorno. Además, la cantidad de películas que en las que ha participado y el promedio de retorno. La definición no deberá considerar directores.

6.def get_director( nombre_director ): Se ingresa el nombre de un director que se encuentre dentro de un dataset debiendo devolver el éxito del mismo medido a través del retorno. Además, deberá devolver el nombre de cada película con la fecha de lanzamiento, retorno individual, costo y ganancia de la misma.

# Sistema de recomendación

1.def recomendacion( titulo ): Se ingresa el nombre de una película y te recomienda las similares en una lista de 5 valores.



Lo que muestro en el vídeo es sobre este Render :[link_render](https://film-lautaro-vergara-amodeo.onrender.com)

Y aquí les dejo el link del vídeo del proyecto: [video](https://youtu.be/t5tS6kgMVvs)

Por las dudas que no puedan ver el vídeo en Youtube, les dejo este mismo en Drive: [video](https://drive.google.com/file/d/1o0K1HU0ry6NWDxLaHQZ9muPI_ohH22L6/view?usp=sharing)
