Cybersecurity Internship - Week 1 Project

This repository contains the documentation and screenshots for my Week 1 tasks in the Cybersecurity Internship Program at NetworkWalks.

## 📁 1. Lab Setup (VirtualBox)
For this project, I successfully built a virtual cybersecurity lab environment using **Oracle VirtualBox**. 
**Steps completed:**
- **Network Configuration:** Created a NAT Network with the subnet `10.0.0.0/24` to ensure isolated communication.
- **Kali Linux Configuration:** Imported and configured Kali Linux, assigning it a static IP address of `10.0.0.3`. 
- **Connectivity Test:** Verified full internet access from the VM by successfully pinging Google's DNS (`8.8.8.8`).
- **Shared Folders:** Enabled a shared folder between the host machine and Kali Linux for easy file transfer.
- **Snapshot:** Took a VM snapshot (Lab Setup Complete) to preserve the working state for future tasks.

## 📁 2. Wireshark SOC Labs (Extra Project)
In addition to the lab setup, I completed 6 hands-on SOC (Security Operations Center) labs using Wireshark to practice real-world network analysis.
**Skills Practiced:**
1. Identifying an attacker's IP address (Port Scan detection).
2. Following TCP Streams to read plain-text conversations.
3. Finding hidden data in HTTP comments.
4. Extracting plain-text credentials from HTTP traffic.
5. Detecting a Brute Force attack on an FTP server.
6. Analyzing and replaying VoIP calls to identify a scammer.

*Note: All screenshots for these labs are organized inside the `wireshark-labs` folder for easy review.*
