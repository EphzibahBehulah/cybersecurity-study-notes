# Metasploit

## What is Metasploit?
Metasploit is a powerful penetration testing framework used to identify, exploit, and validate vulnerabilities.

## Key Features
- Pre-built exploits and payloads
- Easy integration with Nmap
- GUI and CLI interface
- Post-exploitation modules

## Common Workflow
1. **Start Metasploit Console**: `msfconsole`
2. **Search for exploit**: `search vsftpd`
3. **Use an exploit**: `use exploit/unix/ftp/vsftpd_234_backdoor`
4. **Set target and payload**
5. **Run exploit**: `exploit`