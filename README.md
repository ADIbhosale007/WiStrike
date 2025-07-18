# WiStrike 
Wireless Penetration Testing Toolkit for Kali Linux

WiStrike is a powerful, beginner-friendly, and interactive Python-based toolkit built specifically for Kali Linux. It helps automate and simplify wireless network auditing and penetration testing tasks such as scanning, capturing handshakes, cracking Wi-Fi passwords, and performing WPS attacks.
This tool is designed only for ethical hacking, cybersecurity research, and educational use. Unauthorized use is strictly prohibited.

# Features:

1. Start or stop monitor mode on Wi-Fi interfaces.
2. Scan and list available Wi-Fi networks.
3. Capture WPA/WPA2 handshakes from target networks.
4. Crack captured handshakes using:
   - Default rockyou.txt wordlist
   - User-provided custom wordlist
   - Dynamically generated wordlist via crunch
5. Create your own password wordlists.
6. Perform WPS attacks using:
   - Reaver
   - Bully
   - Wifite (recommended)
   - PixieWPS
7. Scan for WPS-enabled networks.
8. Install and manage over 30 popular wireless hacking tools from within the script.

# Demo :
For a preview of what’s possible, check out this quick demo video:
<img width="988" height="568" alt="Screenshot 2025-07-18 142541" src="https://github.com/user-attachments/assets/194a97f6-3e02-4465-9068-62d98e557645" />
SOON VIDEO


# Requirements:

Ensure your system has Python 3 and a compatible wireless adapter that supports monitor mode and packet injection.

This tool runs best on Kali Linux and automatically installs the following (if not already available):

- aircrack-ng  
- crunch  
- reaver  
- pixiewps  
- bully  
- wifite  
- xterm  
- wordlists  
- airodump-ng  
- aireplay-ng  
- network-manager  

# Installation Steps:

1. Open a terminal and clone the project:
   git clone https:
   
   https://github.com/ADIbhosale007/WiStrike.git

3. Navigate into the project folder:
   
   cd WiStrike

5. Run the script:
   
   sudo python3 WiStrike.py

# How to Use:

When you run the script, you’ll see an interactive menu with the following options:

1. Start monitor mode  
2. Stop monitor mode  
3. Scan Networks  
4. Capture WPA/WPA2 Handshake  
5. Install Wireless Tools  
6. Crack Handshake with rockyou.txt  
7. Crack Handshake with custom wordlist  
8. Crack Handshake with generated wordlist  
9. Create your own wordlist  
10. Perform WPS Attacks (Reaver, Bully, PixieWPS, Wifite)  
11. Scan for WPS Networks  
0. About Me  
00. Exit  

Each option provides step-by-step prompts (like interface name, BSSID, channel, wordlist path, etc.) to complete the operation.

# About the Author:

Name: Aditya Bhosale  
Cybersecurity Researcher | 21 years old  
Passionate about ethical hacking and Wi-Fi security.  
LinkedIn: https://www.linkedin.com/in/aditya-bhosale-1683b2211

Motto: Sometimes you win by losing.

# Disclaimer:

This tool is for educational purposes and authorized testing only.  
Using this tool on networks you do not own or do not have permission to test is illegal and strictly prohibited. The developer holds no responsibility for misuse.

