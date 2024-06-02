# Screen Match - Aplicación de Biblioteca de Películas

## Descripción

Screen Match es una aplicación web que permite a los usuarios buscar y consultar información sobre películas utilizando la API de OMDB (Open Movie Database). Esta aplicación fue desarrollada como parte de un curso full stack, abarcando tanto el frontend como el backend.

## Tecnologías Utilizadas

### Frontend
- HTML
- CSS
- JavaScript

### Backend
- Java
- Spring Boot
- Maven

### Base de Datos
- JPQL (Java Persistence Query Language)

### Otros
- API de OMDB: [OMDB API](https://www.omdbapi.com/)

## Estructura del Proyecto

### Modelo-Vista-Controlador (MVC)
La aplicación sigue el patrón de diseño MVC, separando la lógica de negocio, la presentación y el control de flujo en componentes distintos.

### DTO (Data Transfer Object)
Utilizamos DTOs para transferir datos entre las capas de la aplicación, asegurando una separación clara de responsabilidades.

## Características

- **Búsqueda de Películas**: Los usuarios pueden buscar películas por título utilizando la API de OMDB.
- **Detalles de Películas**: Los usuarios pueden ver detalles específicos de una película seleccionada.
- **Interfaz Amigable**: La interfaz de usuario es intuitiva y fácil de navegar.
- **Backend Robusto**: El backend en Java maneja las solicitudes y respuestas, interactuando con la API de OMDB y la base de datos.

## Configuración y Ejecución

### Prerrequisitos
- JDK 11 o superior
- Maven
- Un navegador web

### Instalación

1. **Clonar el repositorio**:
   ```sh
   git clone https://github.com/tu-usuario/screen-match.git
   cd screen-match
Configurar la API de OMDB:

Regístrate en OMDB API para obtener una clave API.
Configura la clave API en tu aplicación. Puedes hacerlo añadiendo una entrada en tu application.properties:
properties
Copiar código
omdb.api.key=YOUR_API_KEY
Construir el proyecto:

sh
Copiar código
mvn clean install
Ejecutar la aplicación:

sh
Copiar código
mvn spring-boot:run
Acceder a la aplicación:

Abre tu navegador y navega a http://localhost:8080.
Notas del Desarrollo
Durante el desarrollo de esta aplicación, se han utilizado varios conceptos avanzados y patrones de diseño:

Streams y Lambdas: Se han utilizado ampliamente para la manipulación y transformación de datos.
Consultas Entregadas (Delivered Queries): Utilizadas para pruebas y nuevas funcionalidades.
Patrones de Diseño: Como MVC y DTO para mantener un código limpio y estructurado.
Conexión Frontend-Backend: Se proporcionó una experiencia completa para entender cómo se conectan ambas partes de una aplicación.
Contribuciones
Las contribuciones son bienvenidas. Si deseas contribuir, por favor, sigue estos pasos:

Haz un fork del repositorio.
Crea una nueva rama (git checkout -b feature/nueva-caracteristica).
Realiza tus cambios y haz commit (git commit -am 'Añadir nueva característica').
Envía tus cambios al repositorio (git push origin feature/nueva-caracteristica).
Abre un Pull Request.
Licencia
Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.

Agradecimientos
Gracias a todos los que participaron en este curso y contribuyeron a este proyecto. Espero que esta experiencia full stack haya sido enriquecedora y que sigas explorando y aprendiendo más sobre el desarrollo web.

Nota: La aplicación no incluye HTML y CSS propios ya que estos fueron proporcionados previamente. Sin embargo, se recomienda revisar y entender cómo funciona el frontend para obtener una comprensión completa del proyecto.
