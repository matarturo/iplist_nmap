
Script Python para obtener listas de direcciones IP a partir de la salida de nmap.
Autor: Arturo Mata <arturo.mata@gmail.com>
Script: ping.py
Versión: 1.0.0
Repositorio: https://github.com/matarturo/
Publicado bajo la Licencia Pública General GNU SIN NINGUNA GARANTÍA.
Consulte LICENCIA.TXT para obtener más detalles.

# Este script escrito en Python analiza segmentos red para validar los hosts activos

# Requisitos 

Nmap => apto instalar nmap
Python => apto instalar python3
Pip Python => pip instalar python-nmap

# Descarga e instalación del script
Para ejecutar este script se requiere ingresar al equipo con credenciales de usuario <root>

$ cd / var / log
$ sudo git clone https://github.com/matarturo/scan_subnet.git
$ cd scan_subnet
$ sudo cp ping.py / var / log
$ cd / var / log

#Para editar el script
$ sudo nano ping.py  

# Ejecución del script
$ sudo python3 ping.py 

#Detener el proceso de busqueda.
Pulsar simultáneamente las teclas CRTL + C

#Una vez obtenido el reporte de hosts activos, se detener el programa 
$ salida
