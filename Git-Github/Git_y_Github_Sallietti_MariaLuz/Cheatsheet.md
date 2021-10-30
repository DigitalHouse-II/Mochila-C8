# Cheatsheet

## Crear

**git init**
Crear un repositorio local / inicializar

## Configurar

**git config user.name nombre_usuario**
**git config user.email email**

Configurar nombre de usuario e email

## Añadir archivos 
### Todos los archivos

**git add .** 

### Solo un archivo archivo

**git add nombre_archivo**

Sumar archivos untracked al staging

## Comitear archivos

**git commit -m "mensaje"**

Realizar un commit de los archivos en staging. Crea una marca temporal, con mensaje, nombre de usuario, email, fecha y hora.

## Pushear archivos a Rama

**git push origin nombre_rama**

Sube los archivos ya comiteados a la rama que se indique

## Obtener información

**git status**

Brinda información sobre el estado de los archivos dentro del repositorio

**git log**
**git log --oneline**

Brinda información sobre cada commit realizado. Con --oneline obtenemos la misma información pero en versión resumida

## Revisar commits

**git checkout codigo_commit**

Permite volver al commit que me interesa revisar

## Deshacer commits

**git reset HEAD~cantidad_commits**

Elimina la cantidad de commits que le indique, contando desde el último hacia el primero

## Añadir repositorio remoto

**git remote add origin url_repositorio**

Vincular el repositorio local con un repositorio creado en remoto (por ej. en Github)

## Controlar vinculación con repositorio remoto

**git remote -v**

Informa con qué repositorio remoto está vinculado mi repositorio local

## Clonar repositorio remoto

**git clone url_repositorio_remoto**

Clono todo un repositorio remoto en local. No hace falta inicializarlo en local y ya está vinculado.

## Actualizar archivos en local

**git pull origin nombre_rama**

Actualiza en mi repositorio local los archivos que hayan cambiado o agrega los que sean nuevos en el repositorio remoto.

## Subir archivos de local a remoto

**git push origin nombre_rama**

Subir los archivos que estén en staging local al repositorio remoto vinculado, indicando la rama

## Conocer Rama

**git branch**

Informa las ramas creadas en el repositorio

## Crear Rama

**git branch nombre_rama**

Crear una nueva rama y asignarle un nombre

## Cambiar de Rama

**git checkout nombre_rama**

Permite moverse entre ramas disponibles

## Eliminar Rama

**git branch -d nombre_rama**

Elimina la rama identificada con ese nombre

**git branch -D nombre_rama**

Fuerza la eliminación de la rama, inclusive si tiene cambios sin fusionar









