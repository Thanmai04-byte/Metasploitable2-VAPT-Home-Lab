# Metasploitable2-VAPT-Home-Lab
Beginner VAPT home lab using Kali Linux, Nmap and Metasploit Framework.
## Project Overview
This is my first hands-on Vulnerability Assessment and Penetration Testing (VAPT) project using Kali Linux and Metasploitable 2.
## Objective
To identify open ports, running services and vulnerabilities in an isolated virtual lab environment.
## Tools Used
- Kali Linux
- Metasploitable 2
- Nmap
- Metasploit Framework
- VirtualBox
## Practical Steps Performed
1. Set up Kali Linux and Metasploitable 2 virtual machines.
2. Identified the IP addresses of both machines.
3. Checked network connectivity using ping.
4. Performed host discovery using Nmap.
5. Scanned open ports and identified running services.
6. Identified FTP service running on port 21.
7. Detected the vsftpd 2.3.4 version.
8. Selected the relevant Metasploit module.
9. Configured RHOSTS and LHOST.
10. Tested the FTP backdoor vulnerability.
11. Successfully established a Meterpreter session.
12. Verified the session and analyzed the security impact.
## Vulnerability Identified
- Service: FTP
- Port: 21
- Version: vsftpd 2.3.4
- Vulnerability: Backdoor vulnerability
- CVE: CVE-2011-2523
## Security Recommendations
- Remove vulnerable software.
- Install updated and secure software.
- Disable unnecessary services.
- Restrict access using firewall rules.
- Monitor system activities.
## What I Learned
- Network reconnaissance
- Port scanning using Nmap
- Service and version detection
- Basic vulnerability assessment
- Exploitation testing using Metasploit
- Meterpreter session verification
- Security impact analysis
## Project Report
See `Project_1_hands_on.pdf` in this repository for detailed documentation and practical screenshots.
## Disclaimer
All testing was performed in my own authorized, isolated virtual lab using Metasploitable 2. No unauthorized systems were targeted.
