# Ejecución de cliente y servidor TCP
## ISIS3204 2023-10
### Sección 3 - Grupo 1

**Pasos para la ejecución**

1. Descargar los archivos de 100 MB y 250 MB disponibles en este [link](https://uniandes-my.sharepoint.com/:u:/g/personal/jp_martinezp1_uniandes_edu_co/EbFFCwdiGFJBvFdDJ40gZ3MBh6xnwq74i03U5ECAyZlbgg?e=lKcfvx) y guardarlos en la misma carpeta del archivo *lab3_server.py* en la máquina virtual
2. En la constante *HOST*, de los archivos [*lab3_client.py*](./lab3_client.py) y [*lab3_server.py*](./lab3_server.py), reemplazar *localhost* por la dirección IP de la máquina en la que se ejecutará el servidor
3. Desde una terminal en la máquina virtual, ejecutar el archivo de Python correspondiente a la aplicación del servidor con el comando *python lab3_server.py*. Se le pedirá ingresar el número de clientes esperados y el archivo que quiere transferir
4. Desde una terminal en la máquina local, ejecutar el archivo de Python correspondiente a la aplicación del cliente con el comando *python lab3_client.py*. Se le notificará que se iniciará la cantidad de clientes especificados en el servidor, posteriormente debe escribir **READY** desde la terminal para iniciar la transferencia del archivo a todos los clientes
5. Se imprimirá por la terminal cuando cada cliente inicie y también cuando finalice
6. Esperar hasta que todos los clientes hayan finalizado su proceso. Se habrán guardado los archivos transferidos a cada cliente y el archivo de log en las carpetas *ArchivosRecibidos* y *Logs*, respectivamente
