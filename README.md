# UserApi
Api using FastApi

# Commands
* Entornos virtuales

Los entornos virtuales son grupos independientes de bibliotecas de Python, 
es decir, son entornos aislados. Todo lo que se instale en ellos no afectará 
ni se verá afectado por agentes externos.

=========================
# Creacion entorno virtual
=========================

1. pip install virtualenv	# Instalacion paquete
2. virtualenv myEnv		# Creacion entorno
3. source myEnv/Scripts/activate	# Activacion entorno

==============================
# Instalacion de fastApi y vcorn
==============================
* Uvicorn (Web server): Lo utiliza fastapi para poder ejecutar 
la aplicacion de servidor

1. pip install fastapi uvicorn
2. uvicorn main:app --reload # Start web server with reload
	   nombreDelArchivo, nombreDeLaVariable	

==============================
# Docker 
==============================
1. docker run -e POSTGRES_USER=postgres -e POSTGRES_PASSWORD=postgres -e POSTGRES_DB=postgres -d -p 5432:5432 postgres                  # Ejecutar el contenedor
2. docker exec -it IdDelContenedor bash                         # Acceder al contenedor
3. psql -U postgres -d postgres
4. \dt                                                              # Listar las tablas



