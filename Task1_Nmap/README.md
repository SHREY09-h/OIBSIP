# Task 1 - Basic Network Scanning with Nmap

## Objective
The objective of this task is to perform a network scan using Nmap to identify open ports and services running on a local machine.

## Tools Used
- Kali Linux
- Nmap

## Commands Used

```bash
python3 -m http.server 8000
nmap -sV 127.0.0.1
```

## Scan Results

```bash
Starting Nmap 7.95 ( https://nmap.org ) at 2026-05-15
Nmap scan report for localhost (127.0.0.1)
Host is up (0.0000010s latency).

Not shown: 999 closed tcp ports (reset)

PORT     STATE SERVICE VERSION
8000/tcp open  http    SimpleHTTPServer 0.6 (Python 3.13.9)

Service detection performed.
```

## Findings and Port Significance

During the Nmap scan, one open port was identified on the local machine.

| Port | State | Service | Version | Significance |
|------|--------|----------|----------|--------------|
| 8000 | Open | HTTP | SimpleHTTPServer 0.6 | Port 8000 is commonly used for web development and testing web applications. The HTTP service allows communication between web servers and clients through a browser. |

### Additional Findings
- The host machine was active and reachable.
- Nmap scanned 1000 common TCP ports.
- 999 ports were closed.
- Only port 8000 was found open and running an HTTP service.

## Security Importance
Open ports can expose running services to a network. Identifying open ports helps security analysts detect unnecessary services and reduce potential security risks.

## Screenshots
Screenshots of the Nmap scan output are included in this repository.

## Files Included
- README.md
- nmap_scan_results.txt
- Screenshots of scan output

## Learning Outcome
Through this task, I learned:
- How to install and use Nmap
- How to scan a local machine
- How to identify open ports and running services
- The importance of open ports in cybersecurity

## Future Improvements
Future scans can include:
- Scanning remote systems in a controlled environment
- Detecting operating systems
- Performing advanced vulnerability assessments

## Conclusion
The network scan was successfully performed using Nmap. The scan identified an active HTTP service running on port 8000. This task demonstrates how Nmap can be used to detect open ports and services on a system.

## Author
DIYORA SHREYKUMAR ASHOKBHAI  
Security Analyst Intern - Oasis Infobyte
