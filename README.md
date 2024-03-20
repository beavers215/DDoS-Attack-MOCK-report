# DDoS-Attack-MOCK-report
Incident report of DDoS attack
Incident: DDoS Attack

Description:
The "company" experienced a Distributed denial-of-service (DDoS) attack that disrupted normal network operations for approximately two hours. The attack targeted the company's internal network infrastructure, specifically exploiting a vulnerability in an unconfigured firewall. As a result, the network services became unresponsive due to an influx of Internet Control Message Protocol (ICMP) packets, rendering essential network resources inaccessible.

------------------------------------------------------------------

Details of the Incident:

Attack Vector: The malicious actor initiated the DDoS attack by flooding the company's network with ICMP pings, exploiting a firewall vulnerability that allowed excessive ICMP traffic to penetrate the network.

Impact: Normal internal network traffic was severely affected, disrupting essential network services. This disruption led to downtime and hindered the company's ability to carry out its operations effectively.

Response: The incident management team promptly responded by blocking incoming ICMP packets, shutting down non-critical network services, and restoring critical network operations. Additionally, the cybersecurity team investigated the incident, 
identifying the source of the attack and implementing measures to mitigate future risks.

------------------------------------------------------------------

Mitigation Measures Implemented:

Implement a new firewall rule to limit the rate of incoming ICMP packets.

Source IP address verification on the firewall to prevent IP address spoofing on incoming ICMP packets.

Network monitoring software will be deployed to detect abnormal traffic patterns and potential security incidents.

Installation of an Intrusion Detection/Prevention System (IDS/IPS) to filter out suspicious ICMP traffic.

------------------------------------------------------------------

Next Steps:

Conduct a thorough post-incident analysis to identify lessons learned and areas for improvement in the organization's cybersecurity posture.
Review and update security policies, procedures, and controls to strengthen resilience against similar cybersecurity threats in the future.
Provide ongoing training and awareness programs to educate employees about cybersecurity risks and best practices for maintaining a secure network environment.
