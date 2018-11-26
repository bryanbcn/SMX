# Partprobe
es un programa, Comando que informa al kernel del sistema operativo sobre los cambios en la tabla de particiones, solicitando que el sistema operativo vuelva a leer la tabla de particiones.

Un uso práctico del comando es usarlo después de utilizar Fdisk o GParted para que el sistema operativo reconozca la nueva configuración de la tabla de particiones. 

## Extensiones útiles del comando 

Partprobe -d (No aactualizes el kernel)
Partprobe -s (Nos muestra un resumen de los dispositivos y las particiones del sistema)
partprobe -h:(Nos muestra las opciones que nos ofrece el comando)
