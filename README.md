# Open-Port-Scanner using Nmap

This project shows how to scan a network using nmap to find :
-  Open ports and active services
-  Service versions and operating system info
-  Possible security risks


## Target host

192.168.129.29 (IPV4 address)

### Use Cases
-  Identify Security risks
-  Network Troubleshooting
-  Pre Security Audit checks

## Quick Start
Run the scan with :
```bash
nmap -T4 -A -v 192.168.129.29
