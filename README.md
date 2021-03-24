# Ejercicio práctico para Ingeniero de Datos Jr en Deacero.

Debe realizar un fork de este repositorio para desarrollar y entregar su trabajo.

1. Obtén los datos de las siguientes fuentes desde las apis:

| Dataset                   | Url                                                               |
| ------------------------- | ----------------------------------------------------------------- |
| Lista Pasajeros 2016      | http://analytics.deacero.com/Api/GetApi/ApiPasajeros2016/api_key  |
| Lista Pasajeros 2017      | http://analytics.deacero.com/Api/GetApi/ApiPasajeros2017/api_key  |
| Lista Viajes 2016         | http://analytics.deacero.com/Api/GetApi/ApiVuelos2016/api_key     |
| Lista Viajes 2017         | http://analytics.deacero.com/Api/GetApi/ApiVuelos2017/api_key     |
| Lista Aerolíneas          | http://analytics.deacero.com/Api/GetApi/ApiLineaAerea/api_key     |

  Nota: El api_key válido se proporciona por correo.

2. Se tiene un requerimiento de análisis de las fuentes de datos de pasajeros y viajes. Como podrás observar, las listas se han estado llevando por año. En esta primera parte del reto se te pide: 
    - Unir cada conjunto de datos en una sola lista. 
    - Explicar el proceso realizado. 
    - En caso de detectar anomalías generadas por esta unión, deberás indicar el tipo de anomalía que se presenta, como se puede resolver y resolverlo de ser posible. 

3. De lo obtenido anteriormente se requiere relacionar las listas de vuelos y pasajeros, que permitan analizar el perfil del pasajero por cada vuelo efectuado. De tal forma que se puedan obtener datos consolidados. En esta parte deberás: 
    - Explicar el proceso que utilizado para unir los pasajeros y los vuelos.  
    - Qué tipo de relación y por qué. 

4. Ahora se requiere que los datos consolidados de los vuelos y pasajeros se puedan unir con los datos de las Líneas Aéreas. En el caso de que la línea aérea no se pueda relacionar con la de vuelos y pasajeros se deberá indicar que se trata de “Otra” y finalmente se deberá dejar únicamente las columnas: 
    - Fecha del viaje 
    - Clase 
    - Precio 
    - Ruta 
    - Edad 
    - Línea Aérea

   En esta parte deberás indicar: 
    - ¿Qué tipo de proceso consideraste para unir los datos que se piden? 
    - ¿Qué columnas utilizaste para lograr esa relación? 
    - ¿Qué tipo de unión utilizaste para unir los datos? 
    - ¿Qué tipo de proceso utilizaste para dejar únicamente las columnas que se piden? 
   
5. Por último, se requiere esta misma información por Clase, Ruta, Línea Aérea y los promedios de Precio y Edad por cada semestre de cada año, el primer semestre es de Ene - Jun y el segundo es de Jul - Dic. 

Los ejercicios deben realizarse en Python, además de un documento donde se contesten las preguntas y se muestren los resultados de las transformaciones. En caso de trabajar con notebooks de jupyter puede exportarse en HTML. 

Una vez concluido el reto se debe comunicar al correo correspondiente con la liga al repositorio de github final para evaluar las respuestas.


Suerte a todos!!! :metal: :nerd_face: :computer:
