Describe que hacen los siguientes comandos de git, escribe su descripcion al frente en una sola linea.

git status: Este comando se usa para obtener el estado actual del repositorio

git clone: Se utiliza para clonar un repositorio de github y así trabajar el versionamiento en la maquina local. - git clone <url del repositorio>

git pull: Descarga los cambios de la rama que solo estén en el repositorio de github y no en la máquina local, en otras palabras actualiza la rama local. - git pull

git checkout: Se utiliza para crear ramas nuevas a partir de una existente, o para reiniciar cambios no guardados en la rama actual. - git checkout -b <nombre nueva rama> - git checkout (reinicia la rama actual)

git log: Se utiliza para ver el historial de logs del repositorio y validar el orden en el cual se han ido actualizando las versiones. - git log origin..HEAD

git branch: Se utiliza para poder crear ramas nuevas en base a la master o en base a otras ramas ya existentes de forma local. - git branch <nombre rama> (crea la rama en base a la master), git branch <rama nueva> <rama original> (crea la rama nueva en base a otra rama ya existe)

git add: Se utiliza para añadir los archivos que se guardaran en el siguiente commit. -  git add . (guarda todos los archivos cambiados), git add "nombre archivo" (guarda solo el nombre del archivo indicado)

git commit: Se utiliza para poder indicar el comentario sobre los cambios que se enviaran en el siguiente push. - git commit -m "titulo mensaje" -m "descripcion del cambio de versionamiento"

git push: Se utiliza para cargar los cambios de la rama actual local hacia el repositorio remoto de git. - git push -u origin <nombre rama>

git merge: Se utiliza para unir o fucionar 2 ramas. - git merge <nombre rama a la que se quiere integrar cambios de la rama actual> 
