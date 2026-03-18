#  Nmap Network Scan Project

##  Objective
To perform network scanning and identify open ports, services, and vulnerabilities.

## 🛠 Tools Used
- Nmap
- Kali Linux

##  Methodology
1. Basic scan using -sV
2. Full scan using -A -p-
3. Vulnerability scan using NSE scripts

##  Commands Used
nmap -sV 127.0.0.1
nmap -A -p- 127.0.0.1
nmap --script=vuln 127.0.0.1

##  Findings
- Open ports detected
- Running services identified

##  Risks
- Exposure of services
- Potential vulnerabilities

##  Recommendations
- Close unused ports
- Keep system updated
- Use firewall

## Conclusion
This project demonstrates basic network reconnaissance using Nmap.
