# Hoja de Trabajo - Universidad Galileo
 - Se harán grupos de tres al azar donde deberán trabajar para resolver los ejercicios del día
 - Una vez finalizados los ejercicios, deberán cada quien por su lado a través de un video evidenciar todo lo que hicieron en el grupo
 - Si no tiene grupo, pues hacer los ejercicios de forma solitaria creando otra cuenta, simulando un compañero o busque a alguien mas con quien trabajar.


## Ejercicio 1: Trabajo con ramas

1. **Crear un repositorio en GitHub:**
   - Cada estudiante crea un nuevo repositorio en GitHub llamado "ejercicio-ramas-nombre-carnet".
   - Inicializa el repositorio con un archivo README.md.

2. **Clonar el repositorio:**
   - Cada estudiante clona el repositorio recién creado en su máquina local:
     ```bash
     git clone https://github.com/tu_usuario/ejercicio-ramas-nombre-carnet.git
     cd ejercicio-ramas-nombre-carnet
     ```

3. **Crear y trabajar en una nueva rama:**
   - Cada estudiante crea una nueva rama llamada `feature/nueva-funcionalidad-nombre-carnet` desde la rama `main`:
     ```bash
     git checkout -b feature/nueva-funcionalidad-nombre-carnet
     ```
   - Realiza algunos cambios en el archivo README.md agregando tu nombre y número de carnet.
   - Haz commit de tus cambios en la nueva rama:
     ```bash
     git add README.md
     git commit -m "Agregar nombre y número de carnet"
     ```

4. **Fusionar la rama:**
   - Cambia de nuevo a la rama `main`:
     ```bash
     git checkout main
     ```
   - Fusiona la rama `feature/nueva-funcionalidad-nombre-carnet` en la rama `main`:
     ```bash
     git merge feature/nueva-funcionalidad-nombre-carnet
     ```

5. **Eliminar la rama:**
   - Cada estudiante elimina su rama `feature/nueva-funcionalidad-nombre-carnet`:
     ```bash
     git branch -d feature/nueva-funcionalidad-nombre-carnet
     ```

## Ejercicio 2: Trabajo con repositorios remotos

1. **Clonar un repositorio existente:**
   - Cada estudiante clona el repositorio "ejercicio-ramas-nombre-carnet" en su máquina local si no lo ha hecho ya.

2. **Agregar cambios y hacer push:**
   - Cada estudiante realiza algunos cambios en el archivo README.md, agregando su nombre y número de carnet.
   - Cada estudiante sube estos cambios al repositorio remoto:
     ```bash
     git push origin main
     ```

3. **Colaboración con compañeros:**
   - Cada estudiante invita a un compañero de clase a colaborar en el repositorio "ejercicio-ramas-nombre-carnet" en GitHub, dándole permisos de escritura.
   - Tu compañero puede realizar cambios en un archivo y hacer push a la rama remota.

## Ejercicio 3: Gestión de cambios

1. **Revertir cambios:**
   - Cada estudiante realiza un cambio en el archivo README.md y hace commit.
   - Cada estudiante utiliza `git revert` para revertir ese cambio y hace otro commit.

2. **Explorar el historial:**
   - Cada estudiante utiliza `git log` para explorar el historial de commits en su repositorio.
   - Encuentra un commit anterior y cámbiate a él utilizando `git checkout`.

3. **Deshacer cambios no confirmados:**
   - Cada estudiante realiza un cambio en el archivo README.md pero no hace commit.
   - Cada estudiante utiliza `git checkout -- README.md` para deshacer ese cambio.