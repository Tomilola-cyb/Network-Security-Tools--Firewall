# Network-Security-Tools--Firewall
Network Security Tools Assignment
Overview
This project demonstrates the configurationof a basic firewall rule on a local server and the verification of that rule through connection testing.
Task Performed
1. Tool used: Uncomplicated Firewall (UFW) on Kali Linux.
2. Configuration: Enabled UFW.
   - Set a default deny policy for incoming traffic.
   - Created a specific rule to DENY traffic on PORT 80 (HTTP).
3. Verification: Used the 'curl' command to attempt a connection to the blocked port, confirming that the firewall successfully dropped the request.

Files in this Repository
/home/kali/firewall_config.txt
