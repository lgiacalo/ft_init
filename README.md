# ft_init

#######################################################################
# Mac
## Files
	- /etc/networks
	- 

## Commands
	- networksetup -listallhardwareports
	- netstat -nr
	- nslookup [domain] [server]
	- scutil --dns
	- host
	- ping
	- route
	- traceroute
	- ipconfig getpacket en0
		yiaddr:						Adresse IP attribuée à l'interface réseau spécifiée sur le système à partir duquel la commande a été émise.
		server_identifier (ip):		L'adresse IP du serveur DHCP.
		chaddr:						Le contrôle d' accès au support (MAC) adresse associée à l'interface réseau spécifiée.
		subnet_mask (ip):	Le masque de sous-réseau.
		router (ip_mult):			Le routeur auquel les paquets réseau destinés aux systèmes extérieurs au sous-réseau doit être envoyé, à savoir l' adresse de la passerelle .
	- 

## See
	- netstat =  Afficher les connexions reseau, les tables de routage, les statistiques des interfaces, les connexions masquees, et les membres multicast.  
	- 



########################################################################
# Linux
## Files
	- 

## Commands
	- 

## See
	- udev

## Install
	- sudo apt-get install net-tools 
		(echo "export PATH=$PATH:/sbin" >> .bashrc)
	- 



########################################################################
# Utils
	- find / -iname resolv.conf 2> /dev/null


########################################################################
# Regex 
	.	= any char
	\.	= the actual dot character
	.?	= .{0,1}	= match any char zero or one times
	.*	= .{0,}		= match any char zero or more times
	.+	= .{1,}		= match any char one or more times



########################################################################
# Instructions
	Bleu :  une commande
	Vert :	une sortie de commande
	Rouge:	une deduction ecrite

#TODO: verifier nom des fichiers 01 ou 1