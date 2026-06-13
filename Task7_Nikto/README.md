# Task 7 - Vulnerability Scanning with Nikto

## Objective

Perform a vulnerability scan on a web server using Nikto and identify potential security issues.

## Tools Used

* Kali Linux
* Nikto

## Commands Used

```bash
python3 -m http.server 8000
nikto -h http://127.0.0.1:8000
```

## Files Included

* README.md
* nikto_scan_results.txt
* Shrey_Task7_NiktoVersion.png
* Shrey_Task7_HTTPServer.png
* Shrey_Task7_ScanResult.png

## Findings

The Nikto scan identified the following:

* Missing X-Frame-Options header.
* Missing X-Content-Type-Options header.
* Directory listing was enabled.
* Server version information was exposed.
* User configuration files (.bashrc and .profile) were detected.

## Demo Video
https://drive.google.com/drive/u/1/folders/1086Zzw0r5wnHY8FwrxkdFmMPTYug3NF3

## Conclusion

Nikto successfully scanned the local web server running on port 8000 and identified several potential security issues. This task demonstrated how vulnerability scanning tools can be used to assess the security of web servers.

## Author

DIYORA SHREYKUMAR ASHOKBHAI

