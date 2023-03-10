# Cyber-Security-Questions-and-Answer

1. What is cryptography?

  Cryptography aids to secure information from third parties who are called adversaries. It allows only the sender and the recipient to access the data securely.
  
  
2. What is traceroute? Mention its uses.

  Traceroute is a network diagnostic tool. It helps track the route taken by a packet that is sent across the IP network. It shows the IP addresses of all the routers it pinged between the source and the destination.

Uses: 

It shows the time taken by the packet for each hop during the transmission. 
When the packet is lost during the transmission, the traceroute will identify where the point of failure is.

3. What is a firewall? Mention its uses.
A firewall is a network security device/system, which blocks malicious traffic such as hackers, worms, malware, and viruses to maintain data privacy.

Uses: 

It monitors the incoming and outgoing network traffic. It permits or allows only data packets that agree to the set of security rules.
It acts as a barrier between the internal network and the incoming traffic from external sources like the Internet.


4. What is a three-way handshake?
It is a process that happens in a TCP/IP network when you make a connection between a local host and the server. It is a three-step process to negotiate acknowledgment and synchronization of packets before communication starts. 

Step 1: The client makes a connection with the server with SYN.

Step 2: The server responds to the client request with SYN+ACK.

Step 3: The client acknowledges the server’s response with ACK, and the actual data transmission begins.

5. What is a response code? List them.
HTTP response codes indicate a server’s response when a client makes a request to the server. It shows whether an HTTP request is completed or not. 

1xx: Informational

The request is received, and the process is continuing. Some example codes are:

100 (continue)
101 (switching protocol)
102 (processing)
103 (early hints)
2xx: Success 

The action is received, understood, and accepted successfully. A few example codes for this are:

200 (OK)
202 (accepted)
205 (reset content)
208 (already reported)
3xx: Redirection 

To complete the request, further action is required to take place. Example codes:

300 (multiple choice)
302 (found)
308 (permanent redirect)
4xx: Client Error 

The request has incorrect syntax, or it is not fulfilled. Here are the example codes for this:

400 (bad request)
403 (forbidden)
404 (not found)
5xx: Server Error 

The server fails to complete a valid request. Example codes for this are:

500 (internal server error)
502 (bad gateway)
511 (network authentication required)
 
6. What is the CIA triad?
CIA Triad is a security model to ensure IT security. CIA stands for confidentiality, integrity, and availability.

Confidentiality: To protect sensitive information from unauthorized access.
Integrity: To protect data from deletion or modification by an unintended person.
Availability: To confirm the availability of the data whenever needed.


Also, check out this blog the Top Cyber Security Skills!

7. What are the common cyberattacks?
Here is a list of common cyberattacks aimed at inflicting damage to a system. 

Man in the Middle attack: The attacker puts himself in the communication between the sender and the receiver. This is done to eavesdrop and impersonate to steal data. 
Phishing: Here, the attacker will act as a trusted entity to perform malicious activities such as getting usernames, passwords, and credit card numbers.
Rogue Software: It is a fraudulent attack where the attacker fakes a virus on the target device and offers an anti-virus tool to remove the malware. This is done to install malicious software into the system. 
Malware: Malware is software that is designed to attack the target system. The software can be a virus, worm, ransomware, spyware, and so on.
Drive-by Downloads: The hacker takes advantage of the lack of updates on the OS, app, or browser, which automatically downloads malicious code to the system.
DDoS: This is done to overwhelm the target network with massive traffic, making it impossible for the website or the service to be operable.
Malvertising: Malvertising refers to the injections of maleficent code to legitimate advertising networks, which redirect users to unintended websites.
Password Attacks: As the name suggests, here, the cyber hacker cracks credentials like passwords.
Check out our blog on Cyber Security Tips and Best Practices to prevent Cyber Security attacks!

8. What is data leakage?
Data leakage means the unauthorized transmission of data from an organization to an external recipient. The mode of transmission can be electronic, physical, web, email, mobile data, and storage devices, such as USB keys, laptops, and optical media. 

Types of data leakage:

Accidental leakage: The authorized entity sends data to an unauthorized entity accidentally.
Malicious insiders: The authorized entity intentionally sends data to an unauthorized entity.
Electronic communication: Hackers make use of hacking tools to intrude the system.

9. Explain port scanning.
A port scan helps you determine the ports that are open, listening, or closed on a network. Administrators use this to test network security and the system’s firewall strength. For hackers, it is a popular reconnaissance tool to identify the weak point to break into a system.

Some of the common basic port scanning techniques are:

UDP
Ping scan
TCP connect
TCP half-open
Stealth scanning

10. Explain brute force attack and the ways to prevent it.
A brute force attack is a hack where the attacker tries to guess the target password by trial and error. It is mostly implemented with the help of automated software used to login with credentials.

Here are some ways to prevent a brute force attack:

Set a lengthy password
Set a high-complexity password
Set a limit for login failures

11. Explain the difference between hashing and encryption.
Hashing	Encryption
A one-way function where you cannot decrypt the original message	Encrypted data can be decrypted to the original text with a proper key
Used to verify data	Used to transmit data securely
Used to send files, passwords, etc. and to search	Used to transfer sensitive business information

12. What is the difference between vulnerability assessment (VA) and penetration testing (PT)?
Vulnerability Assessment (VA)	Penetration Testing (PT)
Identifies the vulnerabilities in a network	Identifies vulnerabilities to exploit them to penetrate the system
Tells how susceptible the network is	Tells whether the detected vulnerability is genuine
Conducted at regular intervals when there is a change in the system or network	Conducted annually when there are significant changes introduced into the system

13. Mention the steps to set up a firewall.
Following are the steps you have to follow to set up a firewall:

Username/password: Alter the default password of a firewall device.
Remote Administration: Always disable the Remote Administration feature.
Port Forward: For the web server, FTP, and other applications to work properly, configure appropriate ports.
DHCP Server: Disable the DHCP server when you install a firewall to avoid conflicts.
Logging: Enable logs to view the firewall troubleshoots and to view logs.
Policies: Configure strong security policies with the firewall.

14. What is SSL encryption?
Secure Socket Layer is a security protocol that is used for the purpose of encryption. It ensures privacy, data integrity, and authentication in the network like online transactions.


The following are the steps for setting up an SSL encryption: 

A browser connects to an SSL-secured web server.
The browser requests the server’s public key in exchange for its own private key.
If it is trustworthy, the browser requests to establish an encrypted connection with the web server.
The web server sends the acknowledgement to start an SSL encrypted connection.
SSL communication starts to take place between the browser and the web server.
Courses you may like


Want to know How to become a cyber security engineer in 2023? check this blog out!


15. What steps will you take to secure a server?
A server that is secured uses the Secure Socket Layer (SSL) protocol to encrypt and decrypt data to protect it from unauthorized access.

Below are the four steps to secure a server:

Step 1: Secure the root and administrator users with a password

Step 2: Create new users who will manage the system

Step 3: Do not give remote access to administrator/default root accounts

Step 4: Configure firewall rules for remote access



16. What is the difference between HIDS and NIDS?

Host Intrusion Detection System	Network Intrusion Detection System
Detects the attacks that involve hosts	Detects attacks that involve networks 
Analyzes what a particular host/application is doing	Examines the network traffic of all devices
Discovers hackers only after the machine is breached	Discovers hackers at the time they generate unauthorized attacks

17. Mention the difference between symmetric and asymmetric encryption.
Differentiator 	Symmetric Encryption	Asymmetric Encryption
Encryption Key	Only one key to encrypt and decrypt a message	Two different keys (public and private keys) to encrypt and decrypt the message
Speed of Execution	Encryption is faster and simple	Encryption is slower and complicated
Algorithms	RC4, AES, DES, and 3DES	RSA, Diffie-Hellman, and ECC
Usage 	For the transmission of large chunks of data	For smaller transmission to establish a secure connection prior to the actual data transfer


To Know More..
https://intellipaat.com/blog/interview-question/cyber-security-interview-questions/
