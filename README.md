# ARPScanonLan

### Definition

```javascript  
  Arp-scan is a command-line tool for system discovery. 
  It constructs and sends ARP requests to the all IP addresses,  and displays any responses 
  that are received. It ask user to add to list when new device connect to network 
  or change its IP address.
```

### Requirements
```javascript
  pip install scapy
```

### How To Run Scan ?

Need to run the arpScan.py file with root privilages :

```javascript
  sudo python arpScan.py
```
And here's some code! :thumbsup:

```javascript
ans, unans = srp(Ether(dst="ff:ff:ff:ff:ff:ff")/ARP(pdst = ips),timeout=2)
```
