# Task Manager - Java Spring Boot

Aplicación básica de gestión de tareas desarrollada con Java y Spring Boot.
Expone una API REST para realizar operaciones CRUD sobre tareas.

## Tecnologías

- Java 17
- Spring Boot
- Spring Data JPA
- Hibernate
- Base de datos H2 (en memoria)
- Maven

## Funcionalidades

- Crear tareas
- Listar tareas
- Obtener una tarea por ID
- Actualizar tareas
- Eliminar tareas

## Ejemplos de Endpoints 
- GET/tasks
- Obtiene todas las tareas
- GET/tasks/{id}
- Obtiene una tarea por ID
- POST/tasks

  Content-Type:Application/json

   {

  "title": "Tarea actualizada",

   "completed": true
  
   }

  DELETE/tasks/{id} 

## Ejecución del proyecto

1. Clonar el repositorio

git clone https://github.com/eric-martinez-dev/task-manager-java.git
cd task-manager-java

2. Ejecutar la aplicación

mvn spring-boot:run

O ejecutar la clase principal desde el IDE.

## Acceso

API REST:
http://localhost:8080/tasks

Consola H2:
http://localhost:8080/h2-console

JDBC URL:
jdbc:h2:mem:testdb

Usuario:
sa
Password:
(vacío)

## Estructura del proyecto

src/main/java  
└── com/example/demo  
    ├── controller  
    ├── model  
    ├── repository  
    └── TaskManager2Application.java  
## Autor
Eric Martínez  
Estudiante de Ingeniería  
GitHub: eric-martinez-dev
