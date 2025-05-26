# Network Port Scanning Exercise

## Objective
Discover open ports on devices in my local network to understand network exposure.

## Tools Used
- Nmap (for network scanning)
- Wireshark (for packet analysis - optional)

## Methodology
1. Performed TCP SYN scan of my local subnet (192.168.1.0/24)
2. Analyzed results to identify open ports
3. Researched services running on discovered ports
4. Documented potential security risks

## Commands Executed
```bash
# Basic network scan
nmap -sS 192.168.217.128/24  -oN scan_results/scan.txt -oX scan_results/scan.html

# Service version detection
nmap -sV 192.168.217.128/24 
