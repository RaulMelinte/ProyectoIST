Proyecto IST
Periódico digital con solitario y conversor


Daniel Olivares Garces
David Herraíz Zanón
Félix Bernal Sánchez
Raúl Melinte

El proyecto ha sido subido al siguiente repositorio de GitHub:
https://github.com/RaulMelinte/ProyectoIST

El proyecto ha consistido en tomar el periódico digital programado durante las sesiones de practicas, para tener la estructura de una web entera, y ampliar la parte del solitario, así como crear una sección Economía con un conversor de monedas en tiempo real.

En la sección Ocio encontramos el solitario.
El juego del solitario es un juego de cartas para un único jugador, en el cual se utiliza una baraja normal de 52 cartas. El juego es conocido mundialmente y presenta muchas variantes.
 
El objetivo del juego es conseguir 4 mazos uno para cada palo en los que la última carta sea la K y la primera carta la A, en orden y alternando el color de los palos.
Para realizar el juego se ha partido del archivo de la práctica número 6, donde se realizó la lógica del juego, el cual se ha mejorado visualmente mediante CSS añadiendo:
•   Fondo.
•   Zonas de los mazos.
•   Títulos en color y diferentes efectos.
Mediante Javascript y html se ha añadido:
•   Un reproductor de música.
•   Una ventana que solicita el nombre o Nick del jugador al iniciar el juego y que luego aparece en el fondo.


En la sección Economía encontramos el conversor de monedas:
Para obtener el valor de las monedas se ha hecho uso del servicio web https://ratesapi.io/, el cual se actualiza diariamente con datos del banco central europeo e incluye información desde el año 1999. 
 

El conversor pide introducir la cantidad a convertir así como su moneda, y la moneda destino. Si se desea se puede seleccionar otra fecha, y la conversión se hará con las equivalencias de ese día. 
Al darle al botón de convertir, se ejecuta un clip de música, se construye un string con la fecha y las monedas, que es la url del servicio web. Al acceder al servicio se recibe un JSON, del que se extrae la equivalencia entre ambas monedas, tras lo cual se multiplica y se muestra la cifra final.
Si se pasa el raton por encima del icono “?” aparecerá una breve explicación.
Se ha empleado HTML/CSS para la estructura y estética, y para mostrar el mensaje de ayuda.
Para la parte de conversión y mostrar el calendario se ha usado JavaScript, y para solicitar el JSON se ha usado una función de JQuery.

