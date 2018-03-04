Algo de GitHub
==============

Esto tambien le sirve para que vayan viendo el documento en "rst", vayan corrihiendo los errores de hortografiA

Como descargar el Repositorio de GitHub a local
+++++++++++++++++++++++++++++++++++++++++++++++


Copien desde GitHub la ruta del repositorio.

.. figure:: ../images/github/01.png

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

Como hacer que GitHub acepte nuestras modificaciones
++++++++++++++++++++++++++++++++++++++++++++++++++++

Vamos a configurar nuestro equipo local para que podamos tener sincronizado nuestros repositorios contra el Github. Esto es lo que nos permitira hacer modificaciones en nuestros equipos "repositorios locales" y subirlo al Github "Repositorio de Github"


Github necesita saber quienes estan autorizado para subir informacion y para lograr eso lo hace gracias a las llaves publicas "Si no sabemos como se crean las llaves publicas, sigue este procedimiento https://github.com/centosoracle/Inicio/blob/master/guia/llavepublica.rst ...!!! ", pero si saben hagamos lo sigueinte, no lo voy a explicar solo dejo las imagenes.

.. figure:: ../images/github/02.png


.. figure:: ../images/github/03.png


.. figure:: ../images/github/04.png


.. figure:: ../images/github/05.png


.. figure:: ../images/github/06.png


Como subir modificaciones locales al Repositorio de GitHub
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

Luego que ustedes ya tengan el repositorio en local lo pueden editar con el editor de su preferencia.::

	$ vi guia/github.rst

luego de gurdar los cambios, con los comando de git, vamos a indicarle que agregue todos los archivo que han sido modificados.








