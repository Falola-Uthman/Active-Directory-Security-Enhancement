# Active Directory Security Enhancement
 
## Objective

In this personal development project, my objective was to create a realistic cybersecurity environment by configuring a set of interconnected virtual machines. This setup was intended to simulate network attacks and facilitate the real-time analysis of logs, thereby improving my capabilities in both offensive and defensive cybersecurity tactics. The hands-on experience of observing and responding to simulated attacks within this environment was crucial to my growth as a security analyst.

## Skills Learned

- Domain Administration: Gained experience in establishing domain controls and managing user credentials on Windows Server 2022.
- Endpoint Security: Applied practical knowledge in integrating and monitoring a domain-connected Windows 10 client within an Active Directory (AD) structure for threat monitoring.
- Log Analysis: Developed proficiency in aggregating and analyzing network logs using Splunk to derive insights into system events and potential security breaches.
- Penetration Testing: Acquired tactical skills in conducting structured attacks from a Kali Linux machine, enabling me to assess and validate security measures.
- Incident Analysis: Sharpened my forensic skills by utilizing Splunk for post-attack analysis to correlate events and dissect the attack process.
- Security Enhancement: Identified system vulnerabilities and attack patterns, which contributed to strengthening the network's defense strategies.

## Tools Used

- Windows Server 2022 VM: Configured as the Active Directory Domain Controller.
- Windows 10 VM: Operated as a client within the domain, forwarding logs for active threat monitoring.
- Splunk Enterprise (Server) VM: Employed for the aggregation and in-depth analysis of network logs.
- Kali Linux VM: Utilized for simulating adversary attacks to test the security of the network.
- Splunk Universal Forwarder: Implemented for real-time log transmission from the AD and Windows 10 VMs.
- Atomic Red Team: Planned future use for advanced simulations based on the MITRE ATT&CK framework.


## Steps

- Initial Setup and Configuration: Deployed Windows Server 2022 and Windows 10 virtual machines, establishing a domain controller and a network endpoint.
- Log Forwarding Setup: Integrated Splunk Universal Forwarder into the environment to facilitate continuous log transmission from the Windows machines.
- Attack Simulation: Executed a structured penetration test from the Kali Linux machine against the Windows 10 VM.
- Incident Observation & Log Analysis: Post-attack, engaged Splunk for thorough event analysis and forensics, studying the details of the simulated breach.
- Security Posture Review: Based on the insights gained, evaluated and enhanced the security measures, preparing for future assessments using Kali Linux and Atomic Red Team tools against the MITRE ATT&CK framework.


## Visual Representation of the SOC Automation Lab Workflow


![Draw](https://github.com/Falola-Uthman/Active-Directory-Security-Enhancement/assets/50869547/0308d907-9b89-4545-9a71-2c895eeba215)

Ref 1: Project System Achitecture.

![Domain created (uthman local)](https://github.com/Falola-Uthman/Active-Directory-Security-Enhancement/assets/50869547/bb4b20a5-619e-4aeb-a594-97d679fe6e4e)

Ref 2: Created Domain (uthman.local).

![Target Pc domain](https://github.com/Falola-Uthman/Active-Directory-Security-Enhancement/assets/50869547/b0090494-51d9-4b37-b3bf-e668cda141de)

Ref 3: Windows 10 VM connected to the created domain

![Splunk AD and Target-PC](https://github.com/Falola-Uthman/Active-Directory-Security-Enhancement/assets/50869547/22648dcb-f1bc-42e6-ac5c-5ab60eb06448)

Ref 4: Evidence of Active Directory and Target PC (Host) forwarding to splunk.

![crowbar brute force](https://github.com/Falola-Uthman/Active-Directory-Security-Enhancement/assets/50869547/b7595512-5450-4bd3-af30-5e599deb20f3)
Ref 5: Crowbar Brute Force attack on the Target PC (Host).

![Brute force result on splunk](https://github.com/Falola-Uthman/Active-Directory-Security-Enhancement/assets/50869547/dfd77c21-9416-4f0b-a923-177d4e8c31f5)
Ref 6: Brute Force logs in splunk.

![further evidence of kali](https://github.com/Falola-Uthman/Active-Directory-Security-Enhancement/assets/50869547/7c62ecd3-698d-4dc6-bec4-1bc0b5ec9efa)
Ref 7: Further Evidence of Brute Force attack on the Target PC (Host).

![evidence of kali](https://github.com/Falola-Uthman/Active-Directory-Security-Enhancement/assets/50869547/a5beaa8d-07de-42cb-a823-f78c6906a1f6)
Ref 8: Evidence of Attack Machine being kali.

![evidence of kali success](https://github.com/Falola-Uthman/Active-Directory-Security-Enhancement/assets/50869547/0bd8cb68-fdb4-46fd-a566-fdc9aca8e59e)
Ref 9: Evidence that the brute force attack was succesful.

This project has been instrumental in fostering a proactive approach to cybersecurity, providing me with invaluable insights into the application of security tools, and equipping me with the knowledge to enhance network security measures.
