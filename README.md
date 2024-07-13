# Proyecto Desafio Alura de Literatura

## Introducción

El proyecto Literatura es una plataforma diseñada con Spring Boot que facilita la gestión de datos relacionados con autores y libros. Utilizando una base de datos PostgreSQL, la aplicación almacena de manera segura la información y proporciona a los usuarios una interfaz intuitiva para navegar y realizar consultas sobre autores y libros. La aplicación cuenta con funcionalidades avanzadas para la búsqueda, filtrado y visualización de datos, lo que la convierte en una herramienta indispensable para profesionales del mundo literario y aficionados a la lectura.

## Funcionalidades

1. Gestión de autores: crear, leer, actualizar y eliminar autores.
2. Gestión de libros: crear, leer, actualizar y eliminar libros.
3. Búsqueda de libros por título o autor.
4. Obtención de la lista de idiomas disponibles.
5. Obtención de la lista de libros por idioma.

## Tecnologías utilizadas

- **Spring Boot**: framework para desarrollar aplicaciones web.
- **PostgreSQL**: base de datos relacional.
- **Hibernate**: ORM (Object-Relational Mapping) para interactuar con la base de datos.
- **Jackson**: biblioteca para serializar y deserializar objetos en formato JSON.
- **Java**: lenguaje de programación utilizado.

## Configuración

La aplicación utiliza variables de entorno para configurar la conexión a la base de datos. Los valores de las variables de entorno se establecen en el archivo `application.properties`.

