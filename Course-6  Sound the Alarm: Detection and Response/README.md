#  Sound the Alarm: Detection and Response

In this Course, I have completed in-depth training in **Detection and Incident Response**, a critical area of a cybersecurity analyst's role. This training involved understanding how cybersecurity professionals verify and respond to **malicious threats**, with a focus on the steps involved in the **incident response process**.

I gained hands-on experience with **network analysis tools**, particularly **packet sniffers**, to analyze network traffic for malicious activity. This included crafting **filtering commands** to examine the contents of captured packets. I also explored the various processes involved in incident detection, investigation, analysis, and response, and learned how to analyze suspicious **file hashes** to identify potential threats.

A key aspect of my training was the importance of **documentation and evidence collection** during the detection and response phases. I developed skills in reconstructing an incident’s timeline by mapping artifacts to approximate the chronology of events. Additionally, I studied the role of **logs** in **Intrusion Detection Systems (IDS)** and **Security Information and Event Management (SIEM)** systems, gaining insight into how these tools detect and respond to attacks.

I was introduced to several IDS and SIEM products and learned how to write basic **IDS rules** to generate alerts for malicious network traffic. This training equipped me with the skills needed to effectively detect, respond to, and document cybersecurity incidents.

![Course 3 Connect and Protect Netwoks   Network Security Certificate (H7E9FRJUY7A4)_page-0001](https://github.com/user-attachments/assets/5c5d6f36-bab6-4373-9e74-8a1c5632959d)

# Portfolio Activity #1: Document an incident with an incident handler's journal

**Activity Overview**

In this activity, you will review the details of a security incident and document the incident using your incident handler's journal. Previously, you learned about the importance of documentation in the incident response process. You've also learned how an incident handler's journal is used to record information about security incidents as they are handled. 

Throughout this course, you can apply your documentation skills using your incident handler's journal. With this journal, you can record information about the experiences you will have analyzing security incident scenarios through the course activities. 

By the time you complete this course you will have multiple entries in your incident handler's journal that you can use as a helpful reference to recall concepts and tools. Later, you'll add this document to your cybersecurity portfolio, which you can share with prospective employers or recruiters. To review the importance of building a professional portfolio and options for creating your portfolio, read Create a cybersecurity portfolio. 

**Scenario**

Review the following scenario. Then complete the step-by-step instructions.

A small U.S. health care clinic specializing in delivering primary-care services experienced a security incident on a Tuesday morning, at approximately 9:00 a.m. Several employees reported that they were unable to use their computers to access files like medical records. Business operations shut down because employees were unable to access the files and software needed to do their job.

Additionally, employees also reported that a ransom note was displayed on their computers. The ransom note stated that all the company's files were encrypted by an organized group of unethical hackers who are known to target organizations in healthcare and transportation industries. In exchange for restoring access to the encrypted files, the ransom note demanded a large sum of money in exchange for the decryption key. 

The attackers were able to gain access into the company's network by using targeted phishing emails, which were sent to several employees of the company. The phishing emails contained a malicious attachment that installed malware on the employee's computer once it was downloaded.

Once the attackers gained access, they deployed their ransomware, which encrypted critical files. The company was unable to access critical patient data, causing major disruptions in their business operations. The company was forced to shut down their computer systems and contact several organizations to report the incident and receive technical assistance.

**Link to template:** [Part-1 Incident Handler's journal.pdf](https://github.com/user-attachments/files/17932500/Part-1.Incident.Handler.s.journal.pdf)

**Here is a completed activity.** 

**Link to template:** [Part-1 Incident handler s journal entry.pdf](https://github.com/user-attachments/files/17932526/Part-1.Incident.handler.s.journal.entry.pdf)

# Activity #1: Research network protocol analyzers

**Activity Overview**

In this activity, you'll focus on the two network protocol analyzers: Wireshark and tcpdump. Your goal is to gain a basic understanding of the Wireshark and tcpdump, how they work, and what their features are.

As you've learned, a network protocol analyzer (packet sniffer) is a tool designed to capture and analyze data traffic within a network. Network protocol analyzers help security analysts examine and understand the network traffic flows.

**Scenario**

Review the following scenario. Then complete the step-by-step instructions.

In your role as a cybersecurity analyst, you have been asked to research the differences and similarities between Wireshark and tcpdump and create a chart that outlines your findings. 

**Link to template:** [Diagram-template.pptx](https://github.com/user-attachments/files/17932642/Diagram-template.pptx)

**Here is a completed activity.** 

**Link to template:** [Diagram-exemplar.pptx](https://github.com/user-attachments/files/17932646/Diagram-exemplar.pptx)

# Activity #2: Investigate a suspicious file hash

**Activity Overview**

In this activity, you'll analyze an artifact using VirusTotal and capture details about its related indicators of compromise using the Pyramid of Pain.  

Previously, you were introduced to the concept of the Pyramid of Pain, which is used to understand the different types of **indicators of compromise (IoCs)**. Remember, an IoC is observable evidence that suggests signs of a potential security incident. The Pyramid of Pain describes the relationship between IoCs and the level of difficulty that malicious actors experience when the IoCs are blocked by security teams.

VirusTotal is one of many tools that security analysts use to identify and respond to security incidents. **VirusTotal** is a service that allows anyone to analyze suspicious files, domains, URLs, and IP addresses for malicious content. Through crowdsourcing, VirusTotal gathers and reports on threat intelligence from the global cybersecurity community. This helps security analysts determine which IoCs have been reported as malicious. As a security analyst, you can take advantage of shared threat intelligence to learn more about threats and help improve detection capabilities. 

**Scenario**

Review the following scenario. Then complete the step-by-step instructions.

You are a level one security operations center (SOC) analyst at a financial services company. You have received an alert about a suspicious file being downloaded on an employee's computer. 

You investigate this alert and discover that the employee received an email containing an attachment. The attachment was a password-protected spreadsheet file. The spreadsheet's password was provided in the email. The employee downloaded the file, then entered the password to open the file. When the employee opened the file, a malicious payload was then executed on their computer. 

You retrieve the malicious file and create a SHA256 hash of the file. You might recall from a previous course that a hash function is an algorithm that produces a code that can't be decrypted. Hashing is a cryptographic method used to uniquely identify malware, acting as the file's unique fingerprint. 

Now that you have the file hash, you will use VirusTotal to uncover additional IoCs that are associated with the file.

**Link to template:** [Pyramid of Pain.pptx](https://github.com/user-attachments/files/17932849/Pyramid.of.Pain.pptx)

* Here is a completed activity. 

**Link to template:** [Investigation-findings.pptx](https://github.com/user-attachments/files/17932880/Investigation-findings.pptx)

# Activity #2: Use a playbook to respond to a phishing incident

**Activity Overview**

In this activity, you will respond to a phishing incident that involves a malicious file hash. This is the same SHA256 file hash that you investigated and verified as malicious in a 
previous activity. You'll follow playbook instructions to investigate and resolve the incident's alert ticket.

Previously, you learned how playbooks outline the step-by-step actions necessary to properly respond to a security incident. Coordinated, effective, and quick action is critical during incident response. A playbook can help security teams minimize the impact of an incident and reduce the incident response time. As a security analyst, playbooks can help guide you to effectively support an organization's incident response efforts.

**Scenario**

Review the scenario. Then complete the step-by-step instructions.

You are a level-one security operations center (SOC) analyst at a financial services company. Previously, you received a phishing alert about a suspicious file being downloaded on an employee's computer. After investigating the email attachment file's hash, the attachment has already been verified malicious. Now that you have this information, you must follow your organization's process to complete your investigation and resolve the alert.

Your organization's security policies and procedures describe how to respond to specific alerts, including what to do when you receive a phishing alert. 

In the playbook, there is a flowchart and written instructions to help you complete your investigation and resolve the alert. At the end of your investigation, you will update the alert ticket with your findings about the incident.

**Link to template:** [Part-3 Alert ticket.pdf](https://github.com/user-attachments/files/17932966/Part-3.Alert.ticket.pdf)

**Link to template:** [Part-3 Phishing incident response playbook.pdf](https://github.com/user-attachments/files/17932971/Part-3.Phishing.incident.response.playbook.pdf)

**Here is a completed activity.** 

**Link to template:** [Part-3 Completed alert ticket.pdf](https://github.com/user-attachments/files/17932975/Part-3.Completed.alert.ticket.pdf)

**Link to template:** [Part-3 Final report.pdf](https://github.com/user-attachments/files/17933038/Part-3.Final.report.pdf)

# # Portfolio Activity #2: Finalize your incident handler's journal

**Activity Overview**

In this activity, you will finalize the incident handler's journal that you've been working on throughout this course. Then, you'll add this document to your cybersecurity portfolio, which you can share with prospective employers or recruiters.

You may recall that in a previous activity at the introduction of this course, you completed your first entry in your incident handler's journal. As you progressed through this course, you used your incident handler’s journal to apply your documentation skills and keep track of your learning journey. By now, you might have multiple entries in your journal. These entries would be valuable to add to your portfolio. To review the importance of building a professional portfolio and options for creating your portfolio, read 
Create your cybersecurity portfolio.

**Link to template:** [Part-3 Incident handler-s journal.pdf](https://github.com/user-attachments/files/17933221/Part-3.Incident.handler-s.journal.pdf)

**Here is a completed activity.** 

**Link to template:** [Part- 4 Completed incident handler-s journal.pdf](https://github.com/user-attachments/files/17933226/Part-.4.Completed.incident.handler-s.journal.pdf)
