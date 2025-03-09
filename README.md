# CRUD Web App (Java + MVC)
<img src="https://github.com/user-attachments/assets/d330cc3e-da1e-48eb-9e17-4498d7bfd581" width="500">


- Implementación de un CRUD completo (Crear, Leer, Actualizar, Eliminar) usando **Java Web**, **Jakarta EE**, **Servlets**, **JSP**, **JSTL** y el patrón **MVC**, conectado a una base de datos **MySQL**.

## Tecnologías
- Java 17
- Jakarta EE 9
- Servlets 5.0
- JSP + JSTL
- MySQL 8.0
- Tomcat 10.0
- Maven

## Instalación
1. Clona el repositorio: `git clone https://github.com/[tu-usuario]/crud-web-app.git`
2. Crea la base de datos: `CREATE DATABASE crud_db;` y ejecuta `src/main/resources/database.sql`
3. Configura `src/main/resources/db.properties` con tus credenciales MySQL.
4. Construye: `mvn clean install`
5. Despliega el `.war` en Tomcat y accede a `http://localhost:8080/crud-web-app/`

## Estructura
- `controller/`: Servlets para manejar peticiones.
- `model/`: Lógica de negocio y acceso a datos.
- `views/`: JSP para la presentación.
- `resources/`: Configuración y scripts SQL.

![image](https://github.com/user-attachments/assets/2ae10554-0250-4dc2-a85b-0a3a796d6aca)

## Uso
- **Crear**: Añade registros desde el formulario.
- **Leer**: Lista registros en la página principal.
- **Actualizar**: Edita registros existentes.
- **Eliminar**: Borra registros seleccionados.

## Licencia
MIT
