# Guía rápida de mensajes de commit de Git (solo 3 tipos)
## Comentarios 
Al momento de hacer commit se debería considerar lo siguiente:

### Tipos
- **feat** (característica): Añade una nueva funcionalidad. Ej: `feat:implementa el inicio de sesión con redes sociales`
- **fix** (corrección): Arregla un error. Ej: `fix:elimina el error de carga de imágenes`
- **chore** (tarea): Cambios internos o de mantenimiento. `Ej: chore:actualiza las dependencias`

### Importancia
- Mensajes claros y concisos que facilitan la comprensión del historial de desarrollo.
- Los tipos ayudan a filtrar y buscar commits específicos.
- Mensajes concretos permiten revertir cambios fácilmente si es necesario.

### Consejos
- Menos de 50 caracteres en el resumen.
- Usar el imperativo (ej: "Implementa" en lugar de "Implementado").
- Ser específico sobre el cambio realizado.

### Ejemplo
- feat:habilita el modo oscuro opcional
- fix:corrige el fallo al guardar archivos
- chore:reorganiza la estructura de carpetas

### Opcionales

- Comentarios en inglés, así se evita el uso de acentos y caracteres especiales.
- Se puede agregar la app o componente al que pertenezca el cambio.

  Por ejemplo: `[chore](my_app):refactor of utility functions`

## Pull Requests (PR)

La idea es facilitar la creación de PR para los desarrolladores, para ello, podemos enumerar las siguientes razones en la descripción:
- **Estandarización y consistencia**: Garantizan que toda la información necesaria se incluya de manera uniforme, facilitando la revisión y comprensión de los cambios propuestos.
- **Guía y claridad**: Ofrecen un esquema predefinido para que los colaboradores sepan exactamente qué información deben proporcionar, mejorando la calidad de la comunicación.
- **Ahorro de tiempo**: Evitan la necesidad de escribir los mismos detalles repetidamente, lo que agiliza el proceso de creación y revisión de pull requests.
- **Uso de media files**: Agregar imágenes en caso de un bug visual para que sea más rápida la revisión, en algunos casos se pueden agregar gifs también.
- Agregar labels, reviewers y assigned to en la descripción.
- No hacer PR de más de 400 líneas ya que se hace difícil de revisar.
