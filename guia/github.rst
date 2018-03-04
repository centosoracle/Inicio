Algo de GitHub
==============

Esto tambien le sirve para que vayan viendo el documento en "rst", vayan corrihiendo los errores de hortografiA


Copien desde GitHub la ruta del repositorio.

.. figure:: ../github/images/01.png

Esto lo vamos hacer siempre desde un terminal en Linux.

En el terminal creamos un directorio.::

	$ mkdir centosoracle

Ingresamos al direcctorio.::

	$ cd centosoracle

Ahora vamos a prepara dicho directorio para que descargue el repositorio de Githup.::

	$ git init

	$ git remote add origin https://github.com/centosoracle/Inicio.git

	$ git pull origin master
	remote: Counting objects: 3, done.
	remote: Compressing objects: 100% (2/2), done.
	Unpacking objects: 100% (3/3), done.
	remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
	From https://github.com/centosoracle/Inicio
	 * branch            master     -> FETCH_HEAD
	 * [new branch]      master     -> origin/master

Listo, ya tienen el repo en local, luego veremos como hacemos para subir la informacion.


