git init - Crea un nuevo repositorio en la carpeta actual
git clone <url> - Copia un repositorio remoto
git status - Estado actual del repositorio
git add archivo - Agregas a la staging area el archivo (con . añades todos)
git commit -m "mensaje" - Guardas los cambios con un comentario
git log - Historial de commits
git diff - Muestra los cambios realizados antes de hacer un commit
git reset --soft HEAD~1 - Vuelves al stage indicado, y mandas el previo a staging area
git reset --hard HEAD~1 - Vuelves al  stage indicando borrando el commit previo
git revert HEAD - Deshace el último cambio (si pones HEAD~numero, deshaces el commit en concreto)
git stash - Guarda cambios de manera temporal
git checkout - Moverte entre commits
git show - Inspeccionar el contenido de un commit sin cambiar a él

git branch - Lista de las ramas
git branch nombre - Creación de rama
git switch rama - Cambiar a la rama nombrada
git restore - Descartar cambios

git config --global alias.tree "log --graph --decorate --all --oneline"