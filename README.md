# Assessing Common Attack Vectors

**Author**: Osamudiamen Eweka  
**Course**: CYB-605-Z2 Principles of Cybersecurity  
**Institution**: Utica University

## Overview

This lab focuses on exploring common attack vectors, including injection attacks, malware, denial-of-service (DoS), and social engineering. The exercises involve hands-on experience with tools like OWASP Juice Shop, Metasploit, and the Social Engineering Toolkit (SET), simulating real-world attack scenarios. Participants gain practical skills in executing and defending against these attacks.

## Objectives

- Understand the key principles behind common attack vectors, including SQL Injection, Cross-Site Scripting (XSS), and malware.
- Perform hands-on exercises simulating these attacks and gain insights into their execution and prevention.
- Learn how to craft and execute social engineering attacks and analyze their effectiveness.
- Understand defensive measures against these attack vectors.

## Lab Setup

### Lab Environment Details

The lab setup includes the following virtual machines, software, and utilities:

- **Virtual Machines**:
  - vWorkstation (Windows Server 2016)
  - pfSense (FreeBSD-based firewall)
  - WebServer01 (Ubuntu 20)
  - AttackLinux01 (Kali Linux)
  - TargetWindows02 (Windows Server 2019)
  - TargetLinux02 (Ubuntu 20)

- **Software & Tools**:
  - OWASP Juice Shop
  - Firefox Web Developer Tools
  - Metasploit Framework
  - Social Engineering Toolkit (SET)
  - Thunderbird

## Hands-On Demonstrations

### 1. Perform an Injection Attack
Participants executed SQL Injection and Cross-Site Scripting (XSS) attacks on the OWASP Juice Shop web application. This segment illustrated how attackers can exploit vulnerabilities in web applications to gain unauthorized access or manipulate data.

### 2. Perform a Malware Attack
Using the Metasploit Framework, participants created and deployed reverse shell malware. This exercise demonstrated how attackers can use reverse shells to bypass firewalls and gain control over a victim's system.

### 3. Perform a Distributed Denial-of-Service (DDoS) Attack
Participants simulated a DDoS attack using a botnet, disrupting a target website by overwhelming it with traffic. The lab illustrated the effectiveness of DDoS attacks and the challenges in defending against them.

### 4. Perform a Social Engineering Attack
Participants crafted and executed a spear phishing email using the Social Engineering Toolkit (SET). The lab emphasized the psychological tactics used in social engineering and how attackers can deceive victims into revealing sensitive information.

## Challenge and Analysis

### Defensive Measures Against Common Attack Vectors

- **Injection Attacks**: Implement input validation, parameterized queries, and regular patching of web applications to prevent injection attacks.
- **Malware Attacks**: Deploy strong endpoint protection and conduct regular security patching to prevent malware attacks.
- **Denial-of-Service (DoS) Attacks**: Utilize traffic scrubbing, anomaly detection, load balancing, and traffic shaping to mitigate DoS attacks.
- **Social Engineering Attacks**: Provide employee training and awareness programs, and implement multi-factor authentication (MFA) to protect against social engineering.

### Research on Additional Attack Vectors
Participants researched additional attack vectors and recommended defensive measures, further expanding their understanding of cybersecurity threats.

## Conclusion

This lab provided a comprehensive exploration of various attack vectors, giving participants hands-on experience in executing and mitigating these attacks. By understanding the mechanics of these threats and applying appropriate defensive measures, participants are better equipped to protect their organizations from cybersecurity breaches.

## References

- Kim, D. (2021). *Fundamentals of Information Systems Security + Cloud Labs*. Jones & Bartlett Learning.
- Jones & Bartlett (2024). *Assessing Common Attack Vectors*. Jones and Bartlett Learning Virtual Lab. URL: https://jbl-lti.hatsize.com/startlab
- Levy, M. (2023). *What is a Reverse Shell | Examples & Prevention Techniques*. Imperva. https://www.imperva.com/learn/application-security/reverse-shell/
- Sundar, V. (2023). *How to Prevent SQL Injection Attacks*. Indusface. https://www.indusface.com/blog/how-to-stop-sql-injection/

For a complete list of references, please refer to the full lab report.
