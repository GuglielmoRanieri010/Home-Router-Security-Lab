# 🔒 My Home Router Security Project

## What I Did
I used Kali Linux in a virtual machine to test my home router's security. Here's my step-by-step process:

### 1. Setup
- Installed Kali Linux on VirtualBox
- Got all the tools ready

### 2. Finding Vulnerabilities
Used these tools to scan my router:
- **nmap** - Found open ports and services
- **dig** - Tested DNS settings  
- **slowhttptest** - Checked if router could handle many connections
- **hping3** - Tested network flooding protection

### 3. What I Found
My router had:
- DNS recursion enabled (could be used for attacks)
- Vulnerable to Slowloris attacks
- UPnP exposed (could open ports without permission)
- Old firmware with known issues

### 4. Creating the Script
With AI help, I made a script that combined all these attacks to test if my router could be taken offline.

### 5. Results
The script worked - my router crashed and all devices lost internet for a few minutes. Then I fixed the security issues.

## Important Note
This was done safely on my own home network in a test environment. No other networks were affected.

## What I Learned
- How to find security vulnerabilities
- Why router updates are important  
- How to protect home networks
- Basic scripting for security testing
