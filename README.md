# Spring Alumnos API

API REST desarrollada con Java 17 + Spring Boot 3 que gestiona alumnos y carreras.
Incluye operaciones CRUD completas y una relación ManyToOne entre Alumno y Carrera.

------------------------------------------------------------

🚀 Tecnologías utilizadas
- Java 17
- Spring Boot 3
- Spring Data JPA
- MySQL
- Maven

------------------------------------------------------------

🔧 Cómo ejecutar el proyecto

1. Clonar el repositorio
   git clone https://github.com/J05U307/spring-alumnos-api.git

2. Crear la base de datos
   CREATE DATABASE alumnos_api;

3. Configurar application.properties
   spring.application.name=spring-alumnos-api
   spring.datasource.url=jdbc:mysql://localhost:3306/alumnos_api
   spring.datasource.username=Tu_usuario
   spring.datasource.password=Tu_password
   spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
   spring.jpa.hibernate.ddl-auto=update
   spring.jpa.show-sql=true
   logging.level.org.hibernate.SQL=debug

4. Ejecutar el proyecto
   mvn spring-boot:run

------------------------------------------------------------

🧪 Colección Postman
Dentro de /postman encontrarás:
spring-alumnos-api.postman_collection.json
Importa ese archivo en Postman para probar todos los endpoints.

------------------------------------------------------------

📚 Endpoints principales

🟢 Alumnos – /alumnos
GET     /alumnos           -> Listar
POST    /alumnos           -> Crear
GET     /alumnos/{id}      -> Buscar por ID
PUT     /alumnos/{id}      -> Actualizar
DELETE  /alumnos/{id}      -> Eliminar

🔵 Carreras – /carreras
GET     /carreras          -> Listar
POST    /carreras          -> Crear
GET     /carreras/{id}     -> Buscar por ID
PUT     /carreras/{id}     -> Actualizar
DELETE  /carreras/{id}     -> Eliminar

------------------------------------------------------------

👨‍💻 Autor
Josue Cusquisiban
