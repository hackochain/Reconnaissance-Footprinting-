# Reconnaissance-Footprinting-
Footprinting is the first phase in ethical hacking, I explored Zenmap and GHDB, Learned 6 new commands that actively scans the IP network and produces the result and also I analyzed that Footprinting plays a vital role.

GHDB which is Google hacking database, An effective way to search for the desired output, It is also called as Google Dork.

PENETRATION TESTING REPORT

FOOTPRINTING & NETWORK SCANNING PHASES

W2-PM-FINAL | CYBERSECURITY |  NETWORKWALKS

Name: Yogavarshini R
Program/Batch	B084-Networkwalks
Date: 13 November 2026
Modules completed	:  W2-PM1 (Multiple Kali Tools)
                     W2-PM2 (GHDB)
                     W2-PM5 (Zenmap Scanning)
Client/Target :	1. Networkwalks (secured written permission already)


1. Liability Disclaimer

I have performed these activities only on the systems & devices where I had secured written permission or the devices/systems that I own myself. All these materials are for education and research purpose only. Do not use anything from here to break the law. The instructor, the authors and Networkwalks are not responsible for what you do with this knowledge. Every action you take is your own responsibility. Misuse can lead to criminal charges, heavy fines, loss of your job and a permanent record. In most countries unauthorised access is a crime even when nothing is damaged.

 2. Introduction
 
This report covers footprinting the networkwalks.com domain using multiple Kali Linux tools (W2-PM1) and scanning my own local network with Zenmap (W2-PM5). One module covers the footprinting phase and the other covers the scanning phase, so together they show how an attacker moves from gathering public information to mapping live hosts on a network. It is the Week 2 part of my ongoing internship program at Networkwalks.
All commands were run in Kali Linux (footprinting) and on a Windows PC with Zenmap installed (scanning). Every step below includes the exact command used, the result I observed, a screenshot as evidence, and a short note on why the finding matters from an attacker's point of view.


3. Tools Used

Kali Linux & Windows	Operating systems used for reconnaissance activities

WHOIS	-- Find domain registration details (owner, dates, name servers).
whatweb	-- Fingerprint web technologies (server, CMS, plugins, IP).
nslookup	-- Resolve the domain name to its IP address using DNS.
curl -I	-- Read the HTTP response headers of the website.
wafw00f	-- Detect whether a Web Application Firewall protects the site.
dnsrecon	-- Enumerate all DNS records (NS, MX, SPF, TXT, SRV).
Zenmap (Nmap GUI)	-- Scan the local subnet to find live hosts, IPs and MAC addresses.
Windows CMD	-- Local IP and MAC address identification

4. Zenmap – Network Scanning

Explored and worked with Zenmap, the graphical interface for Nmap.
Activities performed:
•	Explored the Zenmap interface.
•	Performed network scanning.
•	Identified live hosts in my local network.
•	Examined IP addresses and host information.
•	Understood basic network discovery.

5. GHDB – Google Hacking Database

Explored the Google Hacking Database (GHDB) and practised Google Dorking techniques.
Activities performed:
•	Explored different Google Dork queries.
•	Understood how search operators identify publicly indexed resources.
•	Identified search results containing publicly exposed webcam interfaces.
•	Studied potential security risks associated with exposed devices and misconfigurations.
Security Note: This activity was limited to educational research of publicly indexed results. No unauthorized access or interaction with third-party devices was performed.

6. Conclusion

Successfully completed Week 2 of my cybersecurity internship at Networkwalks.
This week's hands-on activities provided practical exposure to footprinting, network reconnaissance, network scanning, and Google Dorking. Working with Kali Linux tools and Zenmap helped strengthen my understanding of how security professionals gather information and identify potential security exposures.
I look forward to exploring more advanced cybersecurity concepts and tools in the upcoming weeks.


