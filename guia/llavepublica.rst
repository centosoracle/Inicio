Como crear nuestra llave publica de un servidor
===============================================

Debemos tener el paquete instalado.::

	# yum install openssh-server

Ahora ejecutamos el siguiente comando para que cree la llave privada y publica del servidor y se creara en el Home Directory del usuario en este directorio oculto ".ssh".::

	# ssh-keygen -b 4096 -t rsa

	Generating public/private rsa key pair.
	Enter file in which to save the key (/root/.ssh/id_rsa):
	Enter passphrase (empty for no passphrase):
	Enter same passphrase again:
	Your identification has been saved in /root/.ssh/id_rsa.
	Your public key has been saved in /root/.ssh/id_rsa.pub.
	The key fingerprint is:
	c8:7e:e9:d2:d4:0b:20:8c:10:48:42:d5:5b:6f:45:49 root@debian
	The key's randomart image is:
	+---[RSA 4096]----+
	|*+...     oE.    |
	|+    . .   o     |
	| . o  o . .      |
	|  . oo.. o       |
	|     .o.S.       |
	|     .  o..      |
	|      .oo. .     |
	|      .o. .      |
	|       ..        |
	+-----------------+

Listo, ya tenemos la llave pública… Ahora solo la consultamos y la copiamos para colocarla en el Github.::

	~/.ssh$ cat id_rsa.pub 
	ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQDTzO97CPyQHRiszQOPCr7i3Mz/hcudhYt0yXTfCiMGjxOCpyd+x8fhekfc8Dt1HCOoC6JfYAE0LDW0WH/fLI2xD1gDgH0VeyDtqlkZtrgm6YknTlCwixBVpUjnMNv0EhqyE7VakPlGOgbqJ9tUhSJsBVTM5wa61qRSDVIxuBtLjcSQgrnYagzhGB8LZ4JZq8JvUXTGzxVdpsy9N2XVebuhKXNYpxF8XsLZfW8airuQtZuHBDrmV1MSCemAHw5YcCw6mUFZuyEdtOwEl2gF/AgFsId7Pcsfc1M4pqovny5igSYXgSmv+yWKDn2v6cG24eqR+suolNQl cgomezn.stack@gmail.com



