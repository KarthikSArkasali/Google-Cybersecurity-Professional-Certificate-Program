# Connect and Protect: Networks and Network Security

In this course, I have successfully completed advanced training in **Network security**, focusing on its critical role in addressing ongoing security threats and vulnerabilities. This training encompassed a detailed understanding of **network architecture** and the mechanisms employed to secure networks, including the analysis of **network protocols** and the vulnerabilities they may introduce during communication.

Key areas of expertise include the implementation of **firewalls** and other security measures to ensure reliable and secure network operations. I gained insights into various types of **network attacks** and effective techniques to secure compromised systems and devices. This involved examining how malicious actors exploit vulnerabilities in network infrastructure and applying strategies to identify and mitigate potential security risks.

Moreover, I developed proficiency in **network hardening practices**, which strengthen systems against intrusion methods and evolving threats. My training also emphasized addressing the unique security challenges associated with **cloud infrastructures**, leveraging advanced hardening techniques to enhance the overall resilience and integrity of network systems.

![Course 6 Sound the Alarm Detection   Response Certificate (AA6F5MGM4PZB)_page-0001](https://github.com/user-attachments/assets/86cfd9ca-24d0-46d8-9878-43462b3cccb3)

# Portfolio Activity #1: Analyze network layer communication

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

* **Provided Supporting Documents**

    * **Link to template:** [Portfolio (Part-1) Cybersecurity incident report network traffic analysis.pdf](https://github.com/user-attachments/files/17922171/Portfolio.Part-1.Cybersecurity.incident.report.network.traffic.analysis.pdf)

    * **Link to template:** [Portfolio (Part-1) Example of a Cybersecurity Incident Report.pdf](https://github.com/user-attachments/files/17922172/Portfolio.Part-1.Example.of.a.Cybersecurity.Incident.Report.pdf)

* **Audit Evidence Documentation**

    * **Link to template:** [Portfolio (Part-1) Cybersecurity incident report exemplar network traffic analysis.pdf](https://github.com/user-attachments/files/17922175/Portfolio.Part-1.Cybersecurity.incident.report.exemplar.network.traffic.analysis.pdf)

    * **Link to template:** [Portfolio (Part-1) Example of a Cybersecurity Incident Report.pdf](https://github.com/user-attachments/files/17922177/Portfolio.Part-1.Example.of.a.Cybersecurity.Incident.Report.pdf)

# Portfolio Activity #2: Analyze network attacks

**Scenario**

Review the following scenario. Then complete the step-by-step instructions.

You work as a security analyst for a travel agency that advertises sales and promotions on the company’s website. The employees of the company regularly access the company’s sales webpage to search for vacation packages their customers might like. 

One afternoon, you receive an automated alert from your monitoring system indicating a problem with the web server. You attempt to visit the company’s website, but you receive a connection timeout error message in your browser.

You use a packet sniffer to capture data packets in transit to and from the web server. You notice a large number of TCP SYN requests coming from an unfamiliar IP address. The web server appears to be overwhelmed by the volume of incoming traffic and is losing its ability to respond to the abnormally large number of SYN requests. You suspect the server is under attack by a malicious actor. 

You take the server offline temporarily so that the machine can recover and return to a normal operating status. You also configure the company’s firewall to block the IP address that was sending the abnormal number of SYN requests. You know that your IP blocking solution won’t last long, as an attacker can spoof other IP addresses to get around this block. You need to alert your manager about this problem quickly and discuss the next steps to stop this attacker and prevent this problem from happening again. You will need to be prepared to tell your boss about the type of attack you discovered and how it was affecting the web server and employees.

* **Provided Supporting Documents**

    * **Link to template:** [Portfolio (Part-1) Cybersecurity incident report.pdf](https://github.com/user-attachments/files/17922178/Portfolio.Part-1.Cybersecurity.incident.report.pdf)

    * **Link to template:**[Portfolio (Part-1) How to read a Wireshark TCP_HTTP log.pdf](https://github.com/user-attachments/files/17922182/Portfolio.Part- 
1.How.to.read.a.Wireshark.TCP_HTTP.log.pdf)

* **Audit Evidence Documentation**

    * **Link to template:** [Portfolio (Part-1) Cybersecurity incident report exemplar.pdf](https://github.com/user-attachments/files/17922184/Portfolio.Part-1.Cybersecurity.incident.report.exemplar.pdf)

# Portfolio Activity #3: Apply OS hardening techniques

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

* **Provided Supporting Documents**

   * **Link to template:** [Security incident report template.pdf](https://github.com/user-attachments/files/17922288/Security.incident.report.template.pdf)

   * **Link to template:**[DNS HTTP traffic log.pdf](https://github.com/user-attachments/files/17922291/DNS.HTTP.traffic.log.pdf)

   * **Link to template:**[How to read the DNS HTTP traffic log.pdf](https://github.com/user-attachments/files/17922293/How.to.read.the.DNS.HTTP.traffic.log.pdf)

* **Audit Evidence Documentation**

   * **Link to template:**[Security incident report exemplar.pdf](https://github.com/user-attachments/files/17922308/Security.incident.report.exemplar.pdf)

   * **Link to template:**[The Exemplar Explained Security incident.pdf](https://github.com/user-attachments/files/17922311/The.Exemplar.Explained.Security.incident.pdf)

# Portfolio Activity #4: Analysis of network hardening

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

* **Provided Supporting Documents**

    * **Link to template:** [Portfolio (Part-2) Security risk assessment report.pdf](https://github.com/user-attachments/files/17922776/Portfolio.Part-2.Security.risk.assessment.report.pdf)

    * **Link to template:** [Network-hardening-tools.xlsx](https://github.com/user-attachments/files/17922778/Network-hardening-tools.xlsx)

* **Audit Evidence Documentation**

    * **Link to template:** [Portfolio (Part-2) Security risk assessment report exemplar.pdf](https://github.com/user-attachments/files/17922780/Portfolio.Part-2.Security.risk.assessment.report.exemplar.pdf)

    * **Link to template:** [Security-risk-assessment-report-exemplar.docx](https://github.com/user-attachments/files/17922781/Security-risk-assessment-report-exemplar.docx)

# Portfolio Activity #5: Use the NIST Cybersecurity Framework to respond to a security incident

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

* **Provided Supporting Documents**

   * **Link to template:** [Portfolio (Part-3) Incident Report Analysis.pdf](https://github.com/user-attachments/files/17922590/Portfolio.Part-3.Incident.Report.Analysis.pdf)

   * **Link to template:** [Portfolio (Part-3) Applying the NIST CSF.pdf](https://github.com/user-attachments/files/17922591/Portfolio.Part-3.Applying.the.NIST.CSF.pdf)

   * **Link to template:** [Portfolio (Part-3) Example of an Incident Report Analysis.pdf](https://github.com/user-attachments/files/17922595/Portfolio.Part-3.Example.of.an.Incident.Report.Analysis.pdf)

* **Audit Evidence Documentation**

   * **Link to template:**[Portfolio (Part-3) Incident Response Analysis.pdf](https://github.com/user-attachments/files/17922462/Portfolio.Part-3.Incident.Response.Analysis.pdf)
