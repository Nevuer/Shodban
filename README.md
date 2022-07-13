# Shodban
Bash script to block Shodan Scanners

If you have your public IP address exposed to the world, surely Shodan has already scanned your server for open ports and versions.

The script is mainly based on collecting the known IP addresses of Shodan that can be found in this IPFire web site: https://wiki.ipfire.org/configuration/firewall/blockshodan

Once the IP addresses have been collected, a block is applied to each of them so that the server blocks incoming requests from Shodan.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Script en Bash que te permite bloquear los escaners de Shodan en tu servidor web Linux.

Si tienes tu dirección IP pública expuesta al mundo, seguramente Shodan ya ha escaneado tu servidor en busca de puertos y versiones abiertas.

El script se basa principalmente en recoger las direcciones IP conocidas de Shodan que se pueden encontrar en esta web de IPFire: https://wiki.ipfire.org/configuration/firewall/blockshodan

Una vez recogidas las direcciones IP, se aplica un bloqueo a cada una de ellas para que el servidor bloquee las peticiones entrantes de Shodan.

Traducción realizada con la versión gratuita del traductor www.DeepL.com/Translator
