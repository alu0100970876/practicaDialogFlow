# practicaDialogFlow

Tras muchos intentos de integrar google DialogFlow con Unity, lo más que hemos conseguido implementar es que lleguen las respuestas del servidor de google con un pequeño agente conversacional hecho por nosotros.

El código para este interaccion se puede encontrar en este repositorio. En la escena, al generar una colisión con un objeto se manda una peticion con un mensaje de texto al chatbot y este manda el paquete con la info de la respuesta (como se puede ver en la siguiente imagen ) que no hemos sido capaces de darle uso.
[!image]()

Tras hacer esta practica hemos llegado a la conclusión de que si bien esta tecnología es muy util para cierto tipo de interfaces, para cualquier tipo de juego se convierte en una carga al tener que mandar las peticiones y esperar la respuesta del server (las respuestas estan tardando del orden de 2 segundos en los que unity se bloquea) asi que no lo añadiremos al trabajo final.
