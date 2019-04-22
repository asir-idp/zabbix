
# Trabajo idp tema 9 
## Hecho por: 

Instalación de Zabbix en Ubuntu 18.04, descargamos la última versión del programa utilizando el comando.

`wget https://repo.zabbix.com/zabbix/4.2/ubuntu/pool/main/z/zabbix-release/zabbix-release_4.2-1+bionic_all.deb`

![imagen](imagenes/image002.gif)

Descomprimimos y ejecutamos el programa.

![imagen2](imagenes/image003.png)

Actualizamos los repositorios.

![imagen3](imagenes/image)

Instalamos el servidor de Zabbix.

![imagen4](imagenes/image)

Creamos la base inicial ejecutando MariaDB.

![imagen5](imagenes/image)

Especificamos "UTF-8" (codificación de caracteres unicode en iso) como predeterminado.

![imagen6](imagenes/image)

Damos los privilegios de administración.

![imagen7](imagenes/image)

Cerramos MariaDB con "quit".

![imagen3](imagenes/image)

Importamos el esquema inicial y los datos, para ello utilizaremos la contraseña antes creada.

![imagen3](imagenes/image)

Utilizando la herramienta nano editamos el fichero “/etc/zabbix/zabbix_server.conf”.

![imagen3](imagenes/image)

Editamos el fichero “/etc/zabbix/apache.conf” para especificar nuestra zona horaria.

![imagen3](imagenes/image)

Reiniciamos el servidor Zabbix y el agente de procesos.

![imagen3](imagenes/image)

Hacemos que el servidor Zabbix inicie en el arranque

![imagen3](imagenes/image)

Ya estaría completado el proceso de instalación, ahora lo iniciamos escribiendo “http://localhost/zabbix”  en el buscador.

![imagen3](imagenes/image)

El programa va a comprobar los requisitos.

![imagen3](imagenes/image)

Ponemos el nombre de la base de datos, el usuario y la contraseña.

![imagen3](imagenes/image)

Asignamos el nombre de la base de datos.

![imagen3](imagenes/image)

Esto es todo lo que vamos a instalar.

![imagen3](imagenes/image)

Se nos creará el fichero que podremos editar "/usr/share/zabbix/conf/zabbix.conf.php".

![imagen3](imagenes/image)
![imagen3](imagenes/image)

Iniciamos sesión en el programa con usuario Admin y contraseña zabbix.

![imagen3](imagenes/image)


