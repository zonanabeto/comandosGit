# Curso Git

## **Comandos Importantes**

* __git init__ - Inicializar Repo
* __git add -A o .__ - Poner en el stage
* __git status__ - Ver el estatus del repo
* __git log__ - Ver la historia del repo segun los commits
* __git commit -m "lalala"__ - Generar un guardado con un mensaje de nombre
* __git lg__ - Creado por mi para ser un resumen del git log
* __git config --global -e__ - Ver la configuracion de algunos alias o email o nombre
* __git config --global alias."nombre del alias" "nombre de las funciones que haces"__ - Crear un alias y que hace ese alias
* __git commit -am "Bla bla bla"__ - Es la mescla de un git add -A y commit
* __git commit --amend -m "Bla bla bla"__ - Modifica el mensaje del ultimo commit
* __git reset  --soft HEAD^__ - Borra el ultimo commit sin borrar los cambios, se usa HEAD para dirigirse al ultimo commit
* __git reset  --mixed XXXComitXXX__ - Regresa hasta el commit indicado pero no borra los que estaban despues de este
* __git reset  --hard XXXComitXXX__ - Elimina todos los commits hasta el indicado
* __git reflog__ - Todos los logs de git
    * Con otro git reset --hard se puede regresar a como estaba aunque se haya reseteado
* __git mv *NombreActual* *NuevoNombre*__ - Cambio d nombre
* __git rm *NombreArchivo*__ - Eliminar archivo desde git
* __git branch *nombreRama*__ - Crear rama con nombre
* __git checkout *nombreRama*__ - Mover a la rama
* __git diff *Rama1 y rama2*__ - Diferencia entre ramas 
* __git merge *nombre de la rama*__ - desde el branch que al que se le desea unir 
* __git branch -d *nombreRama*__ - Borra el nombre de la rama mencionada
* __git checkout -b  *NombreRama*__ - Crea una rama y te mueve a ella
* __git tag *NombreTag*__ - Crea tag
* __git tag__ - Ver los tags
* __git tag -d *nombreTag*__ - Elimina el Tag
* __git tag -a *Version 0.0.1* -m *mensaje*__ - Ver los tags
* __git tag -a *Version* *numeroCommit* -m *"Mensaje"*__ - Crea un tag en un commit deseado
* __git show *nombreTag*__ - Muestra la info del tag
* __git stash__ - Genera un stash hasta donde no se hizo commit
* __git stash list__ - Muestra la lista de stash
* __git stash pop__ - Merge de stash
* __git stash drop__ - Elimina el ultimo stash
* __git stash apply__ - Aplica el ultimo stash
* __git stash apply@{*numbero de stash*}__ - Aplica el ultimo stash
* __git stash clear__ - Borra todos los stashes
* __git rebase *branch que se desea actualizar*__ - Desde la branch en la que se trabaja 
* __git rebase -i HEAD~*numero de commitprevio a head*__ - Da opcion para hacer cosas en los commits
* __git remote -v__ - Versiones en remote
* __git push tags__ - Subir los tags a github
* __git clone *link del repo*__ - Clone el repositorio de github
* __git fetch__ - Es como un git pull pero no hace el merge automaticamente sino que manual
* __git branch -a__ - Ver todas las branches incluyendo las remotas
* __git remote prune origin__ - Eliminar branches eliminadas previamente en github
* __git push --tags__ - Subir los tags


__ISSUES__

* __git commit -am "bla bla fixes _#numero de issue_"__
