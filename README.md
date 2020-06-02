
## Sources

* QUIZ: https://quizlet.com/231268221/general-information-security-questions-flash-cards/
* SANS Cheat Sheets: https://www.sans.org/blog/the-ultimate-list-of-sans-cheat-sheets/
* Offensive Security (OSCP): https://411hall.github.io/OSCP-Preparation/
    * https://medium.com/@falconspy/oscp-exam-attempt-1-1893df5a0a00
* VulnHub - LABS: https://www.vulnhub.com/

## Sources for Information Security News:
   * Various places. Primarily Security Weekly Podcast (Paul Assadorian), google, Krebs On Security (Sometimes) and Daniel Miessler of danielmiessler.com.
   

## Basic Concepts

1. What is information security and how is it achieved?
    * Information Security refers to the processes and methodologies which are designed and implemented to protect print, electronic, or any other form of confidential, private and sensitive information or data from unauthorized access, use, misuse, disclosure, destruction, modification, or disruption.

2. What are the core principles of information security?
    * CIA triad. CIA stands for confidentiality, integrity, and availability and these are the three main objectives of information security. 
    * Authentication and Non-repudiation

3. What is non-repudiation (as it applies to IT security)?
   * Non-repudiation is the assurance that someone cannot deny the validity of something. 
    * Non-repudiation is a legal concept that is widely used in information security and refers to a service, which provides proof of the origin of data and the integrity of the data.
    * The concept that every service or process should provide proof of the integrity (such as a signature) and origin of data. It is a aspect of information security because it ensures the integrity of data, processes, and transmissions

4. What is the relationship between information security and data availability?
    * Information security encompasses the tactics and processes used to protect data and ensure that only authenticated and approved users have access to authorized data. Information security cannot inhibit authorized users from access, but it must protect data from unauthorized access or theft using logical and physical controls.

5. What is a security policy and why do we need one?
    * A document that governs how, when, and why users may access and interact with information systems. It provides users with reasonable expectations of their roles and responsibilities, as well as serves as a guidance for procedural actions.

6. What is the difference between logical and physical security? Can you give an example of both?
    * Protecting the people involves a combination of physical and logical security. Physical security keeps them safe by allowing only authorized individuals into the building. Logical security protects their computers and data from unauthorized access.
    * Logical security protects computer software by discouraging user access by implementing user identifications, passwords, authentication,and biometrics. Physical security prevents and discourages attackers from entering a building by installing fences, alarms, cameras, security guards, electronic access control, intrusion detection and administration access controls. The difference between logical security and physical security is logical security protects access to computer systems and physical security protects the site and everything located within the site.

7. Is there an acceptable level of risk?
    * A level of risk mitigates as much risk as possible while still enabling the business to operate at optimum levels.
The risk assignment should always be re-evaluated as new technologies, processes, and the threat environment changes.

8. How do you measure risk? Can you give an example of a specific metric that measures information security risk?
    * Risk is calculated by multiplying the threat likelihood value by the impact value, and the risks are categorized as high, medium or low based on the result.  ISO Standard 27005 (Information Security Risk Management - ISRM)
    * 

9. Can you give me an example of risk trade-offs (e.g. risk vs cost)?

10. What are the most common types of attack that threaten enterprise data security?
    * Insider Threats
    * Ransomware
    * Malware that enables data exfiltration,
    * Scripting attacks (XSS, cross site forgery)
    * Injection Attacks (SQL/ javascript)

11. What is the difference between a threat and a vulnerability?
    * A vulnerability is weakness in a system, site, or process that a threat may take advantage of. A threat is any entity or process that manipulates a weaknesses to commit unauthorized actions or attain unauthorized access to an information system.

12. Can you give me an example of common security vulnerabilities?
    * Cross Site Scripting
    * SQL Injections
    * Cross Site Forgery 
    * Buffer Overflows 
    * Poor Encryption/ No Encryption 
    * mis-configured firewall rules 
    * poor access control / active domain rules policies.

13. Are you familiar with any security management frameworks such as ISO/IEC 27002?
    * ISO/IEC 270002
    * NIST SP 800-53: Nist Cyber Security framework
    * SOC 2/3
    * PCI-DSS
    * HIPAA
    * NERC-CIP
    * FFIEC

14. Can you briefly discuss the role of information security in each phase of the software development lifecycle?
    * Requirements Gathering
      * Security Requirements
      * Setting up Phase Gates
      * Risk Assessment
    * Design
      * Identify Design Requirements from security perspective
      * Architecture & Design Reviews
      * Threat Modeling
    * Coding
      * Coding Best Practices
      * Perform Static Analysis
    * Testing
      * Vulnerability Assessment
      * Fuzzing
    * Deployment
      * Server Configuration Review
      * Network Configuration Review

15. Can you describe the role of security operations in the enterprise?
    * A SOC is an organized and highly skilled team whose mission is to monitor and improve an organization's cybersecurity posture while preventing, detecting, analyzing, and responding to cyber security incidents using both technology and precise procedures.

16. What is incident management?
    * IT incident management is an area of IT service management (ITSM) wherein the IT team returns a service to normal as quickly as possible after a disruption, in a way that aims to create as little negative impact on the business as possible.
    * Security incident management focuses heavily on resolving incidents quickly to ensure that employees and users alike aren’t hit with too much downtime. By identifying, managing, recording and analyzing security threats or incidents in real-time, security incident management provides a robust and comprehensive view of any security issues within an IT infrastructure. 

17. Why is DNS monitoring important?
    * DNS plays an important role in connecting end users to the internet. Each connection made to a domain by the client devices is recorded in the DNS logs. Inspecting DNS traffic between client devices and your local resolver could reveal information for forensic analysis as well as discovering malicious activity/connections on your network such as:
      * botnets
      * DDOS attack detections
      * malicious domains
      * dynamic domains

18. What is a security control?
    * A safeguards or countermeasure to avoid, detect, counteract, or minimize security risks.

19. What are the different types of security control?
    * Logical Security Controls
    * Physical Security Controls
    * Procedural Security Controls

20. Can you describe the information lifecycle? How do you ensure information security at each phase?
    * It is the way that information is properly managed throughout its life cycle in order to get the full use and benefit from it. Includes Plan, Obtain, Store/Share, Maintain, Apply, and Dispose

21. What is Information Security Governance?
    * IT security governance is the system by which an organization directs and controls IT security (adapted from ISO 38500).
    * Governance specifies the accountability framework and provides oversight to ensure that risks are adequately mitigated, while management ensures that controls are implemented to mitigate risks.

22. What are your professional values? Why are professional ethics important in the information security field?
    * With great power comes great responsibility. Security professionals are given an exceptional amount of access to organizational IT infrastructure and they are often incredibly trusted. It's very important that security professionals act in an ethical and honest manner to protect the business and it's stakeholders.

## Security Audits and Testing

23. What is an IT security audit?
    * At its root, an IT security audit includes two different assessments. The manual assessment occurs when an internal or external IT security auditor interviews employees, reviews access controls, analyzes physical access to hardware, and performs vulnerability scans. These reviews should occur, at a minimum, annually. Some organizations, however, prefer to do them more frequently.
    * While some apply broadly to the IT industry, many are more sector-specific, pertaining directly, for instance, to healthcare or financial institutions. Below is a short list of some of the most-discussed IT security standards in existence today.
      * ISO Compliance: The International Organization for Standardization (ISO) develops and publishes an array of guidelines designed to ensure quality, reliability, and safety. The ISO/IEC 27000 family of standards are some of the most relevant to system administrators, as these standards focus on keeping information assets secure. The ISO/IEC 27001 is known for its information security management system requirements.
      * HIPAA Security Rule: The HIPAA Security Rule outlines specific guidelines pertaining to exactly how organizations should protect patients’ electronic personal health information.
      * PCI DSS Compliance: The PCI DSS compliance standard applies directly to companies dealing with any sort of customer payment. Think of this standard as the requirement responsible for making sure your credit card information is protected every time you conduct a transaction.
      * SOX Compliance: The SOX Act, known more formally as the Sarbanes-Oxley Act after its sponsors Senator Paul Sarbanes (D-MD) and Representative Michael G. Oxley (R-OOH-4), was passed in 2002 following the highly publicized Enron scandal. The goal was to protect investors by requiring all public companies to provide accurate, reliable financial disclosures on an annual basis.

24. How do you test information security?
    * Penetration testing: This kind of testing simulates an attack from a malicious hacker. This testing involves analysis of a particular system to check for potential vulnerabilities to an external hacking attempt. 
    * Risk Assessment: This testing involves analysis of security risks observed in the organization.

25. What is the difference between black box and white box penetration testing?
    *  Black-Box engagement, the consultant does not have access to any internal information and is not granted internal access to the client’s applications or network. It is the job of the consultant to perform all reconnaissance to obtain the sensitive knowledge needed to proceed, which places them in a role as close to the typical attacker as possible. This type of testing is the most realistic, but also requires a great deal of time and has the greatest potential to overlook a vulnerability that exists within the internal part of network or application. 
    *  White-Box testing, which allows the security consultant to have complete open access to applications and systems. This allows consultants to view source code and be granted high-level privilege accounts to the network. The purpose of white-box testing is to identify potential weaknesses in various areas such as logical vulnerabilities, potential security exposures, security misconfigurations, poorly written development code, and lack-of-defensive measures. This type of assessment is more comprehensive, as both internal and external vulnerabilities are evaluated from a “behind the scenes” point of view that is not available to typical attackers.

26. What is a vulnerability scan?
    * Vulnerability scanning is an inspection of the potential points of exploit on a computer or network to identify security holes. A vulnerability scan detects and classifies system weaknesses in computers, networks and communications equipment and predicts the effectiveness of countermeasures.

27. What is captured in a security assessment plan (security test plan)?
    * The security assessment plan documents the controls and control enhancements to be assessed, based on the purpose of the assessment and the implemented controls identified and described in the system security plan. The security assessment plan defines the scope of the assessment, in particular indicating whether a complete or partial assessment will be performed and if the assessment is intended to support initial pre-authorization activities associated with a new or significantly changed system or ongoing assessment used for operational systems. The security assessment plan also describes the procedures to be used for each control—typically drawn from Special Publication 800-53A or from available assessment cases and tailored as necessary to satisfy organizational or system-specific requirements—including the selection of assessment methods and objects and assigned depth and coverage attributes. 

## Access Control

28. What is the difference between authentication and authorization?
    * Authentication means confirming your own identity, while authorization means granting access to the system. In simple terms, authentication is the process of verifying who you are, while authorization is the process of verifying what you have access to.

29. What types of information can be used for authentication?
    * Type 1 – *Something You Know* – includes passwords, PINs, combinations, code words, or secret handshakes. Anything that you can remember and then type, say, do, perform, or otherwise recall when needed falls into this category.
    * Type 2 – *Something You Have* – includes all items that are physical objects, such as keys, smart phones, smart cards, USB drives, and token devices. (A token device produces a time-based PIN or can compute a response from a challenge number issued by the server.).
    * Type 3 – *Something You Are* – includes any part of the human body that can be offered for verification, such as fingerprints, palm scanning, facial recognition, retina scans, iris scans, and voice verification.

30. What is role-based access control?
    * Role-based access control (RBAC) refers to the idea of assigning permissions to users based on their role within an organization. It provides fine-grained control and offers a simple, manageable approach to access management that is less prone to error than assigning permissions to users individually.

31. What is meant by the term "least privilege"?
    * The principle of least privilege works by allowing only enough access to perform the required job. In an IT environment, adhering to the principle of least privilege reduces the risk of attackers gaining access to critical systems or sensitive data by compromising a low-level user account, device, or application.

32. What is two-factor authentication? Does it require special hardware?
    * Two-factor authentication (also known as 2FA) is a type, or subset, of multi-factor authentication. ... Two-step verification or two-step authentication is a method of confirming a user's claimed identity by utilizing something they know (password) and a second factor other than something they have or something they are.

## Security Architecture

33. Why are open standards important to security solutions?

34. How do you balance demands from different stakeholders who have conflicting requirements?

35. What is layered security architecture? Is it a good approach? Why?
    * Layered security, also known as layered defense, describes the practice of combining multiple mitigating security controls to protect resources and data.

36. Have you designed security measures that span overlapping information domains? Can you give me a brief overview of the solution?

37. How do you ensure that a design anticipates human error?

38. How do you ensure that a design achieves regulatory compliance?

39. What is capability-based security? Have you incorporated this pattern into your designs? How?
    * Capability-based security refers to the principle of designing user programs such that they directly share capabilities with each other according to the principle of least privilege, and to the operating system infrastructure necessary to make such transactions efficient and secure.

40. Can you give me a few examples of security architecture requirements?
    * https://www.isaca.org/resources/isaca-journal/issues/2017/volume-4/enterprise-security-architecturea-top-down-approach

41. Who typically owns security architecture requirements and what stakeholders contribute?

42. What special security challenges does SOA present?
    * Service Oriented Architecture (SOA) is a new way of operating a network system, and as with all new technologies, it comes with its share of challenges. Of particular difficulty is the challenge of securing a service-oriented system. Due to the intentionally decentralized nature of this system, data flows in all directions and needs to be protected at all times. Additionally, to implement access control it must be first defined somewhere, and the rest of the system needs to be aware of the rules and respect them. Since there are many resources in such a system, it becomes cumbersome to require users to authenticate themselves every time they attempt to access a new resource.

43. What security challenges do unified communications present?

44. Do you take a different approach to security architecture for a commercial off-the-shelf (COTS) vs a custom solution?

45. Have you architected a security solution that involved SaaS components? What challenges did you face?

46. Have you worked on a project in which stakeholders choose to accept identified security risks that worried you? How did you handle the situation?

## Network

47. What is a firewall?
    * A firewall is a network security device that monitors incoming and outgoing network traffic and decides whether to allow or block specific traffic based on a defined set of security rules.

48. Besides firewalls, what other devices are used to enforce network boundaries?

49. What is the role of network boundaries in information security?
    * Boundary protection is the "monitoring and control of communications at the external boundary of an information system to prevent and detect malicious and other unauthorized communication." Protection is achieved through the use of gateways, routers, firewalls, guards, and encrypted tunnels

50. What does a intrusion detection (IDS) system do? How does it do it?
    * An intrusion detection system (IDS) is a device or software application that monitors a network for malicious activity or policy violations. Any malicious activity or violation is typically reported or collected centrally using a security information and event management system.

51. What is a honeypot? What type of attack does it defend against?
    * A honeypot is a computer or computer system intended to mimic likely targets of cyberattacks. It can be used to detect attacks or deflect them from a legitimate target. It can also be used to gain information about how cybercriminals operate.

52. What technologies and approaches are used to secure information and services deployed on cloud computing infrastructure?

53. What information security challenges are faced in a cloud computing environment?

54. How does packet filtering work?
    * A packet-filtering firewall examines each packet that crosses the firewall and tests the packet according to a set of rules that you set up. Packet filters work by inspecting the source and destination IP and port addresses contained in each Transmission Control Protocol/Internet Protocol (TCP/IP) packet

55. Can you give me an overview of IP multicast?
    * IP multicast is a method of sending Internet Protocol (IP) datagrams to a group of interested receivers in a single transmission. It is the IP-specific form of multicast and is used for streaming media and other network applications. It uses specially reserved multicast address blocks in IPv4 and IPv6.

56. Can you explain the difference between a packet filtering firewall and a application layer firewall?
    * Packet filtering is a firewall technique used to control network access by monitoring outgoing and incoming packets and allowing them to pass or halt based on the source and destination Internet Protocol (IP) addresses, protocols and ports.
     * In computing, a stateful firewall (any firewall that performs stateful packet inspection (SPI) or stateful inspection) is a firewall that keeps track of the state of network connections (such as TCP streams, UDP communication) traveling across it.
    * A web application firewall (WAF) is an appliance, server plugin, or filter that applies a set of rules to an HTTP conversation. Generally, these rules cover common attacks such as cross-site scripting (XSS) and SQL injection. By customizing the rules to your application, many attacks can be identified and blocked.

57. What are the layers of the OSI model?
    * The 7 Layers of the OSI
      * Layer 7 - Application.
      * Layer 6 - Presentation.
      * Layer 5 - Session.
      * Layer 4 - Transport.
      * Layer 3 - Network.
      * Layer 2 - Data Link.
      * Layer 1 - Physical.

57. How would traceroute help you find out where a breakdown in communication is?
    * Traceroute uses the TTL field in an IP header of a packet to determine how many "hops" a packet as traversed through a network. An analyst would be able to determine if a packet was dropped, where transmission lagged and possibly identify an anomalous route that might signal DNS poisoning/spoofying. 

## Security Leadership

58. How do you ensure that solution architects develop secure solutions?

59. What training do solution architects need to have in regards to IT security? What about developers?

60. How do you sell the value of IT security initiatives to executive management?

61. How do you ensure that a solution continues to be resilient in the face of evolving threats?

62. How do you avoid implementing overly complex or unnecessary security mechanisms?

63. Have you been involved with the governance of information security? What was your role? What did you accomplish?

64. Can you describe the laws and regulations that have a significant impact to information security at our organization?

65. What is the relationship between information security and privacy laws?

66. What is security level management?

67. How do you ensure that security management is transparent and measurable?

68. Can you outline the typical responsibilities of a Chief Security Officer (CSO)?

69. Can you give me an example of some emerging trends in information security that you're keeping an eye on?

## Experience

70. Have you developed an incident response plan?

71. Have you been involved in supporting incident investigations? What was your role? What was the outcome?

72. Have you performed a risk analysis and evaluation? How did you go about it? What stakeholders did you involve?

73. Have you performed a threat assessment? What factors did you consider?

74. Have you performed a vulnerability assessment? What types of vulnerabilities are most difficult to identify?

75. In the context of a vulnerability assessment, how do you calculate the probability that a vulnerability will be exploited?
    * The Common Vulnerability Scoring System (CVSS) is a free and open industry standard for assessing the severity of computer system security vulnerabilities. CVSS attempts to assign severity scores to vulnerabilities, allowing responders to prioritize responses and resources according to threat.
    * Exploit Prediction Scoring System (EPSS)

76. Can you give me an example of a time you identified and implemented controls to mitigate a risk? How did you evaluate the controls?

77. How do you stay up-to-date with technology? For example, how do you keep up with new information security threats?

## Cryptography

78. How does the SSL Protocol work?

79. What is the difference between symmetric-key cryptography and public-key cryptography?
    * Symmetric cryptography: 1 key for both encryption and decryption.
    * Asymmetric cryptography: 2 keys, a public and a private key. can be used two ways:. one way for confidentiality and another for integrity.

80. Can you give me an overview of how public-key cryptography works?

81. What is the difference between the encryption standards AES and DES?

82. What is the role of digital certificates in encryption?

83. What encryption mechanisms would you recommend to an organization that wants to encrypt its outgoing emails?

84. Can you give me an overview of IPsec? What is its purpose?

85. Does IPsec replace the need for SSL?

## Security Incident Management
86. What are the components of ITIL incident management?

87. If our organization experienced a major security incident, what steps should we take to manage the incident?

88. Can you describe the responsibilities of an incident manager?

## Threats

89. In your opinion, what are the top five information security threats facing an organization such as ours?

90. What is a man-in-the-middle attack?

91. Can you give me an example of cross-site scripting?

92. What is SQL injection? How is it prevented?

93. What is a buffer overflow?

94. What is clickjacking?

## Vulnerabilities

95. What is a insecure direct object reference? Why is it a problem?

96. Why is it important to validate redirects and forwards?

97. What are some common security vulnerabilities at the information storage level?

98. What are some common security vulnerabilities at the transport level?

99. How can improper error handling expose security vulnerabilities? How?

## Physical Security Integration
100. Can you give me a few examples of physical security integration?

101. What is social engineering? How common is it?

102. How would you secure an office environment? What about a data center?
