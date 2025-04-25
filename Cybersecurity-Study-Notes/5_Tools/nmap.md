# Nmap

## What is Nmap?
Nmap (Network Mapper) is a free and open-source tool used for network discovery and security auditing.

## Key Features
- Host discovery
- Port scanning
- OS detection
- Service/version detection
- Scriptable interaction using NSE (Nmap Scripting Engine)

## Basic Commands
- Scan a single IP: `nmap 192.168.1.1`
- Scan a range: `nmap 192.168.1.1-50`
- Scan with service/version detection: `nmap -sV 192.168.1.1`
- Scan with OS detection: `nmap -O 192.168.1.1`