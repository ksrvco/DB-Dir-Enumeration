# DB-Dir-Enumeration
Database for directory enumeration on webservers

# About:
One of the stages in web server penetration testing is finding directories on the web server. The more accurate the information gathering stage is, the better the performance of security researchers. There are various tools on the internet for finding files and directories on a web server, and many tools are available by default in the Kali Linux operating system. However, specialized and commercial penetration testing software such as Acunetix Web Vulnerability Scanner and HCL AppScan have their own databases for scanning and counting files on the web server. Access to their databases is not possible because their software is commercial and proprietary, and access to it is not available. To use it myself, I started monitoring the network traffic related to the activity of these software to see what paths they follow on the target web server and what files they check to make sure they exist. I was able to conduct this research and obtain a list of their databases from recording network traffic that they perform to scan files on the desired web server. Now we can use this list in tools that we have written ourselves or are available in open source tools.
This database can also be useful for red teams to use in their scenarios without the need to install the aforementioned software.
Over time, I will put the database of other software that exists for vulnerability scanning and are exclusive and I will update this repository.

# Last updates:
1. Acunetix Web Vulnerability Scanner 15.3.230123162
2. HCL AppScan 10.2.0.28254
