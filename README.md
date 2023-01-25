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
 

Also, check out this blog the Top Cyber Security Skills!

