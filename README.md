# EJERCICIO REDES
* ## Redes
  * ### Primera red
  ----------------------------------------------------------------
  Máscara | Dirección de red | Primera IP | Última IP | Broadcast
  ------- | ---------------- | ---------- | --------- | ---------
  255.255.255.128 | 192.168.1.0 | 192.168.1.1 | 192.168.1.126 | 192.168.1.127
  255.255.255.224 | 192.168.1.128 | 192.168.1.129 | 192.168.1.158 | 192.168.1.159
  255.255.255.248 | 192.168.1.160 | 192.168.1.161 | 192.168.1.166 | 192.168.1.1677
  --------------------------------------
  Las características de las tres subredes en las que está dividida están explicadas en la tabla. Cada host de la subred está comunicado por un switch, que a su vez conecta con otro switch que une las subredes.
  * ### Segunda red
  Esta segunda red usará la dirección 192.168.2.0, las direcciones IP de los host serán dadas por un servidor DHCP con IP 192.168.2.2
  * ### Tercera red
  Esta red usa la dirección 192.168.3.0, al igual que la segunda red asigna las IP con un servidor DHCP alojado en la dirección IP 192.168.3.2
  * ### Cuarta red
  Se usa la dirección de red 192.168.4.0, tiene 4 ordenadores de IP fija, siendo éstas 192.168.4.2, 192.168.4.3, 192.168.4.4 y 192.168.4.5 y 5 que optienen la IP a través de un DHCP (alojado en la dirección 192.168.4.7).
  * ### Quinta red
  Usa la dirección 192.168.5.0, tiene alojados 5 ordenadores cuyas IP son 192.168.5.2, 192.168.5.3, 192.168.5.4, 192.168.5.5 y 192.168.5.6.
* ## Routers
  Cada router posee la primera IP de su red (192.168.1.1, 192.168.2.1 , 192.168.3.1, 192.168.3.1 y 192.168.4.1), a su vez estos están conectados entre sí usando las redes con dirección 192.168.10.0, 192.168.11.0, 192.168.12.0 y 192.168.13.0. Para esto les he asignado como host las direcciones IP 10 y 11.
* ## Servidores web
  Están los tres alojados en la tercera red.
  * ### Dilar
  Tiene la dirección IP 192.168.3.154.
  * ### Wagner
  Tiene la dirección IP 192.168.3.153.
  * ### Albacete
  Tiene la dirección IP 192.168.3.152.
 * ## DNS
    El DNS que resuelve las direcciones de estos servidores tiene la IP 192.168.3.151
