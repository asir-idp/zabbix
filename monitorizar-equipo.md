# Monitorizar un equipo con Zabbix

Creación de un "host" en Zabbix para monitorizarlo:

1. Entramos en la interfaz web de administración de Zabbix, vamos al apartado "Configuration" y, dentro de éste, entramos en el apartado "Host". 

![imagen](imagenes/Monitorizarequipo1.JPG)

2. Pulsamos en "create host" y empezamos a configurar el host. Ponemos un nombre en este caso "windows-pc" y en el apartado grupos añadimos todos los grupos.

![imagen](imagenes/Monitorizarequipo2.JPG)

3. En "Agent Interfaces" añadimos la IP del equipo que vamos a monitorizar, en este caso la IP será 10.1.1.28. Dejamos las demas opciones por defecto y de damos a "Add".

![imagen](imagenes/Monitorizarequipo3.JPG)

4. Entramos en el host que acabamos de crear y nos vamos a la pestaña de "Templates", buscamos el template "Windows OS", le damos a "add" y después a "update".

![imagen](imagenes/Monitorizarequipo4.JPG)

5. Para comprobar la conectividad del servidor con el cliente hacemos un `ping` al equipo del cliente.

![imagen](imagenes/Monitorizarequipo5.JPG)

6. Nos vamos a "Monitoring", y dentro de este pulsamos en Graphs, en "Host" seleccionamos windows-pc

![imagen](imagenes/Monitorizarequipo6.JPG)

7. En "Graph" tenemos dos opciones disponibles una para monitorizar la CPU (CPU Load) y otra para monitorizar la memoria (Memory usage). 

![imagen](imagenes/Monitorizarequipo7.JPG)

8. Vamos a seleccionar la opción de la CPU. Tenemos distintas opciones de tiempo disponibles, vamos a seleccionar .

![imagen](imagenes/Monitorizarequipo8.JPG)

9. Por últimos vamos a monitorizar el uso de memoria. Ya estaría la monitorización completada. 

![imagen](imagenes/Monitorizarequipo9.JPG)
