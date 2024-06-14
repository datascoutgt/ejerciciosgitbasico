# Hoja de Trabajo - Universidad Galileo

## Ejercicio en Parejas: Trabajo Avanzado con Ramas y Colaboración

### Objetivo
Este ejercicio está diseñado para practicar el trabajo avanzado con ramas en Git y la colaboración entre dos personas en un repositorio compartido en GitHub.

### Pasos a Seguir

#### 1. Crear el Repositorio en GitHub
1. **Persona A**: Crea un nuevo repositorio en GitHub llamado "ejercicio-colaborativo-nombre-carnet".
2. **Persona A**: Inicializa el repositorio con un archivo README.md.

#### 2. Clonar el Repositorio
1. **Persona A y Persona B**: Ambos clonan el repositorio en su máquina local:
   ```bash
   git clone https://github.com/tu_usuario/ejercicio-colaborativo-nombre-carnet.git
   cd ejercicio-colaborativo-nombre-carnet
   ```

#### 3. Trabajar en Ramas Separadas
1. **Persona A y Persona B**: Cada uno crea una nueva rama desde `main` con el nombre `feature/nueva-funcionalidad-nombre-carnet`:
   ```bash
   git checkout -b feature/nueva-funcionalidad-nombre-carnet
   ```
2. **Persona A y Persona B**: Realicen cambios significativos en el archivo README.md, agregando sus nombres y números de carnet.
3. **Persona A y Persona B**: Hagan commit de sus cambios en la rama `feature/nueva-funcionalidad-nombre-carnet`:
   ```bash
   git add README.md
   git commit -m "Agregar nombres y números de carnet"
   ```

#### 4. Fusionar las Ramas y Resolver Conflictos
1. **Persona A**: Cambie a la rama `main` y traiga los cambios de la rama de su compañero:
   ```bash
   git checkout main
   git pull origin main
   git merge feature/nueva-funcionalidad-nombre-carnet
   ```
2. **Persona A**: Si hay conflictos, resuélvalos y haga commit de los cambios.
3. **Persona B**: Repita los pasos de la Persona A para fusionar sus cambios en la rama `main`.

#### 5. Revisión y Publicación
1. **Persona A**: Revise los cambios en la rama `main` y asegúrese de que todo funcione correctamente.
2. **Persona A**: Publique los cambios en el repositorio remoto:
   ```bash
   git push origin main
   ```

#### 6. Eliminación de Ramas y Finalización
1. **Persona A y Persona B**: Eliminen las ramas locales después de que se hayan fusionado correctamente:
   ```bash
   git branch -d feature/nueva-funcionalidad-nombre-carnet
   ```

### Notas Adicionales
- Este ejercicio simula un flujo de trabajo realista en el que dos personas colaboran en un proyecto compartido utilizando ramas separadas para desarrollar nuevas funcionalidades.
- Cada estudiante debe asegurarse de entender cada paso y comunicarse eficazmente con su compañero durante el proceso de colaboración.
