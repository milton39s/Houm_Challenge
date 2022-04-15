# Houm_Challenge

Introducción	


Houm es una startup que permite administrar, arrendar y vender propiedades rápido, seguro y fácil a miles de usuarios en Latinoamérica. En su desafío por entregar la mejor experiencia de usuarios, la empresa y su head de operaciones le pide hacer un estudio sobre el comportamiento de sus visitas en torno al clima. Es por esto que lo contactan a usted para dar respuestas a las preguntas de la compañía.



Carlos, nuestro data scientist, le informa que existen tres fuentes de información relevantes, las cuales contienen información de la operación que podrían ser de utilidad. Los tres archivos se detallan a continuación (presentes en el archivo dataset.zip adjunto):



    properties.csv: Contiene información básica de las características de la propiedad y su información geográfica. Las columnas de este archivo son las siguientes: property_id, business_type, type, bedrooms, bathrooms, latitude, longitude, locality, city & country.


    users.csv: Contiene la información de los propietarios y su relación con la propiedad. Las columnas de este archivo son las siguientes: property_id, user_id, name, last_name & country.


    visits.csv: Contiene la información de los clientes que se han registrado en alguna visita a una propiedad. Las columnas de este archivo son las siguientes: schedule_id, property_id, begin_date, end_date, type_visit & status.


Por otro lado, Carlos le comenta que existe un servicio para obtener información de las condiciones climáticas de cada país. Se puede consultar este servicio por medio de su API, la cual esta documentada aquí. Se puede consultar la temperatura y clima de una localidad mediante la siguiente consulta. 



Ejemplo de Request API Wheather VisualCrossing:

https://weather.visualcrossing.com/VisualCrossingWebServices/rest/services/timeline/{lat},{lng}/{start_date}/{end_date}?key={API_KEY}&include=days



Posibles condiciones climáticas retornada por la API: 

https://github.com/visualcrossing/WeatherApi/blob/master/lang/en.txt



Nota: Para la utilización de la api se debe proveer el siguiente API KEY. Esta tiene un límite de 1.000 registros al día. Debes registrarte en https://www.visualcrossing.com/sign-up para obtener la KEY.



Preguntas del desafío:


¿Cuántas visitas se realizaron en total?
¿Cuál es el promedio de propiedades por usuario?
¿Cuál era la temperatura promedio de todas las visitas que realizó el usuario con ID 2?
¿Cuál es la temperatura promedio de las visitas para los días con lluvia?
¿Cuál es la temperatura promedio para las visitas realizadas en la localidad de Suba?




Formato de entrega: 


Para entregar este desafío te solicitamos compartirnos un link de un repositorio en github o gitlab. Este repositorio debe contener un archivo en formato ipynb o py con las respuestas. Debes entregar un archivo requierements.txt con las versiones de las librerías ocupadas.
