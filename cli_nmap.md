nmap 192.168.1.1/24 	#All 256 IPs

nmap example.com –p 23	#port 23

nmap -oN examplescan.txt example.com 

-sV	#services		-sU	#UDP

-sn	#no portscan	-A	#all 

-O	#os detection	--script default

-T0	#slowest		-T5	#fastest

-sC 	#common scripts 	-PR	#ARP scan

nmap --top-ports 20 192.168.1.106 #top 20

nmap --script ftp-brute -p 21 192.168.1.105 

nmap -Pn --script vuln 172.20.10.1

nmap --script-help "afp-* and discovery“
	#filename and category

Categories: 

discovery, dos, exploit, external, fuzzer, intrustive, safe, version, vuln, malware #detects for malware

# Firewall
-sA	#See FW filtered ports

-sN	#TCP, no flag. non-stateful firewall

-Pn	#Skip discovery. Firewall may block discovery

-f	#split packets

-g 	#use given port number to send

-sS/sT/sA/sW/sM	#scan types

# Evading Detection
-D [ip] 	#send with decoy IPs to blend in

Nmap -T0			#slow

nmap --spoof-mac dell 1.1.1.1

nmap --data-string “hello world”

nmap --data-length 48 	#append 48 bytes random

nmap --randomize-hosts	#random order

nmap --source-port 53 	#53,20 are commonly allowed

nmap --ttl 5		#time to live 5

nmap --badsum		#any response is from firewall or IDS, but may not respond

