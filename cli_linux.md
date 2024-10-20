# Common
`ls`	`cd ..`	`pwd`	`exit`

`mkdir` 	`rmdir`	`nano`	`less`

`cat`	`head`	`tail`

`md5sum filename.txt`

`sha256sum filename.txt`

`cp source to dest`


`echo “hidden text” > filename.txt:hiddenpart`

`more < filename.txt:hiddenpart`

# locate password - find files
`grep [searchterm] /etc/shadow` a pwfile

`find -iname "me.txt"`

`logger “[message]”`

`cd /var/log` syslog

`apt-get install [programname]`

`apt-get remove [programname]`

`apt-get update`

`apt-get upgrade` 

`apt-get clean`

`apt update –y && apt upgrade –y && apt 	dist-upgrade `


`adduser [username] sudo`

`su 	#switch user`

`id root 	#info about root`

`whoami`

`history`

`chmod [u (user) | g (group) | o (others) | a 	(all)] [+ | - | =] [r | w | x]`
`chmod a=r` read only for all

`sudo apt install app_name`
`service app_name start`
`service app_name stop`

# Network
`arp-scan 192.168.1.0/24`

`traceroute 4.4.4.4`

`ping 4.4.4.4`

`ifconfig`

`iwconfig`

`dig google.com` 	#dns lookup

`dig dell.com MX`

`dig dell.com axfr` 	#attempts zone transfer

`dnsenum dell.com`

`arp –a` 		#show arp table

`route` #show route table

`curl google.com` 	#gets 

`rdesktop www.dell.com`

`whois google.com`

`telnet www.campus.edu 21` #service p21

`telnet 10.9.2.3`

`netstat -r`	#view routing table

`scanless -t example.com -s spiderip

`scanless -l` #gives a list of services instead of spiderip

`ifconfig eth0 0.0.0.0 up `

`ifconfig eth0 1.1.1.1 netmask 255.255.255.0` #Sets IP 

