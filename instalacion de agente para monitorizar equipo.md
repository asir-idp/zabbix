# Trabajo idp tema 9

## Instalacion del agente zabbix para poder monitorizar la maquina donde lo vamos a instalar

1º Entramos en la pagina oficial de Zabbix y nos vamos a descargas, hay elegiremos Zabbix Agents y elegimos la version para nuestro ordenador, y le damos a descargar. 

![imagen1](imagenes/Captura-agente.JPG)

2º Nos vamos donde este el instalador y le damos doble click.

![imagen2](imagenes/Captura-agente2.JPG)

3º Le damos a next, y seguimos.

![imagen3](imagenes/Captura-agente3.JPG)

4º Aceptamos la licencia de zabbix.

![imagen4](imagenes/Captura-agente4.JPG)

5º Esta es la parte mas importante en la cual ponemos la ip de nuestro servidor zabbix y le damos al icono de Remote command, el resto viene por defecto aunque puedes cambiar el Host name.

![imagen5](imagenes/Captura-agente5.JPG)

6º Le damos a next, y seguimos.

![imagen6](imagenes/Captura-agente6.JPG)

7º Le damos al boton de instalar . 

![imagen7](imagenes/Captura-agente7.JPG)

8º Y le damos a finish.

![imagen8](imagenes/Captura-agente8.JPG)

9º Ahora bien para que el equipo y el servidor se puedan conectar bien sin ningun problema vamos a hacer un `ping` en el cmd poniendo la ip del servidor zabbix. 

![imagen9](imagenes/Captura-agente9.JPG)

10º Para que el ping se efectivo debemos desctivar el firewall de windows para que funcione, tras haber hecho el ping lo volvemos a activar. 

![imagen10](imagenes/agente.JPG)