Este proyecto se hizo a través del bootcamp de Tripleten para la formación de nuevos analistas de datos. En el sprint 8 (enfocado en la recopilación y el almacenamiento de datos), se busca analizar el comportamiento de los taxis y sus viajes en diferentes días y condiciones climatológicas con el fin de probar la hipótesis de que los días sábados, que sean lluviosos, hay más probabilidades de que aumente la duración de un viaje de cualquier parte de la ciudad al Aeropuerto Internacional de O'Hare de Chicago.

Este proyecto comprendió las siguentes instrucciones:

Paso 1. Análisis exploratorio de datos (Python)

Se tienen estos tres CSV:

-project_sql_result_01.csv. Que contiene los siguientes datos:

company_name: nombre de la empresa de taxis
trips_amount: el número de viajes de cada compañía de taxis el 15 y 16 de noviembre de 2017. 

-project_sql_result_04.csv. Que contiene los siguientes datos:

dropoff_location_name: barrios de Chicago donde finalizaron los viajes
average_trips: el promedio de viajes que terminaron en cada barrio en noviembre de 2017.

-project_sql_result_07.csv — Contiene datos sobre viajes desde el Loop hasta el Aeropuerto

start_ts: fecha y hora de la recogida
weather_conditions: condiciones climáticas en el momento en el que comenzó el viaje
duration_seconds: duración del viaje en segundos

Para los dos primeros datasets, se necesitó:

-importar los archivos
-estudiar los datos que contienen
-asegurarte de que los tipos de datos sean correctos
-identificar los 10 principales barrios en términos de finalización del recorrido
-hacer gráficos: empresas de taxis y número de viajes, los 10 barrios principales por número de finalizaciones
-sacar conclusiones basadas en cada gráfico y explicar los resultados


Paso 2. Prueba de hipótesis (Python)

hipótesis:

"La duración promedio de los viajes desde el Loop hasta el Aeropuerto Internacional O'Hare cambia los sábados lluviosos".

Para comprobar esta hipótesis, se tuvo que plantear en el jupyter notebook los siguientes puntos:

-plantear las hipótesis nula y alternativa
-criterio usado para probar las hipótesis y por qué
-El cómo será evaluado el proyecto

Lo que buscó el revisor del proyecto fue:

-cómo se recuperaron los datos del sitio web
-cómo se crearon los slices de datos
-agrupación de los datos
-si uso correctamente los diversos métodos para combinar datos
-fórmulas de las hipótesis
-criterios usados para probar las hipótesis y por qué
-Conclusiones generales