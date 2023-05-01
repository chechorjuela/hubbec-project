# hubbec-project back-hubbec

** Paketes
las versiones con que se fueron creadas este aplicativo fue con la version 16.14.0 de node y 8.3.1. y angular v15.2.

Se debe tener instalado mongoDb, junto con compass para visualizar los cambios en la db.

El proyecto se encuentra desarrollada en las tecnologias mas recientes para angular y nodejs con express. la instalacion del proyecto se tiene que obtener los cambios
de los submodulos de git.

### Git 
Abrir el terminar y ejecutar los siguientes comandos para actualizar los submodulos
>  git submodule update --init --recursive
> 	
>  git submodule update --remote


en la carpeta se necesitara crear un archivo .env en la carpeta root ya que sera el archivo de configuracion.

back-hubbec/.env

Contenido:

APPLICATION_PORT=3000
MONGO_DATABASE=usershubbec
MONGO_PORT=27017
MONGO_HOST=localhost
MONGO_PASSWORD=
MONGO_USER=
TOKEN_EXPIRATION_IN_MIN=587
DEBUG=true
URL_CLIENT=http://localhost:3000

cuando se halla terminado de finalizar de crear el archivo de configuracion. a continucion debemos correr el comando:

> npm i

hay que tener presente que dentro de esta carpeta existe una carpeta public la cual es donde se guardan las imagenes. lo mejor es que esta carpeta permisos de editar, creacion, y eliminar.

cuando se halla terminado estos pasos de configuracion debemos correr el comando.

> npm run dev.

# Angular  angular-hubbec

para el proyecto de angular solamente tendremos que correr el comando 
> npm i

Cuando se halla finalizado se podra correr con:
> npm start
