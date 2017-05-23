Alerta Red
==========

+-------------+
|alertared 3.0|
+-------------+

Este script busca los host de una red y devuelve los conectados y su MAC.
USO alertared, OPCIONES:

 -h Muestra esta ayuda.
 -l Usa el script en modo LOG, es decir pone una linea por host intruso con la fecha primero, no escribe ninguna otra informacion.
 -n No envia correo electronico.
 -m No hace uso del programa arp y no resuelve las MAC de los resultados.
 -a Devuelve todos los hosts encontrados independientemente de las variables internas IPS_CONOCIDAS y MACS_CONOCIDAS.
 -f archivo Especificar en ULTIMO LUGAR el archivo de configuracion (opcional, por defecto tiene el nombre del script con extension .cfg) que debera contener las siguientes lineas:
            1       Interfaz de red (eth0, wlan0, etc.)
            2       Bits de mascara de red (24=255.255.255.0, 16=255.255.0.0)
            3       Destinatario de correo para los avisos (usuario@dominio)
            4 y ss  MAC (a1:...) o nombre del dispositivo 

Contribuidores:
---------------

- Franklin Aliaga
- Ivan Vergés
- Sergio Antonio Barañán Lombarte