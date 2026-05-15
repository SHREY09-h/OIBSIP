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
PORT     STATE SERVICE VERSION
8000/tcp open  http    SimpleHTTPServer 0.6 (Python 3.13.9)
```

## Explanation of Results

- Port 8000 was found open.
- The HTTP service was running on the open port.
- The detected service version was SimpleHTTPServer 0.6.
- Nmap scanned 1000 common TCP ports.
- 999 ports were closed, and only port 8000 was active.

## Significance of Open Port

| Port | Service | Significance |
|------|----------|--------------|
| 8000 | HTTP | Used for web communication and testing web applications |

## Conclusion
The network scan was successfully performed using Nmap. The scan identified an active HTTP service running on port 8000. This task demonstrates how Nmap can be used to detect open ports and services on a system.
