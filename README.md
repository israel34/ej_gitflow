ej_gitflow

## CREACION RAMA DESARROLADOR
## El primer paso es crear la rama develop. Esto podría hacerse de manera normal con:
 git branch develop  
 git push origin develop  


Esta rama, es la que tendrá toda la historia del Proyecto. El resto de desarrolladores que colaboren con el proyecto,
deben clonar esta rama.
Si se usa la extensión git-flow, al ejecutar git flow init, este crearía la rama develop.

## CREAR RAMA DIFERENTE
## Como empezar una rama de característica
git flow feature start nombre_caracteristica  
## Como terminar una rama de característica.
Cuando se haya terminado con el desarrollo de la nueva característica del proyecto, el siguiente paso es realizar la migración (merge) con la rama develop.
