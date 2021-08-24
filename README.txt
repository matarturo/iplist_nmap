Autor: Arturo Mata <arturo.mata@gmail.com>
Script: iplist.py
Versión: 1.0.0
Repositorio: https://github.com/matarturo/
Publicado bajo la Licencia Pública General GNU SIN NINGUNA GARANTÍA.
Consulte LICENCIA.TXT para obtener más detalles.

# Script Python para obtener listas de direcciones IP y puertos a partir de la salida de nmap.

# Requisitos 

Nmap => apt install nmap
Python => apt install python3
Pip Python => pip install python-nmap
Argcomplete => apt-get install -y python-argcomplete
Argparse => apt-get install python-argparse

# Descarga e instalación del script
Para ejecutar este script se requiere ingresar al equipo con credenciales de usuario <root>

$ cd/var/log
$ sudo git clone https://github.com/matarturo/iplist_nmap.git
$ cd iplist_nmap
$ sudo cp iplist.py /var/log
$ cd/var/log

#Para editar el script
$ sudo nano piplist.py  

# Ejecución del script
$ sudo python3 iplist.py 

#Detener el proceso de busqueda.
Pulsar simultáneamente las teclas CRTL + C

#Una vez obtenido el reporte de hosts activos, se detener el programa 
$ salida
