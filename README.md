- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
git reset --hard HEAD~1
Esto eliminara los cambios realizados en el commit

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
git reflog para ver los commit y ver la id del que necesitamos
git reset con la id del commit

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
Al absorber la rama no tuve conflictos se hicieron los cambios sobre el documento

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Si hubo conflicto en el documento. Habia conflicto con lineas que se superponian.
 Nos quedamos con la versión del styled como requeria la practica. 

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
En este caso no hemos tenido conflictos ya que no se pisaban las lineas.

- ¿Qué comando o comandos utilizaste en el paso 25?
git log --oneline --graph --all

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Podria ser si no hubiera commits como si los tenemos no puede ser 

- ¿Qué comando o comandos utilizaste en el paso 27?
git reset --soft 

- ¿Qué comando o comandos utilizaste en el paso 28?
git reflog para ver la ide del paso a descartar 
git reset --hard con la id del paso 

- ¿Qué comando o comandos utilizaste en el paso 29?
git branch -D 

- ¿Qué comando o comandos utilizaste en el paso 30?
git merge --no-ff title -m 

- ¿Qué comando o comandos usaste en el paso 32?
git log y git checkout con la id del commit

- ¿Qué comando o comandos usaste en el punto 33?
git log y git checkout con la id del commit
