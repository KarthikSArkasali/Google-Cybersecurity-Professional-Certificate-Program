# Connect and Protect: Networks and Network Security

In this course, I have successfully completed advanced training in **Network security**, focusing on its critical role in addressing ongoing security threats and vulnerabilities. This training encompassed a detailed understanding of **network architecture** and the mechanisms employed to secure networks, including the analysis of **network protocols** and the vulnerabilities they may introduce during communication.

Key areas of expertise include the implementation of **firewalls** and other security measures to ensure reliable and secure network operations. I gained insights into various types of **network attacks** and effective techniques to secure compromised systems and devices. This involved examining how malicious actors exploit vulnerabilities in network infrastructure and applying strategies to identify and mitigate potential security risks.

Moreover, I developed proficiency in **network hardening practices**, which strengthen systems against intrusion methods and evolving threats. My training also emphasized addressing the unique security challenges associated with **cloud infrastructures**, leveraging advanced hardening techniques to enhance the overall resilience and integrity of network systems.

![Course 6 Sound the Alarm Detection   Response Certificate (AA6F5MGM4PZB)_page-0001](https://github.com/user-attachments/assets/86cfd9ca-24d0-46d8-9878-43462b3cccb3)

# Network

A network is a collection of interconnected devices, such as computers, servers, routers, and switches, that communicate with one another to share resources and data. 

Devices can communicate on two types of networks: a local area network, also known as a LAN, and a wide area network, also known as a WAN.

* A **local area network**, or LAN, spans a small area like an office building, a school, or a home. For example, when a personal device like your cell phone or tablet connects to the WIFI in your house, they form a LAN. The LAN then connects to the internet.

* A **wide area network** or WAN spans a large geographical area like a city, state, or country. You can think of the internet as one big WAN. An employee of a company in San Francisco can communicate and share resources with another employee in Dublin, Ireland over the WAN.

**Network devices**

Network devices are hardware components that connect and manage communication between devices within a network. They play a crucial role in enabling data transfer, resource sharing, and network security. 

![Device types](https://github.com/user-attachments/assets/379fad9b-ae9f-4e73-9cc4-8491e8771fe4)

**Firewall**

**Firewalls** are critical network security devices designed to monitor and control traffic entering or leaving a network. Acting as the first line of defense, firewalls enforce security policies by restricting or allowing specific incoming and outgoing network traffic based on an organization's predefined security rules.

Typically, firewalls are strategically placed between the secured, controlled internal network and untrusted external resources, such as the internet. This positioning helps to prevent unauthorized access while permitting legitimate communication.

It is important to note, however, that firewalls are just one layer of defense within a broader cybersecurity framework. For comprehensive protection, they should be used in conjunction with other security measures, such as intrusion detection systems, encryption, and robust user authentication.

There are two main categories of firewalls.

* **Stateless:** A class of firewall that operates based on predefined rules and does not keep track of information from data packets

* **Stateful:** A class of firewall that keeps track of information passing through it and proactively filters out threats. Unlike stateless firewalls, which require rules to be configured in two directions, a 
                stateful firewall only requires a rule in one direction. This is because it uses a "state table" to track connections, so it can match return traffic to an existing session 

**Next generation firewalls (NGFWs)** are the most technologically advanced firewall protection. They exceed the security offered by stateful firewalls because they include deep packet inspection (a kind of packet sniffing that examines data packets and takes actions if threats exist) and intrusion prevention features that detect security threats and notify firewall administrators. NGFWs can inspect traffic at the application layer of the TCP/IP model and are typically application aware. Unlike traditional firewalls that block traffic based on IP address and ports, NGFWs rules can be configured to block or allow traffic based on the application. Some NGFWs have additional features like Malware Sandboxing, Network Anti-Virus, and URL and DNS Filtering.  

**Servers**

**Servers** are essential components of a network, providing information and services to devices such as computers, smartphones, and smart home devices. These connected devices, referred to as clients, rely on servers to fulfill their requests. This interaction follows the client-server model, a widely used networking structure where clients send requests to servers, and servers process and respond to those requests.

![Server](https://github.com/user-attachments/assets/c034e1cc-66cb-4019-9a2b-8df427a0ec63)

Servers perform a variety of critical tasks, enabling smooth operations across networks. Examples include:

* **DNS Servers:** Resolve domain names to IP addresses, enabling users to access websites using easily remembered names instead of numerical addresses.* 
* **File Servers:** Store and manage files, allowing clients to upload, retrieve, and share data seamlessly across a network.
* **Mail Servers:** Manage and organize email communication for organizations, ensuring reliable delivery and retrieval of messages.

**Hubs and switches**

Hubs and switches both direct traffic on a local network. A **Hub** is a device that provides a common point of connection for all devices directly connected to it. Hubs additionally repeat all information out to all ports. From a security perspective, this makes hubs vulnerable to eavesdropping. For this reason, hubs are not used as often on modern networks; most organizations use switches instead. Hubs are more commonly used for a limited network setup like a home office. 

**Switches** are the preferred choice for most networks. A switch forwards packets between devices directly connected to it. They analyze the destination address of each data packet and send it to the intended device. Switches maintain a MAC address table that matches MAC addresses of devices on the network to port numbers on the switch and forwards incoming data packets according to the destination MAC address. Switches are a part of the data link layer in the TCP/IP model. Overall, switches improve performance and security.

**Routers**

**Routers** connect networks and direct traffic, based on the IP address of the destination network. Routers allow devices on different networks to communicate with each other. In the TCP/IP model, routers are a part of the network layer. The IP address of the destination network is contained in the IP header. The router reads the IP header information and forwards the packet to the next router on the path to the destination. This continues until the packet reaches the destination network. Routers can also include a firewall feature that allows or blocks incoming traffic based on information in the transmission. This stops malicious traffic from entering the private network and damaging the local area network.

**Modems**  

**Modems** usually connect your home or office with an internet service provider (ISP). ISPs provide internet connectivity via telephone lines or coaxial cables. Modems receive transmissions or digital signals from the internet and translate them into analog signals that can travel through the physical connection provided by your ISP. Usually, modems connect to a router that takes the decoded transmissions and sends them on to the local network.

![Modem](https://github.com/user-attachments/assets/b8226d84-321f-4440-9026-fdfb93c42018)

**wireless access points**

A **Wireless access point** sends and receives digital signals over radio waves creating a wireless network. Devices with wireless adapters connect to the access point using Wi-Fi. **Wi-Fi** refers to a set of standards that are used by network devices to communicate wirelessly. Wireless access points and the devices connected to them use Wi-Fi protocols to send data through radio waves where they are sent to routers and switches and directed along the path to their final destination.

![WAP](https://github.com/user-attachments/assets/cbf29011-ef89-48dd-a5e9-587286d9f903)

**Cloud computing** is the practice of using remote servers, applications, and network services that are hosted on the internet instead of on local physical devices.

A **cloud network** is a collection of servers or computers that stores resources and data in a remote data center that can be accessed via the internet. Because companies don't house the servers at their physical location, these servers are referred to as being "in the cloud".

A **cloud service provider (CSP)** is a company that offers cloud computing services. These companies own large data centers in locations around the globe that house millions of servers. Data centers provide technology services, such as storage, and compute at such a large scale that they can sell their services to other companies for a fee. Companies can pay for the storage and services they need and consume them through the CSP’s application programming interface (API) or web console.

CSPs provide three main categories of services:

* **Software as a service (SaaS)** refers to software suites operated by the CSP that a company can use remotely without hosting the software. 

* **Infrastructure as a service (IaaS)** refers to the use of virtual computer components offered by the CSP. These include virtual containers and storage that are configured remotely through the CSP’s API or web console. Cloud-compute and storage services can be used to operate existing applications and other technology workloads without significant modifications. Existing applications can be modified to take advantage of the availability, performance, and security features that are unique to cloud provider services.

* **Platform as a service (PaaS)** refers to tools that application developers can use to design custom applications for their company. Custom applications are designed and accessed in the cloud and used for a company’s specific business needs.

![iass-paas-and-saas](https://github.com/user-attachments/assets/4b75f31e-eec7-4dff-bd48-d37039b5de09)

# The TCP/IP model

The **TCP/IP model** is a framework used to visualize how data is organized and transmitted across a network. This model helps network engineers and network security analysts conceptualize processes on the network and communicate where disruptions or security threats occur. 

The TCP/IP model has four layers: the network access layer, internet layer, transport layer, and application layer. When troubleshooting issues on the network, security professionals can analyze which layers were impacted by an attack based on what processes were involved in an incident. 

![TCP IP](https://github.com/user-attachments/assets/bb3f81aa-cad5-49d8-89da-9759651cbe4f)

The four layers of the TCP/IP model labeled application layer, transport layer, internet layer, and network access layer

**1. Network access layer** 
The network access layer, sometimes called the data link layer, deals with the creation of data packets and their transmission across a network. This layer corresponds to the physical hardware involved in network transmission. Hubs, modems, cables, and wiring are all considered part of this layer. The address resolution protocol (ARP) is part of the network access layer. Since MAC addresses are used to identify hosts on the same physical network, ARP is needed to map IP addresses to MAC addresses for local network communication.

**2. Internet layer**
The internet layer, sometimes referred to as the network layer, is responsible for ensuring the delivery to the destination host, which potentially resides on a different network. It ensures IP addresses are attached to data packets to indicate the location of the sender and receiver. The internet layer also determines which protocol is responsible for delivering the data packets and ensures the delivery to the destination host. Here are some of the common protocols that operate at the internet layer:

   * **Internet Protocol (IP)**. IP sends the data packets to the correct destination and relies on the Transmission Control Protocol/User Datagram Protocol (TCP/UDP) to deliver them to the corresponding service. IP packets allow communication between two networks. They are routed from the sending network to the receiving network. TCP in particular retransmits any data that is lost or corrupt.

   * **Internet Control Message Protocol (ICMP)**. The ICMP shares error information and status updates of data packets. This is useful for detecting and troubleshooting network errors. The ICMP reports information about packets that were dropped or that disappeared in transit, issues with network connectivity, and packets redirected to other routers.

**3. Transport layer**
The transport layer is responsible for delivering data between two systems or networks and includes protocols to control the flow of traffic across a network. TCP and UDP are the two transport protocols that occur at this layer. 

  * **Transmission Control Protocol**
The Transmission Control Protocol (TCP) is an internet communication protocol that allows two devices to form a connection and stream data. It ensures that data is reliably transmitted to the destination service. TCP contains the port number of the intended destination service, which resides in the TCP header of a TCP/IP packet.

  * **User Datagram Protocol**
The User Datagram Protocol (UDP) is a connectionless protocol that does not establish a connection between devices before transmissions. It is used by applications that are not concerned with the reliability of the transmission. Data sent over UDP is not tracked as extensively as data sent using TCP. Because UDP does not establish network connections, it is used mostly for performance sensitive applications that operate in real time, such as video streaming.

**4. Application layer**
The application layer in the TCP/IP model is similar to the application, presentation, and session layers of the OSI model. The application layer is responsible for making network requests or responding to requests. This layer defines which internet services and applications any user can access. Protocols in the application layer determine how the data packets will interact with receiving devices. Some common protocols used on this layer are: 

* Hypertext transfer protocol (HTTP)
* Simple mail transfer protocol (SMTP)
* Secure shell (SSH)
* File transfer protocol (FTP)
* Domain name system (DNS)

**TCP/IP model versus OSI model**

The TCP/IP model next to the OSI model
The OSI visually organizes network protocols into different layers. Network professionals often use this model to communicate with each other about potential sources of problems or security threats when they occur. 

![TCP-vs-OSI](https://github.com/user-attachments/assets/ccf3b9fe-8435-489b-abd5-9c40c9006125)

The TCP/IP model combines multiple layers of the OSI model. There are many similarities between the two models. Both models define standards for networking and divide the network communication process into different layers. The TCP/IP model is a simplified version of the OSI model.

# The OSI model

The **OSI model** is a standardized concept that describes the seven layers computers use to communicate and send data over the network. Network and security professionals often use this model to communicate with each other about potential sources of problems or security threats when they occur.

The seven layers of the OSI model labeled application, presentation, session, transport, network, data link, and physical

<img width="1263" alt="OSI-Model" src="https://github.com/user-attachments/assets/f42fa0e8-9ee0-4a71-a5df-4c8b74b33689">

Some organizations rely heavily on the TCP/IP model, while others prefer to use the OSI model. As a security analyst, it’s important to be familiar with both models. Both the TCP/IP and OSI models are useful for understanding how networks work. 

**Layer 7: Application layer**
The application layer includes processes that directly involve the everyday user. This layer includes all of the networking protocols that software applications use to connect a user to the internet. This characteristic is the identifying feature of the application layer—user connection to the internet via applications and requests.

An **example** of a type of communication that happens at the application layer is using a web browser. The internet browser uses HTTP or HTTPS to send and receive information from the website server. The email application uses simple mail transfer protocol (SMTP) to send and receive email information. Also, web browsers use the domain name system (DNS) protocol to translate website domain names into IP addresses which identify the web server that hosts the information for the website. 

**Layer 6: Presentation layer**
Functions at the presentation layer involve data translation and encryption for the network. This layer adds to and replaces data with formats that can be understood by applications (layer 7) on both sending and receiving systems. Formats at the user end may be different from those of the receiving system. Processes at the presentation layer require the use of a standardized format.

Some formatting functions that occur at layer 6 include encryption, compression, and confirmation that the character code set can be interpreted on the receiving system. One example of encryption that takes place at this layer is SSL, which encrypts data between web servers and browsers as part of websites with HTTPS.

**Layer 5: Session layer**
A session describes when a connection is established between two devices. An open session allows the devices to communicate with each other. Session layer protocols keep the session open while data is being transferred and terminate the session once the transmission is complete. 

The session layer is also responsible for activities such as authentication, reconnection, and setting checkpoints during a data transfer. If a session is interrupted, checkpoints ensure that the transmission picks up at the last session checkpoint when the connection resumes. Sessions include a request and response between applications. Functions in the session layer respond to requests for service from processes in the presentation layer (layer 6) and send requests for services to the transport layer (layer 4).

**Layer 4: Transport layer**
The transport layer is responsible for delivering data between devices. This layer also handles the speed of data transfer, flow of the transfer, and breaking data down into smaller segments to make them easier to transport. Segmentation is the process of dividing up a large data transmission into smaller pieces that can be processed by the receiving system. These segments need to be reassembled at their destination so they can be processed at the session layer (layer 5). The speed and rate of the transmission also has to match the connection speed of the destination system. TCP and UDP are transport layer protocols. 

**Layer 3: Network layer**
The network layer oversees receiving the frames from the data link layer (layer 2) and delivers them to the intended destination. The intended destination can be found based on the address that resides in the frame of the data packets. Data packets allow communication between two networks. These packets include IP addresses that tell routers where to send them. They are routed from the sending network to the receiving network. 

**Layer 2: Data link layer**
The data link layer organizes sending and receiving data packets within a single network. The data link layer is home to switches on the local network and network interface cards on local devices.

Protocols like network control protocol (NCP), high-level data link control (HDLC), and synchronous data link control protocol (SDLC) are used at the data link layer.

**Layer 1: Physical layer**
As the name suggests, the physical layer corresponds to the physical hardware involved in network transmission. Hubs, modems, and the cables and wiring that connect them are all considered part of the physical layer. To travel across an ethernet or coaxial cable, a data packet needs to be translated into a stream of 0s and 1s. The stream of 0s and 1s are sent across the physical wiring and cables, received, and then passed on to higher levels of the OSI model.

# Format of an IPv4 packet

![IP-packet-header-and-data-final](https://github.com/user-attachments/assets/4a2eecd7-a41f-4d5b-8f63-09821b88138f)

* An IPv4 header format is determined by the IPv4 protocol and includes the IP routing information that devices use to direct the packet. The size of the IPv4 header ranges from 20 to 60 bytes. The first 20 bytes are a fixed set of information containing data such as the source and destination IP address, header length, and total length of the packet. The last set of bytes can range from 0 to 40 and consists of the options field.

* The length of the data section of an IPv4 packet can vary greatly in size. However, the maximum possible size of an IPv4 packet is 65,535 bytes. It contains the message being transferred over the internet, like website information or email text.

![Pv4-packet-header-14-field](https://github.com/user-attachments/assets/f69d97fa-c922-43ad-8320-e2cee0cdc90b)

There are 13 fields within the header of an IPv4 packet:

* **Version (VER):** This 4 bit component tells receiving devices what protocol the packet is using. The packet used in the illustration above is an IPv4 packet.

* **IP Header Length (HLEN or IHL):** HLEN is the packet’s header length. This value indicates where the packet header ends and the data segment begins. 

* **Type of Service (ToS):** Routers prioritize packets for delivery to maintain quality of service on the network. The ToS field provides the router with this information.

* **Total Length:** This field communicates the total length of the entire IP packet, including the header and data. The maximum size of an IPv4 packet is 65,535 bytes.

* **Identification:** IPv4 packets can be up to 65, 535 bytes, but most networks have a smaller limit. In these cases, the packets are divided, or fragmented, into smaller IP packets. The identification field 
  provides a unique identifier for all the fragments of the original IP packet so that they can be reassembled once they reach their destination.

* **Flags:** This field provides the routing device with more information about whether the original packet has been fragmented and if there are more fragments in transit.

* **Fragmentation Offset:** The fragment offset field tells routing devices where in the original packet the fragment belongs.

* **Time to Live (TTL):** TTL prevents data packets from being forwarded by routers indefinitely. It contains a counter that is set by the source. The counter is decremented by one as it passes through each 
  router along its path. When the TTL counter reaches zero, the router currently holding the packet will discard the packet and return an ICMP Time Exceeded error message to the sender. 

* **Protocol:** The protocol field tells the receiving device which protocol will be used for the data portion of the packet.

* **Header Checksum:** The header checksum field contains a checksum that can be used to detect corruption of the IP header in transit. Corrupted packets are discarded.

* **Source IP Address:** The source IP address is the IPv4 address of the sending device.

* **Destination IP Address:** The destination IP address is the IPv4 address of the destination device.

* **Options:** The options field allows for security options to be applied to the packet if the HLEN value is greater than five. The field communicates these options to the routing devices.

# Difference between IPv4 and IPv6

As the internet grew, IPv4 addresses became insufficient, leading to IPv4 address exhaustion. To address this, IPv6 was developed, offering significantly more addresses and other improvements.

<img width="1175" alt="IPv4-and-IPv6" src="https://github.com/user-attachments/assets/47e51efe-0d4d-4059-857d-3122bdb5a495">

Key Differences Between IPv4 and IPv6
Address Format:

**IPv4:** Four decimal numbers (0–255) separated by periods (e.g., 198.51.100.0). Supports ~4.3 billion addresses.
**IPv6:** Eight hexadecimal numbers (up to four digits each) separated by colons (e.g., 2002:0db8::ff21:0023:1234). Supports ~340 undecillion addresses.
          Packet Header: IPv6 headers are simpler than IPv4, omitting fields like IHL and Flags while adding the Flow Label field for improved routing efficiency.
**Security and Efficiency:** IPv6 offers better routing, prevents private address collisions, and supports end-to-end encryption more natively.

# Network Address Translation (NAT)

Network Address Translation (NAT) enables devices on a local network with private IP addresses to communicate with the public internet using a shared public IP address. A router replaces the private source IP address in outgoing messages with its public IP and reverses the process for incoming responses. NAT operates at the Internet and Transport layers of the TCP/IP model and requires specific configuration on routers or firewalls.

|   Private IP Addresses    |  Public IP Addresses | 
| :----                     |   :----              |
|  Assigned by the router    |  Assigned by ISP and IANA  |
|  Unique only within private network    |  Unique address in global internet |
|  No cost to use    |  Costs to lease a public IP address  |
|  Address ranges:    |  Assignable address ranges:   |
|     * 10.0.0.0-10.255.255.255<br> * 172.16.0.0-172.31.255.255<br> * 192.168.0.0-192.168.255.255 |     * 1.0.0.0-9.255.255.255<br> * 11.0.0.0-126.255.255.255<br> * 128.0.0.0-172.15.255.255<br> * 192.169.0.0-233.255.255.255|  

**Dynamic Host Configuration Protocol (DHCP)**
DHCP is an application layer protocol that automatically assigns IP addresses, DNS server addresses, and default gateway information to devices on a network. For example, when you connect your phone to a Wi-Fi network, DHCP assigns it an IP address. DHCP servers use UDP port 67, and clients use UDP port 68.

**Address Resolution Protocol (ARP)**
ARP resolves an IP address to a MAC address within a local network. For instance, when your computer sends data to a printer on the same network, ARP ensures the data reaches the correct hardware. Devices maintain an ARP cache for quick reference. ARP operates at the Network Access Layer and does not use port numbers.

**Telnet and Secure Shell (SSH)**
* **Telnet:** A protocol to connect to remote systems via command-line. For example, a network admin might use Telnet to configure a switch. However, Telnet is insecure as it transmits data in plaintext over 
              TCP port 23.
* **SSH:** A secure alternative to Telnet that encrypts communication, ideal for managing servers remotely. SSH uses TCP port 22.
  
**Email Protocols**
* **Post Office Protocol (POP):** Downloads email to a device, often deleting it from the server. For example, using a POP3 email client downloads messages locally, restricting access to other devices. It uses 
                                  TCP/UDP port 110 (unencrypted) and 995 (encrypted).
* **Internet Message Access Protocol (IMAP):** Keeps email on the server, allowing access from multiple devices (e.g., syncing email across a phone and laptop). It uses TCP port 143 (unencrypted) and 993 
                                             (encrypted).
* **Simple Mail Transfer Protocol (SMTP):** Sends and routes email. For example, sending an email from Gmail uses SMTP. It operates on TCP/UDP port 25 (unencrypted) and 587 (encrypted).

**Internet Message Access Protocol (IMAP)**
IMAP is used for incoming email. It downloads the headers of emails and the message content. The content also remains on the email server, which allows users to access their email from multiple devices. IMAP uses TCP port 143 for unencrypted email and TCP port 993 over the TLS protocol. Using IMAP allows users to partially read email before it is finished downloading. Since the mail is kept on the mail server, it allows a user to sync emails across multiple devices. 

**Simple Mail Transfer Protocol**
Simple Mail Transfer Protocol (SMTP) is used to transmit and route email from the sender to the recipient’s address. SMTP works with Message Transfer Agent (MTA) software, which searches DNS servers to resolve email addresses to IP addresses, to ensure emails reach their intended destination. SMTP uses TCP/UDP port 25 for unencrypted emails and TCP/UDP port 587 using TLS for encrypted emails. The TCP port 25 is often used by high-volume spam. SMTP helps to filter out spam by regulating how many emails a source can send at a time.

**Protocols and port numbers**
Remember that port numbers are used by network devices to determine what should be done with the information contained in each data packet once they reach their destination. Firewalls can filter out unwanted traffic based on port numbers. For example, an organization may configure a firewall to only allow access to TCP port 995 (POP3) by IP addresses belonging to the organization.

As a security analyst, you will need to know about many of the protocols and port numbers mentioned in this course. They may be used to determine your technical knowledge in interviews, so it’s a good idea to memorize them. You will also learn about new protocols on the job in a security position.

|   Protocols    |  Ports | 
| :----                     |   :----              |
| DHCP   |  UDP port 67 (servers)<br>UDP port 68 (clients) |
|  ARP   |  none |
|  Telnet    |  TCP port 23  |
|  SSH  |  	TCP port 22   |
|   POP3 |   TCP/UDP port 110 (unencrypted)<br> TCP/UDP port 995 (encrypted, SSL/TLS) |
|   IMAP   |   TCP port 143 (unencrypted)<br> TCP port 993 (encrypted, SSL/TLS)  |
|   SMTP    | TCP/UDP Port 25 (unencrypted)| 
|     SMTPS      |    TCP/UDP port 587 (encrypted, TLS) |

**Proxy servers**
A proxy server is another way to add security to your private network. Proxy servers utilize network address translation (NAT) to serve as a barrier between clients on the network and external threats. Forward proxies handle queries from internal clients when they access resources external to the network. Reverse proxies function opposite of forward proxies; they handle requests from external systems to services on the internal network. Some proxy servers can also be configured with rules, like a firewall.  For example, you can create filters to block websites identified as containing malware.

**Virtual Private Network**

A VPN, or virtual private network, is a network security service that changes your public IP address and hides your virtual location so that you can keep your data private when you’re using a public network like the internet. VPNs provide a server that acts as a gateway between a computer and the internet. This server creates a path similar to a virtual tunnel that hides the computer’s IP address and encrypts the data in transit to the internet. The main purpose of a VPN is to create a secure connection between a computer and a network. Additionally, a VPN allows trusted connections to be established on non-trusted networks.

* **Remote access** 
Individual users use **Remote access** VPNs to establish a connection between a personal device and a VPN server. Remote access VPNs encrypt data sent or received through a personal device. The connection between the user and the remote access VPN is established through the internet.

* **Site-to-site VPN**

Enterprises use **Site-to-site** VPNs largely to extend their network to other networks and locations. This is particularly useful for organizations that have many offices across the globe. IPSec is commonly used in site-to-site VPNs to create an encrypted tunnel between the primary network and the remote network. One disadvantage of site-to-site VPNs is how complex they can be to configure and manage compared to remote VPNs.

* **WireGuard VPN**
WireGuard is a high-speed VPN protocol, with advanced encryption, to protect users when they are accessing the internet. It’s designed to be simple to set up and maintain. WireGuard can be used for both site-to-site connection and client-server connections. WireGuard is relatively newer than IPSec, and is used by many people due to the fact that its download speed is enhanced by using fewer lines of code. WireGuard is also open source, which makes it easier for users to deploy and debug. This protocol is useful for processes that require faster download speeds, such as streaming video content or downloading large files.

* **IPSec VPN**
IPSec is another VPN protocol that may be used to set up VPNs. Most VPN providers use IPSec to encrypt and authenticate data packets in order to establish secure, encrypted connections. Since IPSec is one of the earlier VPN protocols, many operating systems support IPSec from VPN providers.

Although IPSec and WireGuard are both VPN protocols, IPSec is older and more complex than WireGuard. Some clients may prefer IPSec due to its longer history of use, extensive security testing, and widespread adoption. However, others may prefer WireGuard because of its potential for better performance and simpler configuration.

# Portfolio #1

**Activity Overview**

In this activity, you will analyze DNS and ICMP traffic in transit using data from a network protocol analyzer tool. You will identify which network protocol was utilized in assessment of the cybersecurity incident. 

In the internet layer of the TCP/IP model, the IP formats data packets into IP datagrams. The information provided in the datagram of an IP packet can provide security analysts with insight into suspicious data packets in transit.

Knowing how to identify potentially malicious traffic on a network can help cybersecurity analysts assess security risks on a network and reinforce network security.

**Part-1: Analyze network layer communication**

**Scenario**

Review the scenario below. Then complete the step-by-step instructions.

You are a cybersecurity analyst working at a company that specializes in providing IT consultant services. Several customers contacted your company to report that they were not able to access the company website www.yummyrecipesforme.com, and saw the error “destination port unreachable” after waiting for the page to load. 

You are tasked with analyzing the situation and determining which network protocol was affected during this incident. To start, you visit the website and you also receive the error “destination port unreachable.” Next, you load your network analyzer tool, tcpdump, and load the webpage again. This time, you receive a lot of packets in your network analyzer. The analyzer shows that when you send UDP packets and receive an ICMP response returned to your host, the results contain an error message: “udp port 53 unreachable.

![DNS](https://github.com/user-attachments/assets/8927b958-6b03-4ee1-aa1a-5d2b90e51b76)

In the DNS and ICMP log, you find the following information:

**1.** In the first two lines of the log file, you see the initial outgoing request from your computer to the DNS server requesting the IP address of yummyrecipesforme.com. This request is sent in a UDP packet.
**2.** Next you find timestamps that indicate when the event happened. In the log, this is the first sequence of numbers displayed. For example: 13:24:32.192571. This displays the time 1:24 p.m., 32.192571 
        seconds.
**3.** The source and destination IP address is next. In the error log, this information is displayed as: 192.51.100.15.52444 > 203.0.113.2.domain. The IP address to the left of the greater than (>) symbol is 
       the source address. In this example, the source is your computer’s IP address. The IP address to the right of the greater than (>) symbol is the destination IP address. In this case, it is the IP address 
       for the DNS server: 203.0.113.2.domain

**4.** The second and third lines of the log show the response to your initial ICMP request packet. In this case, the ICMP 203.0.113.2 line is the start of the error message indicating that the ICMP packet was 
       undeliverable to the port of the DNS server.

**5.** Next are the protocol and port number, which displays which protocol was used to handle communications and which port it was delivered to. In the error log, this appears as: udp port 53 unreachable. This 
       means that the UDP protocol was used to request a domain name resolution using the address of the DNS server over port 53. Port 53, which aligns to the .domain extension in 203.0.113.2.domain, is a well- 
       known port for DNS service. The word “unreachable” in the message indicates the message did not go through to the DNS server. Your browser was not able to obtain the IP address for yummyrecipesforme.com, 
       which it needs to access the website because no service was listening on the receiving DNS port as indicated by the ICMP error message “udp port 53 unreachable.”

**6.** The remaining lines in the log indicate that ICMP packets were sent two more times, but the same delivery error was received both times. 

**Provided Supporting Documents**

[Portfolio (Part-1) Cybersecurity incident report network traffic analysis.pdf](https://github.com/user-attachments/files/17922171/Portfolio.Part-1.Cybersecurity.incident.report.network.traffic.analysis.pdf)
[Portfolio (Part-1) Example of a Cybersecurity Incident Report.pdf](https://github.com/user-attachments/files/17922172/Portfolio.Part-1.Example.of.a.Cybersecurity.Incident.Report.pdf)

**Audit Evidence Documentation**

[Portfolio (Part-1) Cybersecurity incident report exemplar network traffic analysis.pdf](https://github.com/user-attachments/files/17922175/Portfolio.Part-1.Cybersecurity.incident.report.exemplar.network.traffic.analysis.pdf)
[Portfolio (Part-1) Example of a Cybersecurity Incident Report.pdf](https://github.com/user-attachments/files/17922177/Portfolio.Part-1.Example.of.a.Cybersecurity.Incident.Report.pdf)

**Part-2: Analyze network attacks**

**Scenario**

Review the following scenario. Then complete the step-by-step instructions.

You work as a security analyst for a travel agency that advertises sales and promotions on the company’s website. The employees of the company regularly access the company’s sales webpage to search for vacation packages their customers might like. 

One afternoon, you receive an automated alert from your monitoring system indicating a problem with the web server. You attempt to visit the company’s website, but you receive a connection timeout error message in your browser.

You use a packet sniffer to capture data packets in transit to and from the web server. You notice a large number of TCP SYN requests coming from an unfamiliar IP address. The web server appears to be overwhelmed by the volume of incoming traffic and is losing its ability to respond to the abnormally large number of SYN requests. You suspect the server is under attack by a malicious actor. 

You take the server offline temporarily so that the machine can recover and return to a normal operating status. You also configure the company’s firewall to block the IP address that was sending the abnormal number of SYN requests. You know that your IP blocking solution won’t last long, as an attacker can spoof other IP addresses to get around this block. You need to alert your manager about this problem quickly and discuss the next steps to stop this attacker and prevent this problem from happening again. You will need to be prepared to tell your boss about the type of attack you discovered and how it was affecting the web server and employees.

**Provided Supporting Documents**

[Portfolio (Part-1) Cybersecurity incident report.pdf](https://github.com/user-attachments/files/17922178/Portfolio.Part-1.Cybersecurity.incident.report.pdf)
[Portfolio (Part-1) How to read a Wireshark TCP_HTTP log.pdf](https://github.com/user-attachments/files/17922182/Portfolio.Part-1.How.to.read.a.Wireshark.TCP_HTTP.log.pdf)

**Audit Evidence Documentation**

[Portfolio (Part-1) Cybersecurity incident report exemplar.pdf](https://github.com/user-attachments/files/17922184/Portfolio.Part-1.Cybersecurity.incident.report.exemplar.pdf)

# Portfolio #2

**Part-1: Apply OS hardening techniques**

**Activity Overview**

In this activity, you will take on the role of a cybersecurity analyst working for a company that hosts the cooking website, yummyrecipesforme.com. Visitors to the website experience a security issue when loading the main webpage. Your job is to investigate, identify, document, and recommend a solution to the security problem. 

When investigating the security event, you will review a tcpdump log. You will need to identify the network protocols used to establish the connection between the user and the website. Network protocols are the communication rules and standards networked devices use to transmit data. Unfortunately, malicious actors can also use network protocols to invade and attack private networks. Knowing how to identify the protocols commonly used in attacks will help you protect your organization’s network against these types of security events.

To complete the assignment, you will also need to document what occurred during the security incident. Then, you will recommend one security measure to implement to prevent similar security problems in the future.

**Scenario**

Review the scenario below. Then complete the step-by-step instructions.

You are a cybersecurity analyst for yummyrecipesforme.com, a website that sells recipes and cookbooks. A disgruntled baker has decided to publish the website’s best-selling recipes for the public to access for free. 

The baker executed a brute force attack to gain access to the web host. They repeatedly entered several known default passwords for the administrative account until they correctly guessed the right one. After they obtained the login credentials, they were able to access the admin panel and change the website’s source code. They embedded a javascript function in the source code that prompted visitors to download and run a file upon visiting the website. After running the downloaded file, the customers are redirected to a fake version of the website where the seller’s recipes are now available for free.

Several hours after the attack, multiple customers emailed yummyrecipesforme’s helpdesk. They complained that the company’s website had prompted them to download a file to update their browsers. The customers claimed that, after running the file, the address of the website changed and their personal computers began running more slowly. 

In response to this incident, the website owner tries to log in to the admin panel but is unable to, so they reach out to the website hosting provider. You and other cybersecurity analysts are tasked with investigating this security event.

To address the incident, you create a sandbox environment to observe the suspicious website behavior. You run the network protocol analyzer tcpdump, then type in the URL for the website, yummyrecipesforme.com. As soon as the website loads, you are prompted to download an executable file to update your browser. You accept the download and allow the file to run. You then observe that your browser redirects you to a different URL, greatrecipesforme.com, which is designed to look like the original site. However, the recipes your company sells are now posted for free on the new website.  

The logs show the following process:

* **1.** The browser requests a DNS resolution of the yummyrecipesforme.com URL.
* **2.** The DNS replies with the correct IP address. 
* **3.** The browser initiates an HTTP request for the webpage.
* **4.** The browser initiates the download of the malware.
* **5.** The browser requests another DNS resolution for greatrecipesforme.com.
* **6.** The DNS server responds with the new IP address.
* **7.** The browser initiates an HTTP request to the new IP address.

A senior analyst confirms that the website was compromised. The analyst checks the source code for the website. They notice that javascript code had been added to prompt website visitors to download an executable file. Analysis of the downloaded file found a script that redirects the visitors’ browsers from yummyrecipesforme.com to greatrecipesforme.com. 

The cybersecurity team reports that the web server was impacted by a brute force attack. The disgruntled baker was able to guess the password easily because the admin password was still set to the default password. Additionally, there were no controls in place to prevent a brute force attack. 

Your job is to document the incident in detail, including identifying the network protocols used to establish the connection between the user and the website.  You should also recommend a security action to take to prevent brute force attacks in the future.

**Provided Supporting Documents**

[Security incident report template.pdf](https://github.com/user-attachments/files/17922288/Security.incident.report.template.pdf)
[DNS HTTP traffic log.pdf](https://github.com/user-attachments/files/17922291/DNS.HTTP.traffic.log.pdf)
[How to read the DNS HTTP traffic log.pdf](https://github.com/user-attachments/files/17922293/How.to.read.the.DNS.HTTP.traffic.log.pdf)

**Audit Evidence Documentation**

[Security incident report exemplar.pdf](https://github.com/user-attachments/files/17922308/Security.incident.report.exemplar.pdf)
[The Exemplar Explained Security incident.pdf](https://github.com/user-attachments/files/17922311/The.Exemplar.Explained.Security.incident.pdf)

**Part-2: Analysis of network hardening**

**Activity Overview**

In this activity, you will be presented with a scenario about a social media organization that recently experienced a major data breach caused by undetected vulnerabilities. To address the breach, you will identify some common network hardening tools that can be implemented to protect the organization’s overall security. Then, you will select a specific vulnerability that the company has and propose different network hardening methods. Finally, you will explain how the methods and tools you chose will be effective for managing the vulnerability and how they will prevent potential breaches in the future. 

In the course, you learned network hardening and network security-related hardening practices, such as port filtering, network access privileges, and encryption over networks. Network hardening practices help organizations monitor potential threats and attacks on their network and prevent some attacks from occurring. Some hardening practices are implemented every day, while others are executed every once in a while, such as every other week or once a month. Understanding how to use network hardening tools and methods will help you better monitor network activity and protect your organization’s network against various attacks.

**Scenario**

Review the following scenario. Then complete the step-by-step instructions.

You are a security analyst working for a social media organization. The organization recently experienced a major data breach, which compromised the safety of their customers’ personal information, such as names and addresses. Your organization wants to implement strong network hardening practices that can be performed consistently to prevent attacks and breaches in the future. 

After inspecting the organization’s network, you discover four major vulnerabilities. The four vulnerabilities are as follows:

* **1.** The organization’s employees' share passwords.
* **2.** The admin password for the database is set to the default.
* **3.** The firewalls do not have rules in place to filter traffic coming in and out of the network.
* **4.** Multifactor authentication (MFA) is not used. 

If no action is taken to address these vulnerabilities, the organization is at risk of experiencing another data breach or other attacks in the future. 

**Provided Supporting Documents**

[Portfolio (Part-2) Security risk assessment report.pdf](https://github.com/user-attachments/files/17922776/Portfolio.Part-2.Security.risk.assessment.report.pdf)
[Network-hardening-tools.xlsx](https://github.com/user-attachments/files/17922778/Network-hardening-tools.xlsx)


**Audit Evidence Documentation**

[Portfolio (Part-2) Security risk assessment report exemplar.pdf](https://github.com/user-attachments/files/17922780/Portfolio.Part-2.Security.risk.assessment.report.exemplar.pdf)
[Security-risk-assessment-report-exemplar.docx](https://github.com/user-attachments/files/17922781/Security-risk-assessment-report-exemplar.docx)

**Part-3: Use the NIST Cybersecurity Framework to respond to a security incident**

**Activity Overview**

In this activity, you will use the knowledge you’ve gained about networks throughout this course to analyze a network incident. You will analyze the situation using the National Institute of Standards and Technology's Cybersecurity Framework (NIST CSF) and create an incident report that you can include as part of your cybersecurity portfolio documentation. The CSF is a voluntary framework that consists of standards, guidelines, and best practices to manage cybersecurity risk. For a refresher, please review this reading about NIST frameworks and the five functions of the NIST CSF framework.Creating a quality cybersecurity incident report and applying the CSF can help you build trust and improve security practices within your organization. 

The CSF is scalable and can be applied in a wide variety of contexts. As you continue to learn more and refine your understanding of key cybersecurity skills, you can use the templates provided in this activity in other situations. Knowing how to identify which security measures to apply in response to business needs will help you determine which are the best available options when it comes to network security.

Be sure to complete this activity before moving on. The next course item will provide you with a completed exemplar to compare to your own work. It will also provide an opportunity for you to answer rubric questions that allow you to reflect on key elements of your incident analysis. 

**Scenario**

Review the scenario below. Then complete the step-by-step instructions.

You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

To address this security event, the network security team implemented: 

* A new firewall rule to limit the rate of incoming ICMP packets
* Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets
* Network monitoring software to detect abnormal traffic patterns
* An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

As a cybersecurity analyst, you are tasked with using this security event to create a plan to improve your company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). You will use the CSF to help you navigate through the different steps of analyzing this cybersecurity incident and integrate your analysis into a general security strategy:

* Identify security risks through regular audits of internal networks, systems, devices, and access privileges to identify potential gaps in security.
* Protect internal assets through the implementation of policies, procedures, training and tools that help mitigate cybersecurity threats.
* Detect potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections.
* Respond to contain, neutralize, and analyze security incidents; implement improvements to the security process.
* Recover affected systems to normal operation and restore systems data and/or assets that have been affected by an incident.

**Provided Supporting Documents**

[Portfolio (Part-3) Incident Report Analysis.pdf](https://github.com/user-attachments/files/17922590/Portfolio.Part-3.Incident.Report.Analysis.pdf)
[Portfolio (Part-3) Applying the NIST CSF.pdf](https://github.com/user-attachments/files/17922591/Portfolio.Part-3.Applying.the.NIST.CSF.pdf)
[Portfolio (Part-3) Example of an Incident Report Analysis.pdf](https://github.com/user-attachments/files/17922595/Portfolio.Part-3.Example.of.an.Incident.Report.Analysis.pdf)

**Audit Evidence Documentation**

[Portfolio (Part-3) Incident Response Analysis.pdf](https://github.com/user-attachments/files/17922462/Portfolio.Part-3.Incident.Response.Analysis.pdf)
