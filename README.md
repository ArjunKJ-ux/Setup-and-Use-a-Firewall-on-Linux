# Setup-and-Use-a-Firewall-on-Linux
# Firewall Configuration with UFW

This repository documents my work on configuring a firewall using UFW on Kali Linux as part of a Cyber Security Internship project.

## Overview

- **Objective:**  
  Set up and test basic firewall rules to allow or block traffic.

- **Tools Used:**  
  - UFW (Uncomplicated Firewall) on Linux

## Steps I Followed

1. **Enable UFW:**  
   Enabled the firewall using `sudo ufw enable`.

2. **Check Status:**  
   Verified the active status using `sudo ufw status verbose`.

3. **Block Telnet (Port 23):**  
   Executed `sudo ufw deny 23` to block Telnet traffic.

4. **Allow SSH (Port 22):**  
   Executed `sudo ufw allow 22` to enable SSH access.

5. **Testing:**  
   Performed tests using `telnet` to ensure blocked ports are not accessible, and reviewed the current rules with `sudo ufw status numbered`.

## Files Included

- **firewall_log.txt:**  
  Contains the terminal output of all the UFW commands and connectivity tests.

- **firewall_screenshot.png:**  
  A screenshot demonstrating the firewall configuration (or Windows Firewall if applicable).

## Conclusion

This setup ensures that incoming traffic is fully controlled. Telnet is blocked to prevent unauthorized access, while SSH access is maintained for remote management.

