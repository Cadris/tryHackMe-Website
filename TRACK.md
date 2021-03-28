#Connect To Network-

-> used $ sudo openvpn path/to/silverKail.ovpn

#nmap to sniff the ports 

sudo nmap -sV -sC -oN outputFile_Name  <ip> 

	-sV :	Attempts to determine the version of the services running
	-sC : 	Scan with the default nmap scripts
	-oN :	Output File Name


Result stored in **vulnversity/result.md**

Open Ports
```
21 	- ftp
22 	- ssh
139
445
3128
3333 - http


```
