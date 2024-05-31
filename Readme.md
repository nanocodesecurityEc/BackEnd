# Servidor HTTP básico para una API de gestión de usuarios

Este proyecto consiste en la implementación de un servidor HTTP básico utilizando JavaScript puro para crear una API simple de gestión de usuarios.

## Descripción del ejercicio

El objetivo es desarrollar un servidor capaz de manejar solicitudes HTTP GET, POST, PUT y DELETE para interactuar con usuarios almacenados en memoria.

## Requisitos

### Variables, tipos de datos, operadores, estructuras de control

- Se declaran variables para almacenar los usuarios en memoria.
- Se utilizan estructuras de control como if, else, for o while según sea necesario para manejar diferentes casos en las solicitudes HTTP.

### Funciones

- Se declaran funciones para manejar las acciones asociadas a cada tipo de solicitud (GET, POST, PUT, DELETE).
- Se prefieren las funciones de flecha para mantener el contexto this.

### Objetos y arrays

- Se utilizan objetos para representar usuarios, con propiedades como id, nombre, correo, etc.
- Los usuarios se almacenan en un array.
- Se utilizan métodos de array como map, filter o reduce si es necesario para manipular los datos de los usuarios.
- Se implementa la desestructuración para manejar los datos de las solicitudes HTTP.

### Programación asíncrona

- Se utilizan callbacks para manejar operaciones asíncronas si es necesario.
- Se considera el uso de promesas para operaciones asíncronas más complejas.
- Se utiliza async/await para manejar la asincronía de manera más legible y sencilla.

### Conceptos avanzados

- Se implementan closures si es necesario para encapsular variables o comportamientos.
- Se utilizan eventos para manejar diferentes acciones dentro del servidor.
- Se implementa manejo de errores para devolver respuestas adecuadas en caso de errores en las solicitudes.
- Se utilizan clases y módulos en ES6+ para organizar y estructurar el código de manera eficiente.

## Puntos adicionales (opcional)

- Se agrega autenticación básica utilizando tokens JWT.
- Se implementa la persistencia de datos utilizando el sistema de archivos del servidor o una base de datos simple como JSON o SQLite.


## Capturas
Se debe ejecutar el servidor en el puerto 3000


![image](https://github.com/nanocodesecurityEc/BackEnd/assets/168138135/7405e896-18a7-4352-b7da-bc5134c099ba)

![image](https://github.com/nanocodesecurityEc/BackEnd/assets/168138135/1161a126-d4c6-4236-bf31-f04aef8488fb)
![image](https://github.com/nanocodesecurityEc/BackEnd/assets/168138135/33a04424-bb0c-41c1-a72b-ee332ddde978)
![image](https://github.com/nanocodesecurityEc/BackEnd/assets/168138135/053ff30f-545b-4b6c-a57d-5ceccbe9aae0)
![image](https://github.com/nanocodesecurityEc/BackEnd/assets/168138135/9e0f8c31-6f9a-4249-a873-bdb9d4ec21f3)

# JSON de ejemplo para introducir en los metodos

```json
{
    "id": 1,
    "name": "John Doe",
    "email": "john@example.com"
}




