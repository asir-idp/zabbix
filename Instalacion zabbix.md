
# Trabajo idp tema 9 

## Hecho por:

1º Instalación de Zabbix en Ubuntu 18.04, descargamos la última versión del programa utilizando el comando.

`wget https://repo.zabbix.com/zabbix/4.2/ubuntu/pool/main/z/zabbix-release/zabbix-release_4.2-1+bionic_all.deb`

![imagen](imagenes/image002.gif)

2º Descomprimimos y ejecutamos el programa.

![imagen2](imagenes/image003.png)

3º Actualizamos los repositorios.

![imagen3](imagenes/image005.png)

4º Instalamos el servidor de Zabbix.

![imagen4](imagenes/image007.png)

5º Creamos la base inicial ejecutando MariaDB.

![imagen5](imagenes/image009.png)

6º Especificamos "UTF-8" (codificación de caracteres unicode en iso) como predeterminado.

![imagen6](imagenes/image011.png)

7º Damos los privilegios de administración.

![imagen7](imagenes/image013.png)

8º Cerramos MariaDB con "quit".

![imagen8](imagenes/image015.png)

9º Importamos el esquema inicial y los datos, para ello utilizaremos la contraseña antes creada.

![imagen9](imagenes/image017.png)

10º Utilizando la herramienta nano editamos el fichero “/etc/zabbix/zabbix_server.conf”.

![imagen10](imagenes/image019.png)

11º Editamos el fichero “/etc/zabbix/apache.conf” para especificar nuestra zona horaria.

![imagen11](imagenes/image021.png)

12º Reiniciamos el servidor Zabbix y el agente de procesos.

![imagen12](imagenes/image023.png)

13º Hacemos que el servidor Zabbix inicie en el arranque

![imagen13](imagenes/image025.png)

14º Ya estaría completado el proceso de instalación, ahora lo iniciamos escribiendo “http://localhost/zabbix”  en el buscador.

![imagen14](imagenes/image027.png)

15º El programa va a comprobar los requisitos.

![imagen15](imagenes/image029.png)

16º Ponemos el nombre de la base de datos, el usuario y la contraseña.

![imagen16](imagenes/image031.png)

17º Asignamos el nombre de la base de datos.

![imagen17](imagenes/image033.png)

18º Esto es todo lo que vamos a instalar.

![imagen18](imagenes/image035.png)

19º Se nos creará el fichero que podremos editar "/usr/share/zabbix/conf/zabbix.conf.php".

![imagen19](imagenes/image037.png)

![imagen20](imagenes/image039.png)

20º Iniciamos sesión en el programa con usuario Admin y contraseña zabbix.

![imagen21](imagenes/image042.gif)


