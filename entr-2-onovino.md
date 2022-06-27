# Entregable informática - 2 - clase 12 [onovino]

## ¿Que es un usuario root en Linux?

Se conoce como superusuario que posee todos los permisos, derechos, coloquialmente conocido como administrador.

## ¿Por qué ubuntu no me deja establecer la contraseña durante la instalación?

Por defecto en Linux la cuenta root no tiene una contraseña establecida.
Se utiliza y recomienda el comando sudo para ejecutar comandos con privilegios de nivel raíz, donde la contraseña es aquella
asignada al usuario que está ejecutando los comandos en la terminal. Porque así realiza cambios de forma temporal y no
con una cuenta con todos los privilegios, lo cual puede tener consecuencias.

## ¿Cuáles son los procesos típicos de Linux?

El kernel de Linux - PID1 con máxima prioridad (init) arranca el sistema, definido como padre y luego los demás procesos
ejecutados a partir de este son procesos hijos.

## ¿Cómo identificarlos?

top: monitorear porque se están ejecutando en ese momento.
ps -efH | less: muestra de manera detallada la jerarquías de los procesos.
PID: es un id (único) asociado a ese proceso que se está ejecutando.
PPID: es el proceso padre.

## Investigar y establecer una contraseña para el usuario root.

Hay varias formas. Una de ellas es ejecutar en la terminal el siguiente comando:
sudo passwd root, sudo passwd -dl root.
