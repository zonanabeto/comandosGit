# Curso Git

## Comandos Importantes

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