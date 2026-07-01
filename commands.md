## Host Discovery
nmap -sn 192.168.56.0/24
## Port Scan
nmap 192.168.56.102
## Service Detection
nmap -sV 192.168.56.102
## OS Detection
sudo nmap -O 192.168.56.102
## Aggressive Scan
sudo nmap -A 192.168.56.102
## Save Results
- Text

  nmap -oN scan.txt 192.168.56.102
- XML

  nmap -oX scan.xml 192.168.56.102
- All formats

  nmap -oA fullscan 192.168.56.102
