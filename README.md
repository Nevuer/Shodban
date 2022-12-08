# Shodban - https://www.nevuer.com/block-shodan-scanners-shodban/

![alt text](https://www.nevuer.com/wp-content/uploads/2022/07/Block-Shodan-Scanners.jpeg)

Bash script to block Shodan Scanners on your personal Linux Server

If you have your public IP address exposed to the world, surely Shodan has already scanned your server for open ports and versions.

The script is mainly based on collecting the known IP addresses of Shodan that can be found in this IPFire web site: https://wiki.ipfire.org/configuration/firewall/blockshodan

Once the IP addresses have been collected, a block is applied to each of them so that the server blocks incoming requests from Shodan.

---------------------------------------------------------------------------------------------------------------------------------------------------------

## BEFORE 

![alt text](https://www.neverhackme.com/wp-content/uploads/2022/07/Shodan-Info-1024x378.png)

## AFTER

![alt text](https://www.neverhackme.com/wp-content/uploads/2022/07/Shodan-Block-1024x347.png)

