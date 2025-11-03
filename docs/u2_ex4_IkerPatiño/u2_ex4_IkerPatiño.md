#  Práctica 4: PHPMYADMIN
## Instal·lació de PhpMyAdmin
Instalamos phpadmin
![d](1.png)

Añadimos contraseña para phpmyadmin
![dd](2.png)

Crearemos un enlace simbolico para que nginx pueda acceder a phpMyAdmin
![dd](3.png)

Ahora comprobamos que funcione.

![€d](4.png)

## Permitir acceso por contraseña del root de MySQL
Ahora entraremos a MySQL y añadiremos lo siguiente para permitir acceso por contraseña.

![d](5.png)

## Configuración de acceso por contraseña para un usuario dedicado de MySQL
Creamos un usuario nuevo.

![d](6.png)

Le damos privilegios y aplicamos cambios.

![ðd](7.png)

Y ahora comprobamos.

![e](8.png)

## Asegura la instancia de PHPMyAdmin
Creamos un fichero .htpasswd para almacenar credenciales usuarios y contraseñas.

![dd](9.png)

Ahora lo añadimos a la configuración.

![dd](10.png)

Ahora volvemos a acceder a la página y nos pedirá contraseña.

![d](11.png)

