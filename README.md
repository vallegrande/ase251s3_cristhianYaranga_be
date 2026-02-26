# ase251s3_cristhianYaranga_be
Creación del proyecto

Primero ingresé a la página oficial de Spring Initializr (https://start.spring.io
), donde configuré el proyecto con las siguientes especificaciones:

Proyecto: Maven

Lenguaje: Java

Versión de Spring Boot: versión estable

Packaging: Jar

Dependencia agregada: Spring Web

Luego hice clic en Generate para descargar el proyecto en formato ZIP.

Descompresión y apertura en IntelIdea

Después de descargar el archivo:

Descomprimí la carpeta del proyecto.

Abrí mi Intel.

Seleccioné “Open Folder”.

Busqué la carpeta del proyecto y la abrí.

El entorno reconoció automáticamente que era un proyecto Maven.

Creación del controlador (Hola Mundo)

Dentro del paquete principal creé una nueva clase llamada:

CristhianYaranga.java

En esta clase agregué el código para mostrar el mensaje "Hola Mundo" en el navegador utilizando:

La anotación @RestController

La anotación @GetMapping

Con esto se creó la ruta:

http://localhost:8080/hello

