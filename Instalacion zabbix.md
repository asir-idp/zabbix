
# Trabajo idp tema 9 
## Hecho por: 

Instalación de Zabbix en Ubuntu 18.04, descargamos la última versión del programa utilizando el comando.

`wget https://repo.zabbix.com/zabbix/4.2/ubuntu/pool/main/z/zabbix-release/zabbix-release_4.2-1+bionic_all.deb`

![imagen](imagenes/image002.gif)

Descomprimimos y ejecutamos el programa.

![imagen2](imagenes/image003.png)

Actualizamos los repositorios.

![imagen3](imagenes/image005.png)

Instalamos el servidor de Zabbix.

![imagen4](imagenes/image007.png)

Creamos la base inicial ejecutando MariaDB.

![imagen5](imagenes/image009.png)

Especificamos "UTF-8" (codificación de caracteres unicode en iso) como predeterminado.

![imagen6](imagenes/image011.png)

Damos los privilegios de administración.

![imagen7](imagenes/image013.png)

Cerramos MariaDB con "quit".

![imagen8](imagenes/image015.png)

Importamos el esquema inicial y los datos, para ello utilizaremos la contraseña antes creada.

![imagen9](imagenes/image017.png)

Utilizando la herramienta nano editamos el fichero “/etc/zabbix/zabbix_server.conf”.

![imagen10](imagenes/image019.png)

Editamos el fichero “/etc/zabbix/apache.conf” para especificar nuestra zona horaria.

![imagen11](imagenes/image021.png)

Reiniciamos el servidor Zabbix y el agente de procesos.

![imagen12](imagenes/image023.png)

Hacemos que el servidor Zabbix inicie en el arranque

![imagen13](imagenes/image025.png)

Ya estaría completado el proceso de instalación, ahora lo iniciamos escribiendo “http://localhost/zabbix”  en el buscador.

![imagen14](imagenes/image027.png)

El programa va a comprobar los requisitos.

![imagen15](imagenes/image029.png)

Ponemos el nombre de la base de datos, el usuario y la contraseña.

![imagen16](imagenes/image031.png)

Asignamos el nombre de la base de datos.

![imagen17](imagenes/image033.png)

Esto es todo lo que vamos a instalar.

![imagen18](imagenes/image035.png)

Se nos creará el fichero que podremos editar "/usr/share/zabbix/conf/zabbix.conf.php".

![imagen19](imagenes/image037.png)

![imagen20](imagenes/image039.png)

Iniciamos sesión en el programa con usuario Admin y contraseña zabbix.

![imagen21](imagenes/image41.gif)


