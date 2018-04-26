# CyberSec_Week9

## Summary

### Honeypots Deployed
1 Honeypot Deployed: Dionaea

### Issues Encountered
One of the main issues that I encountered is not being able to log in to the honeypot server following the instructions from the course page. The first time I set up the honeypot following the instructions, there was no way to access the login of the honeypot. Tryiing to fix this, I attempted to reinstall the VM and ran into an error when trying to install mhn on the admin server. 

I then used Google Cloud to directly create an Ubuntu 14.04 VM and it ended up working. Using the newly created Ubuntu VM as the mhn server, I added the honeypot server from the assignment instructions and finally got the system to work.

### Data Collected
The data collected are as follows:

__TOP 5 Attacker IPs:__
1. 77.72.85.25 (134 attacks) Russia
2. 5.188.11.71 (70 attacks) Russia
3. 46.166.139.181 (66 attacks) Netherlands
4. 106.246.228.251 (58 attacks) South Korea
5. 5.188.11.91 (47 attacks) Russia

__TOP 5 Attacked Ports:__
1. 23 (244 times)
2. 3306 (157 times)
3. 445 (97 times)
4. 5060 (95 times)
5. 2000 (55 times)
