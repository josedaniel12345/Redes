El protocolo DHCP se basa en las siglas DORA:

- DISCOVER
- OFFER
- REQUEST
- ACK

![[Pasted image 20231116131518.png]]

Como se puede apreciar el DHCP REQUEST que algunos piensan que es unicast es un broadcast por el simple hecho de que la dirección de destino es 255.255.255.255.


DORA:
- DHCP DISCOVER → BROADCAST
- DHCP OFFER → UNICAST
- DHCP REQUEST → BROADCAST
- DHCP ACK → UNICAST
- DHCP NACK → UNICAST

EXPLICACIÓN PETICIONES/PROCESO DHCP
- DISCOVER:
  - El "DHCP Discover" es el primer paso en el proceso de asignación dinámica de direcciones IP en una red. En este paso, un dispositivo, como un equipo u ordenador, envía un mensaje de descubrimiento DHCP a la red con el fin de obtener una dirección IP. Este mensaje es transmitido a través de la red y es la manera en que un dispositivo busca un servidor DHCP disponible para obtener una configuración de red, que incluye la dirección IP asignada, la máscara de subred, la puerta de enlace y otros parámetros de red necesarios.
- OFFER:
  - En el proceso de asignación dinámica de direcciones IP en una red, después de que un dispositivo, como un equipo u ordenador, envía un mensaje de descubrimiento DHCP (DHCP Discover), los servidores DHCP disponibles responden con un mensaje llamado DHCP Offer. Este mensaje contiene una oferta de configuración de red, que incluye una dirección IP disponible para el dispositivo, así como otros parámetros de red como la máscara de subred, la puerta de enlace y la configuración de DNS. El dispositivo receptor evalúa las ofertas y selecciona una para aceptar, marcando así el siguiente paso en el proceso DHCP.

### RESUMEN

En resumen, el proceso completo implica el "DHCP Discover" del dispositivo, seguido por el "DHCP Offer" de los servidores disponibles, luego el "DHCP Request" del dispositivo para solicitar la configuración deseada, y finalmente, el "DHCP Acknowledgment" o "DHCP Negative Acknowledgment" del servidor para confirmar o rechazar la solicitud.


![[https://github.com/josedaniel12345/Redes/blob/main/DORA.png]]


