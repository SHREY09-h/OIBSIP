# Task 1 - Basic Network Scanning with Nmap

## Objective
Perform a network scan using Nmap to identify open ports and services.

## Tools Used
- Kali Linux
- Nmap

## Commands Used

```bash
python3 -m http.server 8000
nmap -sV 127.0.0.1
```

## Scan Result

| Port | State | Service | Version |
|------|--------|----------|----------|
| 8000 | Open | HTTP | SimpleHTTPServer 0.6 |

## Findings
- Port 8000 was open.
- HTTP service was running on the port.
- 999 TCP ports were closed.

## Significance of Open Port
Port 8000 is used for web communication and testing web applications.

## Files Included
- README.md
- nmap_scan_results.txt
- Screenshots

## Demo Video
https://drive.google.com/file/d/1KjZLR0FjavumANC8WARUNVpbwC9gGkTg/view?usp=drive_link

## Conclusion
The network scan was completed successfully using Nmap. The scan identified an active HTTP service running on port 8000.

## Author
DIYORA SHREY ASHOKBHAI
