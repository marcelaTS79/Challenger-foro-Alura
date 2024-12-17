# API REST - Foro Alura

Esta es una API REST desarrollada con **Spring Boot**, que gestiona un foro de discusión, permitiendo operaciones CRUD en temas y usuarios.
![Foro Alura](imagenes/images.png)

## Características Principales
- Creación, lectura, actualización y eliminación (CRUD) de temas.
- Gestión de usuarios en el foro.
- Persistencia de datos con MySQL.
- Validación de datos de entrada.
- Desarrollo siguiendo buenas prácticas y arquitectura REST.

## Tecnologías Utilizadas
- **Java 17**
- **Spring Boot 3.0.6**
- **Maven**
- **MySQL**
- **Lombok**
- **Postman** (para pruebas)

## Instalación y Configuración

### Prerrequisitos
Asegúrate de tener instalado:
- [Java 17](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)
- [Maven](https://maven.apache.org/)
- [MySQL](https://dev.mysql.com/downloads/)

### Clona el Proyecto
Clona este repositorio en tu máquina local:
```bash
git clone https://github.com/tu-usuario/foro-alura.git

### Crea una base de datos
CREATE DATABASE foro_alura;

### Configura el archivo application.properties
spring.datasource.url=jdbc:mysql://localhost:3306/foro_alura
spring.datasource.username=tu_usuario
spring.datasource.password=tu_contraseña
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

### Ejecutar la aplicación
mvn spring-boot:run

## Licencia
Este proyecto está licenciado bajo la licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más información.
Copyright (c) 2024 Lina Marcela Tangarife Sánchez
