# Librería de Gestión de Archivos

Esta librería proporciona una interfaz para el manejo de archivos, incluyendo operaciones como creación, renombramiento, copia, movimiento, lectura, escritura y eliminación de archivos.

## Uso

1. Descarga el JAR de la librería.

2. Crea una instancia de la clase `GestorArchivos` en tu aplicación:

```java
GestorArchivos gestor = new GestorArchivos();
```
4. **Llamar a los métodos**:

   - Utiliza los métodos públicos de la clase `GestorArchivos` para realizar operaciones de manejo de archivos, como crear, renombrar, copiar, mover, leer, escribir y eliminar archivos.

     Ejemplos:

     - Para crear un archivo:

       ```java
       gestor.crearArchivo();
       ```

     - Para renombrar un archivo:

       ```java
       gestor.renombrarArchivo();
       ```

     - Para copiar un archivo:

       ```java
       gestor.copiarArchivo("destino/nuevo_archivo.txt");
       ```

     - Para mover un archivo:

       ```java
       gestor.moverArchivo("destino/nuevo_ubicacion/nuevo_archivo.txt");
       ```

     - Para leer un archivo:

       ```java
       String contenido = gestor.leerArchivo();
       ```

     - Para escribir en un archivo:

       ```java
       gestor.escribirEnArchivo();
       ```

     - Para eliminar un archivo:

       ```java
       gestor.eliminarArchivo();
       ```
5. **Utilizar el método `herramientas()`**:

   - Además, puedes utilizar el método `herramientas()` para acceder a un menú interactivo que permite al usuario seleccionar y realizar diferentes operaciones de manejo de archivos:

     ```java
     gestor.herramientas();
     ```

Asegúrate de que tu proyecto esté configurado para utilizar el JAR de la librería y que todas las dependencias se gestionen adecuadamente.
