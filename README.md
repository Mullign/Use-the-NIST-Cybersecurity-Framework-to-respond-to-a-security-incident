# Use-the-NIST-Cybersecurity-Framework-to-respond-to-a-security-incident

Activity Overview

In this activity, you will create an incident report using the knowledge you’ve gained about networks throughout this course to analyze a network incident. You will analyze the situation using the National Institute of Standards and Technology's Cybersecurity Framework (NIST CSF). The CSF is a voluntary framework that consists of standards, guidelines, and best practices to manage cybersecurity risk. Creating a quality cybersecurity incident report and applying the CSF can demonstrate a proactive approach to security, improve communication and transparency with stakeholders, and improve security practices within your organization. You can also add the incident report you create to your cybersecurity portfolio when  you complete it.

The CSF is scalable and can be applied in a wide variety of contexts. As you continue to learn more and refine your understanding of key cybersecurity skills, you can use the templates provided in this activity in other situations. Knowing how to identify which security measures to apply in response to business needs will help you determine which are the best available options when it comes to network security.

Be sure to complete this activity before moving on. In the next course item, you will be able to self-assess your response. After that, there will be a completed exemplar to compare to your own work. It will also provide an opportunity for you to answer rubric questions that allow you to reflect on key elements of your professional statement.

Scenario

Review the scenario below. Then, complete the step-by-step instructions.

You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

To address this security event, the network security team implemented: 

A new firewall rule to limit the rate of incoming ICMP packets

Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets

Network monitoring software to detect abnormal traffic patterns

An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

As a cybersecurity analyst, you are tasked with using this security event to create a plan to improve your company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). You will use the CSF to help you navigate through the different steps of analyzing this cybersecurity event and integrate your analysis into a general security strategy. We have broken the analysis into different parts in the template below. You can explore them here:

Identify security risks through regular audits of internal networks, systems, devices, and access privileges to identify potential gaps in security. 

Protect internal assets through the implementation of policies, procedures, training, and tools that help mitigate cybersecurity threats. 

Detect potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections. 

Respond to contain, neutralize, and analyze security incidents; implement improvements to the security process. 

Recover affected systems to normal operation and restore systems data and/or assets that have been affected by an incident.


Summary
the multimedia company experienced a Distributed Denial of Service (DDoS) attack that disrupted the organization’s internal network for approximately two hours. The attack was characterized by a flood of ICMP (Internet Control Message Protocol) packets, which overwhelmed network resources and caused service unavailability.
Identify
Incident Start: The attack began when a flood of ICMP packets overwhelmed the company’s network.
Immediate Impact: Normal internal network traffic was unable to access critical network resources due to network congestion.
Response:
The Incident Response Team blocked incoming ICMP traffic at the firewall.
Non-critical services were taken offline to preserve system resources.
Critical network services were restored to ensure business continuity.
Incident Duration: The incident lasted for approximately two hours before full recovery.


Protect
Blocked incoming ICMP packets at the firewall.
Temporarily shut down non-essential network services to focus resources on restoring critical services.
Initiated a full investigation to identify the source and nature of the attack.


Detect
Vulnerability: The DDoS attack exploited an unconfigured firewall, which allowed the ICMP flood to enter the network without being blocked or filtered.
Attack Method: The attacker utilized a DDoS attack using ICMP ping floods, overwhelming the company’s network by sending large volumes of packets from distributed sources. This disabled network services until proper mitigation measures were put in place.


Respond
Review and Harden Firewall Settings: Ensure all firewall rules are configured correctly to block unnecessary traffic, including ICMP packets, unless explicitly required for operational purposes.
Deploy Network Monitoring Tools: Implement continuous monitoring solutions to detect unusual traffic patterns that could indicate a DDoS attack or other malicious activities early on.
DDoS Protection Measures: Evaluate third-party DDoS protection solutions, such as Cloudflare or AWS Shield, to mitigate future risks from large-scale attacks.
Incident Response Drills: Conduct regular tabletop exercises and incident response drills focusing on DDoS scenarios to better prepare the team for handling future attacks.


Recover
Take Non-Critical Services Offline: Temporarily shut down non-essential services to reduce load and free up network resources for critical services.
Restore Critical Services: Focus on restoring mission-critical services first to minimize business impact. In this case, your organization restored network access and resumed operations after two hours.







