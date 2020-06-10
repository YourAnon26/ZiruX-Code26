# ZiruX-Code26

## Opciones de Configuracion

* `-h = Menu de Ayuda`
* `-t = Web o IP`
* `-p = Puerto   --> defecto: 80 Optimo: [80 o 443]`
* `-c = Clientes --> defecto: 50 Optimo: [30-135]`
* `-m = Metodo   --> defecto: RANDOM Opciones: [get o post]`
* `-T = Habilitar el enrutamiento TOR, por defecto: Desactivado`


## Ejemplos de comandos.

  Sin TOR:
* `python3 code26.py -t www.ejemplo.com`
* `python3 code26.py -t www.ejemplo.com -p 80 -c 50 -m get`
  Con TOR:
* `python3 code26.py -t www.ejemplo.com -T`
* `python3 code26.py -t www.ejemplo.com -p 80 -c 50 -m get -T`

## Revisamos que python esta instalado correctamente en su version 3.6 o superior
* `python3 -V`


## Como Instalo Tor Network
* `sudo apt-get update`
* `sudo apt-get install tor`
* `sudo apt-get install torsocks`
* `sudo apt-get install tor-geoipdb`
* `sudo /etc/init.d/tor restart`
