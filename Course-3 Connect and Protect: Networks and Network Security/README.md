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

# Difference between IPv4 and IPv6

As the internet grew, IPv4 addresses became insufficient, leading to IPv4 address exhaustion. To address this, IPv6 was developed, offering significantly more addresses and other improvements.

Key Differences Between IPv4 and IPv6
Address Format:

IPv4: Four decimal numbers (0–255) separated by periods (e.g., 198.51.100.0). Supports ~4.3 billion addresses.
IPv6: Eight hexadecimal numbers (up to four digits each) separated by colons (e.g., 2002:0db8::ff21:0023:1234). Supports ~340 undecillion addresses.
Packet Header: IPv6 headers are simpler than IPv4, omitting fields like IHL and Flags while adding the Flow Label field for improved routing efficiency.

Security and Efficiency: IPv6 offers better routing, prevents private address collisions, and supports end-to-end encryption more natively.

