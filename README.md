# Elevate-Labs-Task-03

# Basic Vulnerability Scan (OpenVAS)

##  Objective
Perform a basic vulnerability scan on localhost using OpenVAS (Greenbone Security Assistant) to identify common security issues.

##  Tools Used
- OpenVAS (Community Edition) – Greenbone Security Assistant

##  Target
- Localhost (127.0.0.1)

##  Summary of Findings
1. **SSL/TLS: Report Weak Cipher Suites** – Medium risk  
2. **Weak MAC Algorithm(s) Supported (SSH)** – Low risk  
3. **Self-Signed SSL/TLS Certificate Detected** – Informational  
4. **Service & Version Enumeration** – Informational  

##  Recommendations
- Disable weak ciphers in SSL/TLS services.
- Harden SSH (`/etc/ssh/sshd_config`) by allowing only strong MACs and ciphers.
- Replace self-signed certificates with trusted CA-signed certificates.
- Keep system packages up to date.

##  Scan Results

<img width="1919" height="912" alt="Screenshot 2025-09-02 154240" src="https://github.com/user-attachments/assets/a5486775-8970-4a95-b09d-1d7baf4d3993" />


*Scanner:* Greenbone Security Assistant (OpenVAS)
