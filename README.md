# Report on the Colonial Pipeline Ransomware Attack
Report (with sources) on the Colonial Pipeline Ransomware attack, propogated by the Revel Ransomware Group. The Malware, threat actors, response efforts, and additional developments and effects of the Cyber Attack that have had an impact on society and the industry.

https://docs.google.com/document/d/17kx5Fansvd8qryBY_ftdwRET2f5LszQV/view

# Other Ransomware/Malware Attacks

**Revel Ransomware Group (Responsible for Colonial Pipeline Hack) may be Back**

https://clark.com/protect-your-identity/cash-app-data-breach/

The revelation about the data breach is detailed in a U.S. Securities and Exchange Commission (SEC) report filed on behalf of Block, the parent company of Cash App.

https://www.sec.gov/ix?doc=/Archives/edgar/data/0001512673/000119312522095215/d343042d8k.htm

**Ronin Hack** on T-Mobile

https://www.wired.com/story/ronin-hack-lazarus-tmobile-breach-data-malware-telegram/

**Lockbit Ransomware Gang Lurked in a US Gov Network For Months**

https://www.bleepingcomputer.com/news/security/lockbit-ransomware-gang-lurked-in-a-us-gov-network-for-months/

**First Python Ransomware Attack Targeting Jupyter Notebooks**

https://blog.aquasec.com/python-ransomware-jupyter-notebook

**Chinese Hackers use VLC to Propagate Malware**

https://www.androidpolice.com/hackers-vlc-malware/

# Vulnerabilities (Zero Day and Others) 

**Mandiant says 2021 was a Record Year for Zero Day Exploits**

https://www.theregister.com/2022/04/23/zeroday_exploits_2021/

**Nginx Zero Day Vulnerability**

https://securityonline.info/nginx-zero-day-rce-vulnerability-alert/

**Researchers Detail Bug That Could Paralyze Snort Intrusion Detection System**

https://thehackernews.com/2022/04/researchers-detail-bug-that-could.html

# Various Cyber Security Frameworks and Lifecycles

### The OSINT Framework
The framework provides links to a large collection of resources for a huge variety of tasks from harvesting email addresses to searching social media or the dark web.

https://osintframework.com/
### The MITRE Att&ck Framework
The MITRE ATT&CK framework is a comprehensive matrix of tactics and techniques used by threat hunters, red teamers, and defenders to better classify attacks and assess an organization's risk.

https://attack.mitre.org/

### The CIA Triad
The three letters in "CIA triad" stand for confidentiality, integrity, and availability. The CIA triad is a common, respected model that forms the basis for the development of security systems and policies.

**Confidentiality** involves the efforts of an organization to make sure data is kept secret or private. To accomplish this, access to information must be controlled to prevent the unauthorized sharing of data—whether intentional or accidental. A key component of maintaining confidentiality is making sure that people without proper authorization are prevented from accessing assets important to your business. Conversely, an effective system also ensures that those who need to have access have the necessary privileges.

**Integrity** involves making sure your data is trustworthy and free from tampering. The integrity of your data is maintained only if the data is authentic, accurate, and reliable. Compromising integrity is often done intentionally. An attacker may bypass an intrusion detection system (IDS), change file configurations to allow unauthorized access, or alter the logs kept by the system to hide the attack. Integrity may also be violated by accident. Someone may accidentally enter the wrong code or make another kind of careless mistake. Also, if the company’s security policies, protections, and procedures are inadequate, integrity can be violated without any one person in the organization accountable for the blame. To protect the integrity of your data, you can use hashing, encryption, digital certificates, or digital signatures. For websites, you can employ trustworthy certificate authorities (CAs) that verify the authenticity of your website so visitors know they are getting the site they intended to visit. 

**Availability**  
Even if data is kept confidential and its integrity maintained, it is often useless unless it is available to those in the organization and the customers they serve. This means that systems, networks, and applications must be functioning as they should and when they should. Also, individuals with access to specific information must be able to consume it when they need to, and getting to the data should not take an inordinate amount of time. 

To ensure availability, organizations can use redundant networks, servers, and applications. These can be programmed to become available when the primary system has been disrupted or broken. You can also enhance availability by staying on top of upgrades to software packages and security systems. In this way, you make it less likely for an application to malfunction or for a relatively new threat to infiltrate your system. Backups and full disaster recovery plans also help a company regain availability soon after a negative event.

https://www.fortinet.com/resources/cyberglossary/cia-triad#:~:text=The%20three%20letters%20in%20%22CIA,of%20security%20systems%20and%20policies

### The Threat Intelligence Lifecycle
A process to transform raw data into finished intelligence for decision making and action. It guides a cybersecurity team through the development and execution of an effective threat intelligence program.

https://cyware.com/educational-guides/cyber-threat-intelligence/what-is-the-threat-intelligence-lifecycle-9981
### The Diamond Model
An approach employed by several information security professionals to authenticate and track cyber threats. According to this approach, every incident can be depicted as a diamond.

https://cyware.com/educational-guides/cyber-threat-intelligence/what-is-the-diamond-model-of-intrusion-analysis-5f02
### The Cyber Kill Chain
A cybersecurity model created by Lockheed Martin that traces the stages of a cyber-attack, identifies vulnerabilities, and helps security teams to stop the attacks at every stage of the chain.

https://www.lockheedmartin.com/en-us/capabilities/cyber/cyber-kill-chain.html

# Cyber Security Terms and Tenets
**HIDS vs NIDS and which one is better and why?**  
HIDS is host intrusion detection system and NIDS is network intrusion detection system. Both the systems work on the similar lines. It’s just that the placement in different. HIDS is placed on each host whereas NIDS is placed in the network. For an enterprise, NIDS is preferred as HIDS is difficult to manage, plus it consumes processing power of the host as well.

**What is port scanning?**  
Port scanning is the process of sending messages in order to gather information about the network, system etc. by analyzing the response received.

**What is the difference between a VA (Vulnerability Assessment) and a PT (Penetration Test)?**  
Vulnerability Assessments assess computers, systems, and networks for security weaknesses, also known as vulnerabilities. These scans are typically automated and give a beginning look at what could possibly be exploited. A penetration test attempts to actively exploit weaknesses in an environment. While a vulnerability scan can be automated, a penetration test requires various levels of expertise.

A penetration test simulates a hacker attempting to get into a business system through hands-on research and the exploitation of vulnerabilities. Actual analysts, often called ethical hackers, search for vulnerabilities and then try to prove that they can be exploited. Using methods like password cracking, buffer overflow, and SQL injection, they attempt to compromise and extract data from a network in a non damaging way. Penetration tests are an extremely detailed and effective approach to finding and remediating vulnerabilities in software applications and networks.

https://www.securitymetrics.com/blog/pentesting-vs-vulnerability-scanning-whats-difference

**When do you use tracert/traceroute?**  
In case you can’t ping the final destination, tracert will help to identify where the connection stops or gets broken, whether it is firewall, ISP, router etc.

**What is DDoS and its mitigation?**  
DDoS stands for distributed denial of service. When a network/server/application is flooded with large number of requests which it is not designed to handle making the server unavailable to the legitimate requests. The requests can come from different not related sources hence it is a distributed denial of service attack. It can be mitigated by analyzing and filtering the traffic in the scrubbing centers. The scrubbing centers are centralized data cleansing station wherein the traffic to a website is analyzed and the malicious traffic is removed.

**How do you handle Antivirus alerts?**  
Check the policy for the AV and then the alert. If the alert is for a legitimate file then it can be whitelisted and if this is malicious file then it can be quarantined/deleted. The hash of the file can be checked for reputation on various websites like virus total, malwares.com etc. AV needs to be fine-tuned so that the alerts can be reduced.

**What is a false positive and false negative in case of IDS?**  
When the device generated an alert for an intrusion which has actually not happened: this is false positive and if the device has not generated any alert and the intrusion has actually happened, this is the case of a false negative.

**Is a false positive or a false negative more acceptable?**  
False positives are more acceptable. False negatives will lead to intrusions happening without getting noticed.

# Articles I've Read to Become more Familiar with Cybersecurity Processes

### Open Source Intelligence - OSINT
The process of collecting and analyzing publicly available information that can be exploited by adversaries. The lifecycle consists of five setps: identifying, harvesting, processing, analyzing, and reporting.

https://www.sentinelone.com/cybersecurity-101/open-source-intelligence-osint/

### The Dark Web
An unregulated network of unindexed web content where activity is made anonymous through a variety of encryption and routing techniques. To access, users need a special browser, and they most commonly use Tor.

https://www.crowdstrike.com/cybersecurity-101/the-dark-web-explained/

### Data Anonymization
The process of protecting private or sensitive information by erasing or encrypting identifiers that connect an individual to stored data.

https://www.imperva.com/learn/data-security/anonymization/#:~:text=Data%20anonymization%20is%20the%20process,an%20individual%20to%20stored%20data.

### Attack Flow — Beyond Atomic Behaviors | by Jon Baker | MITRE-Engenuity
https://medium.com/mitre-engenuity/attack-flow-beyond-atomic-behaviors-c646675cc793
### Create custom analytics rules to detect threats with Microsoft Sentinel
https://docs.microsoft.com/en-us/azure/sentinel/detect-threats-custom
###  Log Parsing and Analysis in Sumo Logic 
https://www.sumologic.com/glossary/log-analysis/
