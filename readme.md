- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
git reset -- hard HEAD~1 
Se requirio volver al commit anterior, y como no se querian descartar los 		cambios se usó --hard denture del command. - ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
git reflog : para listar el historic de los commits realizados.
git reset —hard <commit id> : para volver directamente al commit que 			habiamos desvinculado
 - El merge del paso 13, ¿Causó algún conflicto? ¿Por qué? 
No, simplemente sacó el mensaje “Already up to date”, creo que indica que no es necesario el merge.
- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué? 
Si, por que las dos ramas tenian diferencias en las líneas, por ende debió decidirse cual contenido continuaría en esa rama.
- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué? 
no, de hecho las dos ramas de este merge (master, styeled) en este paso se encuentran en el mismo commit.
- ¿Qué comando o comandos utilizaste en el paso 25?
git log —graph
- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? 
si, simplemente con que master se moviera al commit de la rama title hubiera sido suficiente para que master tuviera lo que ten title
- ¿Qué comando o comandos utilizaste en el paso 27? 
git reset HEAD~1
- ¿Qué comando o comandos utilizaste en el paso 28? 
git reset — hard HEAD
- ¿Qué comando o comandos utilizaste en el paso 29? 
git branch -D title
- ¿Qué comando o comandos utilizaste en el paso 30? 
git reflog
git reset —hard 23e58f2
- ¿Qué comando o comandos usaste en el paso 32? 
git reset — hard ba996de
- ¿Qué comando o comandos usaste en el punto 33? 
git reflog
git reset — hard ce21d9e
