# Trabajo Colaborativo

Este proyecto fue desarrollado como parte de una tarea de trabajo colaborativo. A continuación, se explican los pasos seguidos para realizar el proyecto, los conflictos enfrentados y cómo se resolvieron.

---

## **Pasos seguidos**

1. **Creación de ramas:**
   - Cada miembro del equipo creó una rama individual para trabajar en una funcionalidad específica.
   - Las ramas creadas fueron:
     - `rama-Felipe`
     - `rama-Josue`
     - `rama-Zenan`

2. **Edición y commits:**
   - Cada miembro realizó al menos dos cambios en su rama y registró los cambios con un mensaje claro utilizando `git commit`.

3. **Fusión de ramas (Merge):**
   - Se fusionaron las ramas individuales en la rama principal (`main`).
   - Durante el proceso, se enfrentó un conflicto en el archivo `texto.txt`.

---

## **Conflicto enfrentado**

### Descripción del conflicto
Al realizar un `merge` entre la rama principal (`main`) y el repositorio remoto, Git detectó un conflicto en el archivo `texto.txt`. Esto ocurrió porque el archivo tenía cambios diferentes en la versión local y la versión remota.

### Conflicto detectado
El archivo `texto.txt` mostró el siguiente conflicto:
```plaintext
<<<<<<< HEAD
Contenido local del archivo
=======
Contenido remoto del archivo
>>>>>>> FETCH_HEAD
