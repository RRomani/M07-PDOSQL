# M07-PDOSQL
1º Instalamos mysql-server con la siguiente comanda: sudo apt-get install mysql-server

2º Entraremos en el modo mysql con este comando: mysql -u -p

3º Nos descargamos la BD de internet.

4º Pasamos la informacion que acabamos de descargar a una BD que crearemos, con la consulta: mysql -u root -p world <~/Baixades/world.sql

5º Despues instalaremos php-mysql para poder usar mysql desde archivos php, comando: sudo apt-get install php-mysql

6º Reiniciamos el servicio de apache2: sudo service apache2 restart

Y se acabo.
