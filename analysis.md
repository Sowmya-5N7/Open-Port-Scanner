## Scan Overview
''bash 
nmap -sS 192.168.129.0/24 -oN scan_results.txt where ->-sS is TCP SYN Scan which sends SYN Packets to check port status without completing TCP handshake Process.-> -oN scan_results.txt is output which saves the results in text format to scan_results.txt
