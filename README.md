# basic-port-scanner
# It scans a range of ports of given ip address.

#x-------------------------------------------------------------------------------------------------------------------x
# You can create your own port scanner with python. With which you can find open ports in your targeted ip address.
# The simple logic behind building a ports scanner is: 
 #             > a loop that can define a of range the ports.
 #             > socket library in python which has some inbuilt functions
 #             > and basic python syntax
#x-------------------------------------------------------------------------------------------------------------------x

# Features:
## This port scanner is faster than Nmap 

#  Limitations :
## Like the wellknown nmap it doesn't list out the versions and services running on the port.

# Usage:
## chmod +x scanner.py
## ./scanner.py ip start_port end_port
