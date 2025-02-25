# Controllers

Los **Controllers** son componentes clave en el patrón de arquitectura MVC (Modelo-Vista-Controlador) que se encargan de recibir las solicitudes (requests) del cliente y devolver las respuestas (responses). En el backend, los controladores gestionan la interacción entre los modelos (lógica de datos) y las vistas (interfaz o respuestas) de la aplicación.

## Funciones principales:
- **Recibir solicitudes**: Los controladores reciben las solicitudes HTTP, como GET, POST, PUT y DELETE.
- **Procesar lógica de negocio**: Los controladores procesan las solicitudes, a menudo interactuando con los servicios para realizar la lógica de negocio.
- **Llamar a los modelos**: Los controladores interactúan con los modelos para recuperar o modificar datos en la base de datos.
- **Enviar respuestas**: Los controladores devuelven una respuesta adecuada al cliente, generalmente en formato JSON o HTML.
