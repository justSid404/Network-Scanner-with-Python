# Network-Scanner-with-Python
Scan your local network with a simple command using a Python script.

Pre-requisite Modules:
- argparse  (pip3 install argparse)
- Scapy     (pip3 install scapy)

Syntax:
networkScanner.py -t <IP address or Network address>

Example:
*input:*
>python3 networkScanner.py -t 192.168.1.1/24

*output*
_________________________________
IP Address      MAC Address
_________________________________
192.168.1.1     ff:ff:ff:ff:ff:ff
