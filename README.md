# Honeypot-SIEM

## Objective

The Detection Lab project aimed to establish a controlled environment for simulating and detecting cyber attacks using Azure Sentinel, a cloud-native Security Information and Event Management (SIEM) system. A honeypot is a security mechanism that creates a virtual trap in a controlled and safe environment to lure attackers. The primary focus was to ingest and analyze logs within a Security Information and Event Management (SIEM) system to mimic real-world attack scenarios. This hands-on experience was designed to deepen understanding of network security, attack patterns, and defensive strategies. 

### Skills Learned

- Advanced understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used
- Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Network analysis tools (such as Wireshark) for capturing and examining network traffic.
- Create realistic network traffic and attack scenarios.
- Custom Powershell Script written by Josh Madakor

## 
<img width="449" alt="Screen Shot 2024-05-31 at 10 33 20 AM" src="https://github.com/kilahj/Honeypot-SIEM/assets/99774720/8761f159-4fe2-46ba-85db-8e73119b7dec">
<img width="467" alt="Screen Shot 2024-05-31 at 10 34 03 AM" src="https://github.com/kilahj/Honeypot-SIEM/assets/99774720/771f572a-7af9-4067-9852-ab898272b888">

>Created a VM and turned off the external firewall to expose to internet to make VM seem enticing to hackers/attackers (honeypot)
##
<img width="467" alt="Screen Shot 2024-05-31 at 10 27 58 AM" src="https://github.com/kilahj/Honeypot-SIEM/assets/99774720/00c2abcc-8bd9-41fb-93d8-86a7c2580944">


<img width="449" alt="Screen Shot 2024-05-31 at 10 29 32 AM" src="https://github.com/kilahj/Honeypot-SIEM/assets/99774720/d8425d8b-aab9-4f5d-bdf2-5e7ba0ccde32">

>API Key provided by https://ipgeolocation.io/ to generate longitude and latitude for IP Address.


<img width="1350" alt="Screen Shot 2024-05-31 at 10 59 03 AM" src="https://github.com/kilahj/Honeypot-SIEM/assets/99774720/03d3bcbe-2fc1-4069-9b76-59e60035950c">

>The location with the highest amount of attacks came from Russia (10K attempts). Other locations included: China, Vietnam, Pakistan, etc. 

One takeaway from this project: many attackers attempted to gain access using common usernames such as "Admin" or "Administrator" or "test". It's extremely important to always create unique and strong passwords and usernames! Adding two-factor or multifactor authentication is another form of defense. 
