# ToDoApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.3.3.

## Build

Para poder iniciar el proyecto necesitaremos instalar unos paquetes antes de nada, para ello utilizaremos los comandos en la terminal de linux:
$ `sudo apt install git`
$ `sudo apt install npm`
$ `sudo npm clean -f`
$ `sudo npm i -g n`
$ `sudo n stable `
$ `npm i -S express`
$ `npm i -D nodemon `
$ `npm i -S mongodb`
$ `npm i -S mongojs`
$ `npm i -S cors`
$ `npm i -S jwt-simple`
$ `npm i -S moment`
$ `npm i -S bcrypt`
$ `npm i -S morgan`
$ `npm i -S helmet`
Para iniciar nuestro proyecto necesitaremos abrir una terminal y dirigirnos al directorio:
	*/node/api-crud/ y ejecutamos $ `npm start` 
se ejecutará en el puerto 4000.
Luego repetimos el proceso en otra terminal nueva y nos dirigimos al directorio: 
	*/node/api-auth/ y ejecutamos $ `npm start` 
Se ejecutará en el puerto 4100
También necesitamos iniciar mongo con:
	$ sudo systemctl start mondongo
y opcionalmente iniciar el shell de mongo con: $ mongosh
Por último necesitaremos ir en una nueva terminal en el directorio:
	*/node/to-do-app/
y ejecutar la aplicación con:
	$ `ng serve`
Para acceder a la aplicación necesitamos entrar en la dirección:


localhost:4200/login, y loguearse con por ejemplo
email: prueba1@pru.eba
contraseña: prueba1
