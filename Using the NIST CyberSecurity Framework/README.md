# **Project: Incident Report Analysis (NIST CSF)**

## **Objective**

This project demonstrates the practical application of the NIST Cybersecurity Framework (CSF) by analyzing a Distributed Denial-of-Service (DDoS) attack. The objective was to break down the incident and the response efforts, mapping each phase to one of the five core functions of the NIST CSF.

## **Process Used**

The analysis followed the five functions of the NIST Cybersecurity Framework to structure the response to a DDoS attack that flooded the network with ICMP packets:

* **Identify:** The investigation identified that the attack vector was an unconfigured firewall that allowed a flood of ICMP pings.  
* **Protect:** To protect against future incidents, new firewall rules were implemented to limit ICMP traffic and check for spoofed IP addresses.  
* **Detect:** Network monitoring software was set up to detect and alert on abnormal traffic patterns.  
* **Respond:** During the incident, an Intrusion Detection/Prevention System (IDS/IPS) was used to filter malicious ICMP traffic.  
* **Recover:** The final step involved the restoration of all critical network services affected by the attack.

## **Skills Demonstrated**

* **NIST CSF Application:** Practical use of the framework to guide and analyze an incident response process.  
* **Incident Analysis:** Deconstructing a security incident to understand its cause, impact, and resolution.  
* **DDoS Mitigation:** Understanding and applying common techniques to defend against DDoS attacks.  
* **Network Security:** Recommending and implementing firewall rules and monitoring solutions.