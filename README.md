# README - Menú de Búsqueda de Libros y Autores

Este proyecto presenta una clase `Menu` que ofrece un menú interactivo para consultar y listar libros y autores a partir de una API externa. El menú permite realizar varias acciones, como buscar libros por título, consultar autores por nombre, listar libros registrados, y más. A continuación, se describe el funcionamiento y las características principales de este código.

## Descripción

La clase `Menu` es responsable de gestionar la interacción con el usuario mediante un menú de opciones. A través de este menú, el usuario puede acceder a varias funciones relacionadas con la consulta de libros y autores, que se obtienen de una API externa. Esta clase utiliza otras clases auxiliares para manejar las solicitudes a la API y convertir los datos obtenidos en un formato legible.

### Funciones principales

1. **Buscar Libro por Título**  
   Permite al usuario buscar un libro por su título, enviando la solicitud a la API y mostrando los resultados obtenidos.

2. **Buscar Autor por Nombre**  
   El usuario puede ingresar el nombre de un autor y obtener una lista de libros relacionados con dicho autor.

3. **Listar Libros Registrados**  
   Muestra una lista de todos los libros registrados hasta el momento.

4. **Listar Autores Registrados**  
   Muestra una lista de todos los autores registrados.

5. **Listar Autores por un Año Determinado**  
   Permite consultar y mostrar autores que están registrados en un determinado año.

6. **Listar Libros por Idioma**  
   Permite buscar libros filtrados por el idioma en el que están escritos.

7. **Salir**  
   Sale del programa, terminando la ejecución.

## Estructura del Código

La clase `Menu` contiene los siguientes componentes:

- **Scanner teclado**: Utilizado para la entrada de datos por parte del usuario.
- **ConsumoAPI consumoApi**: Interactúa con la API externa para obtener los datos de libros y autores.
- **String URL_BASE**: Contiene la URL base de la API externa utilizada para las búsquedas.
- **ConvierteDatos conversor**: Se encarga de convertir los datos obtenidos desde la API a un formato que sea fácil de mostrar al usuario.

## Funcionamiento

El menú se ejecuta dentro de un bucle `while` que se repite hasta que el usuario selecciona la opción de salir (`0`). El programa presenta una serie de opciones, y según la opción elegida, se ejecuta una función específica (por ejemplo, buscar libros por título, listar autores, etc.).

El flujo es el siguiente:
1. El menú se muestra al usuario con las opciones disponibles.
2. El usuario ingresa su opción a través del teclado.
3. Dependiendo de la opción seleccionada, se ejecuta la función correspondiente.
4. Si el usuario elige una opción no válida, se le informa y se vuelve a mostrar el menú.
5. El programa continuará ejecutándose hasta que el usuario decida salir (opción `0`).

## Requisitos

- **Java 8+**: Asegúrate de tener una versión compatible de Java instalada en tu sistema.
- **Conexión a Internet**: Necesaria para realizar las solicitudes a la API externa.

## Uso

1. Ejecuta la clase `Menu` para iniciar el programa.
2. Aparecerá un menú interactivo en la consola donde podrás seleccionar la opción deseada.
3. Ingresa el número de la opción que deseas ejecutar.
4. El programa responderá según la opción seleccionada. 

## Ejemplo de ejecución

![Captura de pantalla 2025-01-21 202813](https://github.com/user-attachments/assets/da5b9fb5-0216-4c4a-a3be-14b138143601)

![Captura de pantalla 2025-01-21 202841](https://github.com/user-attachments/assets/e6f18331-21eb-48ad-b712-f6b4c87d0624)


