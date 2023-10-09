## Rutas de la API

A continuación se enumeran las rutas de la API con sus métodos HTTP correspondientes y ejemplos de entrada:

1. Crear una tarea
   Método: POST
   Ruta: /api/tasks
   Input: JSON con la información de la tarea (title, description y completed)

```
{
   "title": "Ejemplo de título",
   "description": "Ejemplo de descripción",
   "completed": false
}
```

2. Obtener una tarea por ID
   Método: GET
   Ruta: /api/tasks/{taskId}
   Input: taskId en la ruta (reemplazar {taskId} con el ID de la tarea que deseas obtener)

3. Obtener todas las tareas
   Método: GET
   Ruta: /api/tasks

4. Actualizar una tarea
   Método: PUT
   Ruta: /api/tasks/{taskId}

```
   {
   "title": "Nuevo título",
   "description": "Nueva descripción",
   "completed": true
   }
```

5. Eliminar una tarea por ID
   Método: DELETE
   Ruta: /api/tasks/{taskId}

6. Obtener información adicional de una tarea
   Método: GET
   Ruta: /api/tasks/{taskId}/additional-info