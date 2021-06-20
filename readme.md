- ¿Qué comando utilizaste en el paso 11? ¿Por qué?

	* git reset --hard HEAD~1
	* He utilizado este comando para volver al commit anterior y a la vez añadiendo el --hard hacemos el restore para recuperar el documento anterior en el working area


- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

	* git reflog,  git reset --hard c01f608
	* Utilizando git reflog he buscado el commit al que queria volver y he usado su HASH para acceder a el.

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

	* No crea ningún conflicto porque realmente no absorbe nada (Tramposo jajajaj) y da el mensaje: Already up to date

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

	* Si, porque al modificar el archivo en las 2 ramas hay lineas de codigo con distinto contenido.

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

	* No causa ningún conflicto porque no hay añadimos ningun archivo nuevo que pueda crear conflicto con su lineas de texto con otro.

- ¿Qué comando o comandos utilizaste en el paso 25?

	* git log --graph

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

	* Sí que podría ser FF, porque lo que hacemos solo es juntar los trabajos de varias ramas

- ¿Qué comando o comandos utilizaste en el paso 27?

	* git reset HEAD~1

- ¿Qué comando o comandos utilizaste en el paso 28?

	* git restore git-nuestro.md

- ¿Qué comando o comandos utilizaste en el paso 29?

	* git branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30?

	* git reset 6e3414b, este es el hash del merge de title para volver a el.	

- ¿Qué comando o comandos usaste en el paso 32?

	* git reflog, git reset 637ade5

- ¿Qué comando o comandos usaste en el punto 33?

	* git reflog, git reset 0e62113
