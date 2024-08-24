Final Report: Video & Notes Walkthrough of All You've Learned

Diego Garcia
University of Advancing Technology
NTS442
Briant Becote
8/22/24



Final Report: Video & Notes Walkthrough of All You've Learned
The following document will be a collection of the total notes used throughout the class. The links will be reiterated in both hyperlink form and in the references tab where necessary. Appreciation is extended to other class peers who worked alongside me throughout this course particularly Mitchel Moss, and Ozzy James. 

NOTE: AS DOWNLOAD PRIVLAGES WERE NOT GRANTED IMAGES (USED IN NOTES) WAS NOT ABLE TO BE ATTATCHED, REFERENCE BELOW VIDEO:
https://youtu.be/wtmTp2WUch4 
—-----------------------------------------------------------------------------------------------------
John the ripper notes

John the ripper is used to unencrypt hashes of different kinds such as MD4 MD5 Sha1 and NTLM

The string is what is encrypted by a hashing algorithm 

MD5- the hash will be standard 32 characters
—------
P=polynomial time : longer a list is to go through the longer it would take to sort, not exponential
Np= Non-deterministic polynomial time: problems with solutions can be found very quickly. This does not mean the solution is easy but that there is an algorithm out there to check the solutions quickly (say with a rainbow table algorithm)
—--------
Book of possible passwords is called a - Dictionary
John the ripper makes use of a dictionary

To install on windows you must have the zip for jumboJohn which is most common
For everything else look below

—--------------------------------
—--------------------------------
John syntax

—------------
Hash identifier

—----------------
NTLM, NT used to mean new technology but became standard so sometimes is just called lm by windows
Dump the SAM database to get the NTLM hash, you can use the tool mimikatz

—-----------
Unshadow is a John command, helps you get passwords that are stored in /etc/shadow from linux
Unshadow (path to pass] [path to shadow] 
—----------
Word mangling, the act of replacing some characters in a word with numbers and symbols, ex include Theman THEman theMan (for the man), or more severely <00L6Uy (for coolguy)

Custom rules can be made for john dictionary additions in case of mangling with john.conf
—--------
Rar2john is another type of john tool for rar files which are kind like zip files  
—-------------------------------------------------------------------------------------------------------
Complete beginner pathway notes



man command is short for manual (ex man ssh)

searchsploit fuel cms   cam be used for finding exploits
Format - 
CVE-YEAR-NUMBER





LINUX FUNDAMENTALS







INTRODUCTORY NETWORKING







Nmap site and commands- https://nmap.org/book/nse-usage.html 



Enumeration try hack me definition- Enumeration is defined as "a process which establishes an active connection to the target hosts to discover potential attack vectors in the system, and the same can be used for further exploitation of the system." - Infosec Institute. It is a critical phase when considering how to enumerate and exploit a remote machine - as the information you will use to inform your attacks will come from this stage

WEB HACKING FUNDEMENTALS







Juice shop room- OWASP- utilizes burp suite and different query injections as a primary focus. Cross site scripting is also in occurrence 

Remote code execution- RCE


Php- 

Pickle rick- A good room for testing Query injection and file troubleshooting, particularly because the distinctive languages used for flags which allows steady progress. 

Cryptography-

Never use the force command for hashcat (leads to false positives)

WINDOWS EXPLORATION BASICS


Meterpriter commands



Nmap command

Gobuster

Introduction to Cyber Security


SECURITY ENGINEER





INTRO TO PEN TESTING 

CYBER DEFENSE

Mitre- https://engage.mitre.org/ 
Nessus- https://www.tenable.com/products/nessus 



References
CrackStation. (n.d.). Password cracking dictionary. CrackStation. https://crackstation.net/etworkChuck. (2021, March 30). Learn web hacking fundamentals. YouTube. https://youtu.be/iWoiwFRLV4IetworkChuck. (2021, March 30). Learn web hacking fundamentals. YouTube. https://youtu.be/iWoiwFRLV4I
Lyon, G. F. (n.d.). Using the Nmap scripting engine. Nmap. https://nmap.org/book/nse-usage.html
Here are the APA citations for the provided links:

1. **Linux Fundamentals:**
   - Simplilearn. (2020, November 2). *Linux fundamentals*. YouTube. https://youtu.be/kPylihJRG70
   - Simplilearn. (2020, November 9). *Linux fundamentals*. YouTube. https://youtu.be/7Zt2Mp2IeBI
   - Simplilearn. (2020, November 9). *Linux fundamentals*. YouTube. https://youtu.be/bwgaZCb2ft8

2. **Introductory Networking:**
   - Lyon, G. F. (n.d.). *Using the Nmap scripting engine*. Nmap. https://nmap.org/book/nse-usage.html

3. **Web Hacking Fundamentals:**
   - NetworkChuck. (2021, March 30). *Learn web hacking fundamentals*. YouTube. https://youtu.be/iWoiwFRLV4I
   - NetworkChuck. (2021, March 30). *Web hacking fundamentals*. YouTube. https://youtu.be/XZyapIKV3Rw
   - CrackStation. (n.d.). *Password cracking dictionary*. CrackStation. https://crackstation.net/

4. **Basic Computer Exploitation:**
   - NetworkChuck. (2020, September 7). *Computer exploitation basics*. YouTube. https://youtu.be/xl2Xx5YOKcI

5. **Intro to Cyber Security:**
   - National Cyber Security Centre. (2020, October 6). *Passwords, passwords everywhere*. https://www.ncsc.gov.uk/blog-post/passwords-passwords-everywhere

6. **Cyber Defense:**
   - MITRE Corporation. (n.d.). *Cyber defense knowledge base*. MITRE Engage. https://engage.mitre.org/
   - Tenable. (n.d.). *Nessus vulnerability assessment tool*. Tenable. https://www.tenable.com/products/nessus

These citations include the necessary details like author, date, title, source, and URLs as per APA format.
 MITRE Corporation. (n.d.). Cyber defense knowledge base. MITRE Engage. https://engage.mitre.org/
National Cyber Security Centre. (2020, October 6). Passwords, passwords everywhere. https://www.ncsc.gov.uk/blog-post/passwords-passwords-everywhere
NetworkChuck. (2020, September 7). Computer exploitation basics. YouTube. https://youtu.be/xl2Xx5YOKcI
NetworkChuck. (2021, March 30). Web hacking fundamentals. YouTube. https://youtu.be/XZyapIKV3Rw
NetworkChuck. (2021, March 30). Web hacking fundamentals. YouTube. https://youtu.be/XZyapIKV3Rw
Simplilearn. (2020, November 2). Linux fundamentals. YouTube. https://youtu.be/kPylihJRG70
Simplilearn. (2020, November 9). Linux fundamentals. YouTube. https://youtu.be/7Zt2Mp2IeBI

Tenable. (n.d.). Nessus vulnerability assessment tool. Tenable. https://www.tenable.com/products/nessus
Simplilearn. (2020, November 9). Linux fundamentals. YouTube. https://youtu.be/bwgaZCb2ft8
—-------------------------------------------------------------------------------------------------------------

Linux fundamentals
https://youtu.be/kPylihJRG70
https://youtu.be/7Zt2Mp2IeBI
https://youtu.be/bwgaZCb2ft8 
Introductory networking
https://nmap.org/book/nse-usage.html 
Web hacking fundamentals
https://youtu.be/iWoiwFRLV4I 
https://youtu.be/XZyapIKV3Rw 
https://crackstation.net/ 
Basic computer exploitation 
https://youtu.be/xl2Xx5YOKcI
Intro to cyber security
https://www.ncsc.gov.uk/blog-post/passwords-passwords-everywhere 
CYBER DEFENSE

Mitre- https://engage.mitre.org/ 
Nessus- https://www.tenable.com/products/nessus 



