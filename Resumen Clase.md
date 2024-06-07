**Git: Resumen de Comandos y Conceptos Básicos**

Recuerda presionar Ctrl + Shift ´V o Cmd + Shift + V si quieres ver esto en vista previa integrada

1. **Instalación y Configuración:**
   - Verificar la instalación de Git: 
     ```sh
     git --version
     ```
   - Configurar nombre de usuario global:
     ```sh
     git config --global user.name "Tu Nombre"
     ```
   - Configurar email global:
     ```sh
     git config --global user.email "tu@email.com"
     ```

2. **Ayuda y Documentación:**
   - Obtener ayuda sobre un comando específico:
     ```sh
     git help <comando>
     ```
   - Salir de la página de ayuda: Pulsar `q`

3. **Configuración Avanzada:**
   - Ver y editar la configuración global:
     ```sh
     git config --global -e
     ```
   - Escribir cambios y salir del editor: `:wq!`

4. **Control de Versiones:**
   - Verificar el estado del repositorio:
     ```sh
     git status
     ```
   - Agregar cambios al área de stage:
     ```sh
     git add <archivo>
     ```
   - Realizar un commit con un mensaje:
     ```sh
     git commit -m "Mensaje del commit"
     ```

5. **Gestión de Archivos:**
   - Moverse entre directorios:
     ```sh
     cd <ruta>
     ```
   - Crear un directorio:
     ```sh
     mkdir <nombre_del_directorio>
     ```
   - Abrir el editor de código (Visual Studio Code):
     ```sh
     code .
     ```

6. **Manipulación de Archivos:**
   - Eliminar un archivo:
     ```sh
     rm <nombre_del_archivo>
     ```
   - Eliminar un archivo con Git:
     ```sh
     git rm <nombre_del_archivo>
     ```
   - Cambiar el nombre de un archivo:
     ```sh
     mv <nombre_actual> <nuevo_nombre>
     ```

7. **Ignorar Archivos:**
   - Crear un archivo .gitignore:
     ```sh
     touch .gitignore
     ```
   - Ignorar archivos por extensión:
     ```sh
     *.ext
     ```
   - Ignorar un directorio y su contenido:
     ```sh
     <nombre_del_directorio>/
     ```

8. **Conceptos Clave:**
   - `git add`: Agrega cambios al área de stage.
   - `git commit`: Guarda los cambios en el repositorio.
   - `git status`: Muestra el estado actual del repositorio.
   - `git rm`: Elimina archivos del repositorio.
   - `git mv`: Mueve o renombra archivos en el repositorio.

9. ** Aprendiendo sobre git diff **

1. Agregue diferentes lineas de texto en un archivo de texto que quiera

9. ** Aprendiendo sobre git log **

Monitoree todos los cambios 