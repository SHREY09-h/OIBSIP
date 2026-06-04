# Task 2 - Basic Firewall Configuration with UFW

## Objective
Configure a basic firewall using UFW on Kali Linux.

## Tools Used
- Kali Linux
- UFW

## Commands Used

```bash
sudo ufw enable
sudo ufw allow ssh
sudo ufw deny http
sudo ufw status verbose
```

## Configuration
- SSH traffic was allowed on port 22.
- HTTP traffic was denied on port 80.

## Firewall Status

| Port | Action |
|------|---------|
| 22/tcp | ALLOW IN |
| 80/tcp | DENY IN |

## Files Included
- README.md
- ufw_configuration.sh
- Screenshots

## Demo Video Link

## Conclusion
The firewall was configured successfully using UFW to manage incoming traffic and improve system security.

## Author
DIYORA SHREYKUMAR ASHOKBHAI
