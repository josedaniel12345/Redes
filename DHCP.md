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

![[DORA.excalidraw]]


