# APP sobre preguntas tipo test

Consume la API de https://api-programming-questions.onrender.com/
Modifica todo el HTML que necesites.

## Iteración 1

Rellena cada elemento del DOM con la información obtenida de la API

- Pregunta 
- Posibles respuestes
- Respuesta correcta

Al hacer clic en el botón _Revelar respuesta correcta_ debe revelearse la respuesta correcta.

## Iteración 1.5

Fíjate que el JSON trae más información, como una referencia a la documentación a consultar una vez hemos contestado a la pregunta tipo test. Añade esta información también en el DOM para que pueda consultarla el usuario.

## Iteración 2

Mezcla las posibles respuestas para que estas no tengan siempre el mismo orden al recuperarlas de la API

## Iteración 3

Añade un botón para poder pedir una nueva pregunta tipo test a la aPI

## Iteración _waiting my team_

Mientras tus compañeros implementan otras funcionalidades de la API, haz que la app sea un poco más _tipo test_. Por ejemplo, que puedas hacer clic sobre una pregunta tipo test y te la ponga en verde o rojo si la has acertado o no.

## Iteración 4

Añade un selector para elegir la categoría de la pregunta tipo test.
Este selector debe rellenarse con las categorías que provee la API

## Iteración 5

Tras realizar la pregunta tipo test, implemente dos botones para poder votar positiva o negativamente sobre una pregunta tipo test.

<img src="https://oscarm.tinytake.com/media/166e515?filename=1721287218440_TinyTake18-07-2024-09-20-07_638568840167408950.png&sub_type=thumbnail_preview&type=attachment&width=607&height=414" title="Powered by TinyTake Screen Capture"/><br>

Consulta la documentación de la API para saber como realizar esta acción.

## Iteración 6

Crea una nueva sección en la app para proponer nuevas preguntas tipo test a la API.
Puedes crear un formulario con todos los campos necesarios para agregar un nueva pregunta.
Consulta la documtación de la API para saber que JSON debes generar y a donde tienes que ejecutar la petición de tipo POST.