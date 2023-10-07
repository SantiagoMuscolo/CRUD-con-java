# API de Usuarios con Java, Spring Boot y SQL

Este proyecto es una API que proporciona operaciones CRUD (Crear, Leer, Actualizar, Eliminar) para gestionar usuarios. Utiliza Java, Spring Boot y SQL para la persistencia de datos.

## Endpoints

### Obtener todos los usuarios

- **URL:** `/user`
- **Método HTTP:** GET
- **Descripción:** Retorna una lista de todos los usuarios registrados en el sistema.

### Obtener un usuario por ID

- **URL:** `/user/{id}`
- **Método HTTP:** GET
- **Parámetros de URL:** `id` (ID del usuario)
- **Descripción:** Retorna los detalles de un usuario específico según su ID.

### Crear un nuevo usuario

- **URL:** `/user`
- **Método HTTP:** POST
- **Cuerpo de la solicitud (JSON):**
  ```json
  {
    "firstName": "Nombre",
    "lastName": "Apellido",
    "email": "correo@example.com"
  }
