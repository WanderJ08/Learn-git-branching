<center> <h1>ANALISIS DE SISTEMAS</h1> </center> 
<center> <h3>Wander Jerez 2021-0990</h3> </center>

<center> <h3>Secuencia introductoria</h3> </center>

- Git commit: Confirmar una instantánea del directorio del entorno de ensayo en el historial de confirmaciones de los repositorios.

- Git Branch: Es una especie de herramienta de gestión de ramas. Puede listar las ramas que tienes, crear una nueva rama, eliminar ramas y cambiar el nombre de las ramas

- git checkout: Se usa para cambiar de rama y revisar el contenido de tu directorio de trabajo.

- git merge: Se utiliza para fusionar uno o más ramas dentro de la rama que tienes activa.

- git rebase: Te permite cambiar fácilmente una serie de confirmaciones, modificando el historial de tu repositorio. Puedes reordenar, editar o combinar confirmaciones.

<center> <h3>Acelerando</h3> </center>

- Head: El head indica donde estas

- Moverse un commit hacia atrás con ^: Con un git checkout head^ te dirige un padre o commit hacia atrás desde el head (La posición en la que te encuentras).

- Moverse una cantidad de commits hacia atrás con ~<4>: un git checkout HEAD~4 te mueve 4 padres o commits hacia atrás desde el Head.

- Puedes reasignar directamente una rama a un commit usando la opción -f:  git branch -f main HEAD~3 mueve (forzadamente) la rama main tres padres por detrás de HEAD.

- git reset: Git reset deshace los cambios moviendo la referencia de una rama hacia atrás en el tiempo a un commit anterior. git reset va a mover la rama hacia atrás, como si el commit nunca se hubiera hecho. Ejemplo de sintaxis Git reset HEAD~1.

- git revert: Sirve para deshacer cambios efectuados en el historial de confirmaciones de un repositorio.

<center> <h3>Moviendo el trabajo por ahí</h3> </center>

- git cherry-pick: git cherry-pick Commit1 Commit2 , es una manera bastante directa de decir que quieres copiar una serie de commits sobre tu ubicación actual (HEAD).

- Rebase -i: git rebase -i HEAD~4, hace un rebase desde 4 padres detrás de head y te permite seleccionar a cuáles padres hacerle el rebase.

<center> <h3>Un poco de todo</h3> </center>

- Git command—amend: El comando git commit --amend es una manera práctica de modificar el commit más reciente. Te permite combinar los cambios preparados con el commit anterior en lugar de crear un commit nuevo. También puede usarse para editar el anterior mensaje del commit sin cambiar la instantánea.

- Git tag: Git describe La salida de ese comando se ve así: tag_numCommits_g_hash, donde tag es el tag más cercano en la historia, numCommits dice a cuántos commits de ese tag estás, y hash es el hash del commit que estás describiendo.

<center> <h3>Push y Pull -- Git Remotes!</h3> </center>

- git clone: Git clone se utiliza principalmente para apuntar a un repositorio existente y clonar o copiar dicho repositorio en un nuevo directorio, en otra ubicación.

- git fetch: Descarga commits, archivos y referencias de un repositorio remoto a tu repositorio local.

- git pull: El comando git pull es básicamente una combinación de los comandos git fetch y git merge, donde Git descargará desde el repositorio remoto especificado y a continuación, de forma inmediata intentará combinarlo en la rama en la que te encuentres.

- git fakeTeamwork: El comportamiento por default de fakeTeamwork es simplemente crear un commit en main.

- git push: El comando git push se usa para cargar contenido del repositorio local a un repositorio remoto. El envío es la forma de transferir confirmaciones desde tu repositorio local a un repositorio remoto.

- git pull –rebase: Es un atajo para hacer fetch y rebase!

- Pull Request: Básicamente un pull request es una petición para integrar nuestras propuestas o cambios de código a un proyecto. 

![foto1](/imagenes/imagen1.png)
![foto1](/imagenes/imagen2.png)

