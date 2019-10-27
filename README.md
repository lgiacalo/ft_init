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

