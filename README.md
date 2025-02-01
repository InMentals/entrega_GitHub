# entrega_GitHub

- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
	git reset --hard HEAD~1
	
	Porque este comando me devuelve al último comit perdiendo 
	los cambios del working copy, y como estoy en la rama "styled" 
	es como si hubiera hecho retroceder la rama al último commit.

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
 	git reflog 
	git reset --hard <commit_hash>
	
	Consulto primero el hash del commit al que quiero ir y lo rehago de la
	misma forma que lo he deshecho y haciendo avanzar la rama.
   

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
	No causó ningún conflicto como tal, simplemente la rama integradora ("styled")
	es padre de la rama que estoy intentando integrar ("main"). Es decir, ya
	esta integrada. Por eso git devuelve el mensaje "Already up to date".


- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
	Sí causó conflicto porque en ambas ramas hubo modificaciones en el 
	archivo git-nuestro.md.


- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
	No causó ningún conflicto porque al estar en la misma línea
	se hizo con fast-forward.


- ¿Qué comando o comandos utilizaste en el paso 25?
	git log --graph --decorate --pretty=oneline


- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
	Sí, podría ser fastforward porque la rama integradora ("main")
	es un estado anterior de la rama integrada ("style").
	Sería como hacer una actualización.


- ¿Qué comando o comandos utilizaste en el paso 27?
	git reset HEAD~1


- ¿Qué comando o comandos utilizaste en el paso 28?
	git restore git-nuestro.md


- ¿Qué comando o comandos utilizaste en el paso 29?
	git branch -D title


- ¿Qué comando o comandos utilizaste en el paso 30?
	git reflog
	git reset --hard <commit_hash>


- ¿Qué comando o comandos usaste en el paso 32?
	git reflog
	git checkout <commit_hash>


- ¿Qué comando o comandos usaste en el punto 33?
	git checkout main
