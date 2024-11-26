# Play It Safe: Manage Security Risks

In the Foundations of Cybersecurity course, I have completed comprehensive training in the CISSP’s eight security domains, gaining a deep understanding of primary threats, risks, and vulnerabilities to business operations. My learning includes expertise in the **National Institute of Standards and Technology’s (NIST) Risk Management Framework (RMF)** and the **risk management** process. I am well-versed in security frameworks and controls, with a strong grasp of the core components of the confidentiality, integrity, and availability (CIA) triad.

Additionally, I have explored the **Open Web Application Security Project (OWASP)** security principles and conducted security audits. I have hands-on experience with industry-leading **Security Information and Event Management (SIEM)** tools, including their use in real-world scenarios by entry-level security analysts to protect business operations. This includes utilizing SIEM dashboards for daily tasks and analyzing security events.

I have also developed proficiency in the purposes and applications of **playbooks**, leveraging them to effectively respond to **identified threats**, **risks**, and **vulnerabilities**, demonstrating my capability in enhancing organizational security posture.


![Coursera PDUGL4X2LY25 (All in one)_page-0001](https://github.com/user-attachments/assets/e71d5c3e-82bf-45f4-9b4a-2acfe7c5f79d)

# Threats

A **threat** is any circumstance or event that can negatively impact assets. As an entry-level security analyst, your job is to help defend the organization’s assets from inside and outside threats. Therefore, understanding common types of threats is important to an analyst’s daily work. As a reminder, common threats include:

  * **Insider threats:** Staff members or vendors abuse their authorized access to obtain data that may harm an organization.
  * **Advanced persistent threats (APTs):** A threat actor maintains unauthorized access to a system for an extended period of time.

# Risks

A **risk** is anything that can impact the **confidentiality**, **integrity**, or **availability** of an asset. A basic formula for determining the level of risk is that risk equals the likelihood of a threat. One way to think about this is that a risk is being late to work and threats are traffic, an accident, a flat tire, etc. 

There are different factors that can affect the likelihood of a risk to an organization’s assets, including:

 * **External risk:** Anything outside the organization that has the potential to harm organizational assets, such as threat actors attempting to gain access to private information
 * **Internal risk:** A current or former employee, vendor, or trusted partner who poses a security risk
 * **Legacy systems:** Old systems that might not be accounted for or updated, but can still impact assets, such as workstations or old mainframe systems. For example, an organization might have an old vending 
    machine that takes credit card payments or a workstation that is still connected to the legacy accounting system.
 +* **Multiparty risk:** Outsourcing work to third-party vendors can give them access to intellectual property, such as trade secrets, software designs, and inventions.
  * **Software compliance/licensing:** Software that is not updated or in compliance, or patches that are not installed in a timely manner.

# Vulnerabilities

A **vulnerability** is a weakness that can be exploited by a threat. Therefore, organizations need to regularly inspect for vulnerabilities within their systems. Some vulnerabilities include:

 * **ProxyLogon:** A pre-authenticated vulnerability that affects the Microsoft Exchange server. This means a threat actor can complete a user authentication process to deploy malicious code from a remote location.
 * **ZeroLogon:** A vulnerability in Microsoft’s Netlogon authentication protocol. An authentication protocol is a way to verify a person's identity. Netlogon is a service that ensures a user’s identity before allowing access to a website's location.
 * **Log4Shell:** Allows attackers to run Java code on someone else’s computer or leak sensitive information. It does this by enabling a remote attacker to take control of devices connected to the internet and run malicious code.
 * **PetitPotam:** Affects Windows New Technology Local Area Network (LAN) Manager (NTLM). It is a theft technique that allows a LAN-based attacker to initiate an authentication request.
 * **Security logging and monitoring failures:** Insufficient logging and monitoring capabilities that result in attackers exploiting vulnerabilities without the organization knowing it
 * **Server-side request forgery:** Allows attackers to manipulate a server-side application into accessing and updating backend resources. It can also allow threat actors to steal data.

The OWASP’s common attack types list contains three new risks for the years 2017 to 2021: insecure design, software and data integrity failures, and server-side request forgery. This update emphasizes the fact that security is a constantly evolving field. It also demonstrates the importance of staying up to date on current threat actor tactics and techniques, so you can be better prepared to manage these types of risks.

![szc-NuF5QlGxA_zoi9LvEg_f089df6d2f2b4fd0bf7ebd806ed63cf1_S33G012](https://github.com/user-attachments/assets/9f704f2f-2e34-41fe-bd43-4f05d429137b)

# National Institute of Standards and Technology (NIST) Risk Management Framework (RMF)

The **NIST Risk Management Framework (RMF)** is a structured process designed by the National Institute of Standards and Technology (NIST) to help organizations manage and mitigate risks associated with information systems. It provides a comprehensive, flexible, and repeatable approach for integrating security, privacy, and cyber supply chain risk management activities into the system development lifecycle. The RMF aligns with federal standards and supports compliance with laws like the Federal Information Security Modernization Act (FISMA).

There are seven steps in the RMF: **Prepare**, **Categorize**, **Select**, **Implement**, **Assess**, **Authorize**, and **Monitor**.

* **Prepare:** Establish the organizational context, governance, and risk management strategy to support effective security and privacy operations.<br>
**Example:** A healthcare organization prepares for implementing RMF by defining risk tolerance, establishing a security team, and allocating resources for managing patient data securely.

* **Categorize:** Classify the information system and the data it processes based on potential impacts of a breach in confidentiality, integrity, or availability (CIA).<br>
**Example:** A financial institution categorizes its payment processing system as "High Impact" due to the risk of fraud or disruption to critical transactions.

* **Select:** Identify and customize baseline security controls tailored to the system's categorization and risk profile.<br>
**Example:** An e-commerce platform selects encryption controls for customer data in transit and at rest to safeguard against unauthorized access.

* **Implement:** Deploy and configure the chosen security controls in the information system and document how they are applied.<br>
**Example:** A software development firm implements multi-factor authentication (MFA) across all systems to reduce the risk of unauthorized access.

* **Assess:** Evaluate the effectiveness of implemented controls to ensure they function as intended and address risks adequately.<br>
**Example:** A government agency conducts penetration testing to assess whether its firewalls and intrusion detection systems can withstand simulated attacks.

* **Authorize:** Senior officials make a risk-based decision to approve the system for operation, considering any remaining residual risks.<br>
**Example:** A cloud service provider's executive team authorizes a new file storage system after confirming that encryption and access controls mitigate major risks.

* **Monitor:** Continuously oversee the system's security posture, track new risks, and adapt controls as needed to address emerging threats.<br>
**Example:** A retail company uses Security Information and Event Management (SIEM) tools to monitor for anomalies and prevent potential breaches in its payment systems.

# Security frameworks 

**Security frameworks** are guidelines used for building plans to help mitigate risk and threats to data and privacy. Frameworks support organizations’ ability to adhere to compliance laws and regulations. For example, the healthcare industry uses frameworks to comply with the United States’ Health Insurance Portability and Accountability Act (HIPAA), which requires that medical professionals keep patient information safe. 

There are many different frameworks and controls that organizations can use to remain compliant with regulations and achieve their security goals. Frameworks covered in this reading are the Cyber Threat Framework (CTF) and the International Organization for Standardization/International Electrotechnical Commission (ISO/IEC) 27001. Several common security controls, used alongside these types of frameworks, are also explained. 

* **Cyber Threat Framework (CTF)**

According to the Office of the Director of National Intelligence, the CTF was developed by the U.S. government to provide “a common language for describing and communicating information about cyber threat activity.” By providing a common language to communicate information about threat activity, the CTF helps cybersecurity professionals analyze and share information more efficiently. This allows organizations to improve their response to the constantly evolving cybersecurity landscape and threat actors' many tactics and techniques.

* **International Organization for Standardization/International Electrotechnical Commission (ISO/IEC) 27001**

An internationally recognized and used framework is ISO/IEC 27001. The ISO 27000 family of standards enables organizations of all sectors and sizes to manage the security of assets, such as financial information, intellectual property, employee data, and information entrusted to third parties. This framework outlines requirements for an information security management system, best practices, and controls that support an organization’s ability to manage risks. Although the ISO/IEC 27001 framework does not require the use of specific controls, it does provide a collection of controls that organizations can use to improve their security posture. 

# Security controls

**Security controls** are safeguards designed to reduce specific security risks. Security controls are the measures organizations use to lower risk and threats to data and privacy. For example, a control that can be used alongside frameworks to ensure a hospital remains compliant with HIPAA is requiring that patients use multi-factor authentication (MFA) to access their medical records. Using a measure like MFA to validate someone’s identity is one way to help mitigate potential risks and threats to private data.

Controls are used alongside frameworks to reduce the possibility and impact of a security threat, risk, or vulnerability. Controls can be physical, technical, and administrative and are typically used to prevent, detect, or correct security issues.

* **Examples of physical controls:**
  * Gates, fences, and locks
  * Security guards
  * Closed-circuit television (CCTV), surveillance cameras, and motion detectors
  * Access cards or badges to enter office spaces

* **Examples of technical controls:**
  * Firewalls
  * MFA
  * Antivirus software
    
* **Examples of administrative controls:**
  * Separation of duties
  * Authorization
  * Asset classification

# CIA triad

The CIA triad is a model that helps inform how organizations consider risk when setting up systems and security policies. It is made up of three elements that cybersecurity analysts and organizations work toward upholding: confidentiality, integrity, and availability. Maintaining an acceptable level of risk and ensuring systems and policies are designed with these elements in mind helps establish a successful security posture

**Confidentiality**

Confidentiality ensures that only authorized users can access specific data or resources. It protects sensitive information from being exposed to unauthorized individuals.

* **Key Practice:**
The principle of least privilege is a key method to enhance confidentiality. This principle restricts access so users can only interact with the data necessary for their job. By limiting access, the organization minimizes the risk of accidental or intentional data exposure.<br>

* **Example:**
In a hospital, doctors have access to their patients' medical records but cannot view records of patients they are not treating. This ensures confidentiality by limiting access to only necessary information.

* **Real-Time Example:**
A data breach at a bank could occur if employees without clearance access sensitive customer information. By implementing least privilege and role-based access controls, the bank can ensure only relevant employees can view financial data.

**Integrity**

Integrity means ensuring that data remains accurate, authentic, and reliable. This involves protecting data from being altered or corrupted by unauthorized parties.

* **Key Practice:**
Cryptography and encryption are common techniques used to maintain integrity. Encryption transforms data into a secure format that unauthorized users cannot access or tamper with.
  * **Cryptography:** Protects data during transmission (e.g., online banking transactions).
  * **Checksum Verification:** Verifies that downloaded files or system data are unaltered.

* **Example:**
In an organization, internal communication on a messaging platform is encrypted to prevent tampering. If an attacker tries to intercept and modify a message, the system can detect and block it.

* **Real-Time Example:**
During the 2020 U.S. elections, cryptographic signatures were used to ensure the integrity of vote-counting systems, preventing tampering or manipulation of election data.

**Availability**

Availability ensures that data and systems are accessible to authorized users whenever needed. It involves maintaining operational uptime and minimizing disruptions due to outages or attacks.

* **Key Practice:**
Systems must be designed with redundancy, backup plans, and robust access protocols. For example, employees working remotely may need secure access to internal networks, while still ensuring restricted access based on their job roles.

* **Example:**
A remote employee in the accounting department can access financial systems but is blocked from accessing ongoing development project files. This ensures data availability and appropriate confidentiality.

* **Real-Time Example:**
During a distributed denial-of-service (DDoS) attack, websites like Amazon maintain availability by using load balancers and distributed servers to handle traffic surges without going offline. These measures ensure customers and employees can still access services without interruption.

# NIST Cybersecurity Framework

The **NIST Cybersecurity Framework (CSF)** is a widely recognized framework that helps organizations manage and reduce cybersecurity risks. Developed by the National Institute of Standards and Technology (NIST), it provides a flexible and repeatable structure for improving security posture across industries.

NIST CSF focuses on five core functions: **Identify**, **Protect**, **Detect**, **Respond**, and **Recover**. These core functions help organizations manage cybersecurity risks, implement risk management strategies, and learn from previous mistakes. Basically, when it comes to security operations, NIST CSF functions are key for making sure an organization is protected against potential threats, risks, and vulnerabilities. 

* **Identify:**
Focuses on understanding and managing cybersecurity risks to systems, people, assets, and data.<br>
**Real-Time Example:** A financial institution conducts a vulnerability assessment on its online banking platform to identify exposed endpoints, ensuring customer data and transactions remain secure.

* **Protect:**
Implements safeguards such as policies, procedures, and tools to mitigate cybersecurity threats.<br>
**Real-Time Example:** A healthcare provider uses multi-factor authentication (MFA) and encrypts electronic health records to protect patient information from unauthorized access.

* **Detect:**
Develops capabilities to quickly identify security incidents through effective monitoring and alerting mechanisms.<br>
**Real-Time Example:** An e-commerce company employs a Security Information and Event Management (SIEM) system to detect unusual login patterns, such as multiple failed login attempts, flagging a potential brute-force attack.

* **Respond:**
Ensures procedures are in place to contain, neutralize, and analyze security incidents while preventing recurrence.<br>
**Real-Time Example:** A software company responds to a ransomware attack by isolating infected systems, analyzing the attack vector, and applying patches to prevent similar incidents.

* **Recover:**
Focuses on restoring systems, data, and operations to minimize disruption and reduce risk.<br>
**Real-Time Example:** After a DDoS attack on its servers, a retail website uses backup systems to restore functionality and implements a distributed server strategy to prevent future outages.

# Security principles

In the workplace, security principles are embedded in your daily tasks. Whether you are analyzing logs, monitoring a security information and event management (SIEM) dashboard, or using a 
vulnerability scanner you will use these principles in some way. 

Previously, you were introduced to several OWASP security principles. These included:

* Minimize attack surface area: Attack surface refers to all the potential vulnerabilities a threat actor could exploit.
* Principle of least privilege: Users have the least amount of access required to perform their everyday tasks.
* Defense in depth: Organizations should have varying security controls that mitigate risks and threats.
* Separation of duties: Critical actions should rely on multiple people, each of whom follow the principle of least privilege. 
* Keep security simple: Avoid unnecessarily complicated solutions. Complexity makes security difficult. 
* Fix security issues correctly: When security incidents occur, identify the root cause, contain the impact, identify vulnerabilities, and conduct tests to ensure that remediation is successful.

**Security audits**

A security audit is a review of an organization's security controls, policies, and procedures against a set of expectations. Audits are independent reviews that evaluate whether an organization is meeting internal and external criteria. Internal criteria include outlined policies, procedures, and best practices. External criteria include regulatory compliance, laws, and federal regulations. 

# log

log is a record of events that occur within an organization's systems and networks. Security analysts access a variety of logs from different sources. Three common log sources include firewall logs, network logs, and server logs. Let's explore each of these log sources in more detail.

* **Firewall log** is a record of attempted or established connections for incoming traffic from the internet. It also includes outbound requests to the internet from within the network.<br>
* **Network log** is a record of all computers and devices that enter and leave the network. It also records connections between devices and services on the network.<br>
* **Server log** is a record of events related to services such as websites, emails, or file shares. It includes actions such as login, password, and username requests.<br>

**Security Information and Event Management (SIEM)**

A security information and event management, or SIEM, tool is an application that collects and analyzes log data to monitor critical activities in an organization. It provides real-time visibility, event monitoring and analysis, and automated alerts. It also stores all log data in a centralized location.

# Playbook

**Playbook** is a step-by-step guide that tells a team how to handle a specific incident, like a cybersecurity threat. It explains what needs to be done, who is responsible, and how to complete each task.

Playbooks are always updated because:

* Mistakes or gaps in the process are found.
* Industry rules or laws change.
* New cyber threats or hacking methods appear.

Since no single person knows everything, teams work together to improve playbooks. This keeps them effective and ready to handle new challenges. Playbooks help beginners and experts stay organized during incidents.

# Types of playbooks

Incident and Vulnerability Response Playbooks are essential tools for entry-level cybersecurity professionals, guiding them through predefined steps to handle incidents and vulnerabilities effectively. Developed in alignment with an organization's business continuity plan, these playbooks help ensure operations can quickly recover after disruptions like security breaches.

Both playbooks focus on adhering to legal and organizational standards, minimizing errors, and completing critical tasks within specific timeframes. They are especially vital during forensic investigations, as mishandling data can compromise its usability.

Common Steps in Playbooks:

* **Preparation:** Establish readiness and tools.
* **Detection:** Identify threats or vulnerabilities.
* **Analysis:** Assess impact and severity.
* **Containment:** Limit damage to systems.
* **Eradication:** Remove threats completely.
* **Recovery:** Restore normal operations.
* **Post-Incident Activities:** Evaluate and improve future responses.

* **Playbooks and SIEM Tools**

Playbooks are essential tools for cybersecurity teams, providing a consistent, step-by-step response to security incidents. They detail specific actions, roles, and sequences, often using flowcharts or tables for clarity. Playbooks cover various scenarios, such as recovery from ransomware attacks, ensuring effective responses regardless of who handles the case.

When paired with Security Information and Event Management (SIEM) tools, playbooks enhance incident response. For instance, if a SIEM tool flags unusual user behavior, the playbook guides analysts through the investigation and resolution process. This integration ensures timely and standardized handling of security events.

* **Playbooks and SOAR Tools**

Playbooks are also used with Security Orchestration, Automation, and Response (SOAR) tools, which automate repetitive tasks generated by SIEM or Managed Detection and Response (MDR) tools. Unlike SIEM, SOAR automates responses, such as blocking a user account after multiple failed login attempts. Analysts then use playbooks to investigate and resolve the issue effectively.

By combining playbooks with SIEM and SOAR tools, organizations streamline threat detection, response, and resolution, improving efficiency and consistency in incident handling.

# Portfolio #1

**Portfolio Activity:** Conduct a security audit

In part one of this activity, I conducted an internal security audit, which I can now include in my cybersecurity portfolio

**Scenario**

Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She expresses concerns about not having a solidified plan of action to ensure business continuity and compliance, as the business grows. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

Your task is to review the IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist. 




