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




# JSON de ejemplo para introducir en los metodos

```json
{
    "id": 1,
    "name": "John Doe",
    "email": "john@example.com"
}
# Capturas
![image](https://github.com/nanocodesecurityEc/BackEnd/assets/168138135/0dac9aa9-4d10-4fa0-9f23-7f8639dc4cca)
![image](https://github.com/nanocodesecurityEc/BackEnd/assets/168138135/1c172d06-a243-46dc-a5fa-098cb450d1f1)
![image](https://github.com/nanocodesecurityEc/BackEnd/assets/168138135/79f28d90-50c3-488f-99e9-33d3b0be3589)
![image](https://github.com/nanocodesecurityEc/BackEnd/assets/168138135/56cbf47b-fd6c-4a67-a9f9-c08365214495)
![image](https://github.com/nanocodesecurityEc/BackEnd/assets/168138135/581d1fa7-aa48-48db-9cfe-6b8bb355e9a6)

