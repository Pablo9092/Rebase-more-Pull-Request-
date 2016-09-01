# Rebase y sus aplicaciones con pull request

## ¿Para que nos sirve git rebase? ##


### Al hacer uso del comando git rebase, esté nos permite dirigirnos  al commit base donde se separan dos ramas y hace una copia de los  commits entre la cabeza y la base, entonces se generan nuevos commits  en la cabeza de master, de está forma se puede saber que se hizo en cada  commit hasta ahora. Git rebase conserva los commits que fueron replicados  por si hubiera algún error podamos regresar ha un lugar donde todo  vaya bien. Entonces podemos darnos cuenta que c y d han sido insertados  en mi rama master. Git nos permite cambiar la historía de su proyecto  pero es muy cuidadoso con esto. A continuacion en la **Figura 1** se  muestra el proceso de un rebase.


![Figura 1. Procedimiento grafico de un rebase](Downloads/Homework/Rebase.png)



## Aplicaciones con pull request##

### Cuando implementamos un pull request después de un rebase se  genera permisos para hacer fija una rama creada con el rebase, haciendo  con esto una confirmación de que hasta este punto es estable y ya no  habra retorno a los commits que fueron replicados. 
