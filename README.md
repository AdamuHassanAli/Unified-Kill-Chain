# Unified-Kill-Chain Lab
<b>Platform:</b> TryHackMe | <b>Type:</b> Hands-On Lab | <b>Focus:</b> Advanced Threat Modeling, Attack Lifecycle Analysis, Defensive Strategies
 
## Overview:
In this lab, I explored the </b>Unified Kill Chain (UKC)</b> framework, a modern and comprehensive attack lifecycle model that expands upon the Lockheed Martin Cyber Kill Chain and MITRE ATT&CK. The UKC consists of </b>18 distinct phases</b> that cover every step of a cyberattack, offering deeper visibility into complex threat scenarios.

The framework helps defenders align detection, prevention, and response strategies across an extended set of attacker actions.

Key aspects covered include:
- <b>Reconnaissance:</b> Gathering information about targets using passive and active methods.
- <b>Weaponization:</b> Developing malicious payloads tailored to exploit identified vulnerabilities.
- <b>Delivery:</b>  Transmitting the payload to the target environment.
- <b>Exploitation:</b> Executing the malicious code to breach the system.
- <b>Persistence:</b> Establishing a foothold to maintain access over time.
- <b>Defense Evasion:</b> Employing techniques to avoid detection by security measures.
- <b>Command & Control (C2):</b> Establishing communication channels to control compromised systems.
- <b>Lateral Movement:</b> Navigating through the network to access additional systems.
- <b>Exfiltration:</b> Extracting sensitive data from the target environment.
- <b>Objectives:</b> Achieving the attacker's end goals, such as data theft or system disruption.

The UKC's detailed approach allows for a more nuanced understanding of complex attack scenarios, enabling defenders to anticipate and mitigate threats effectively. 
## What I Learned:
- How to map attacker actions to the correct phase of the Unified Kill Chain
- How each UKC phase contributes to a more complete understanding of adversary behavior
- Understood how the UKC complements other frameworks like MITRE ATT&CK, providing a more holistic view of cyber threats.
- Developed strategies to detect and respond to threats at various stages of the attack lifecycle.
- How granular threat modeling helps in prioritizing security efforts more effectively
- Where MITRE ATT&CK fits in as a tool to support specific phases with technique-level detail

## Skills Gained:
- Advanced Threat Analysis: Enhanced ability to analyze and interpret complex attack patterns.
- Incident Response Planning: Improved skills in developing effective response strategies to mitigate cyber threats.
- Security Framework Application: Proficient in applying the UKC framework to real-world scenarios for better threat detection and prevention.
- Network Defense Techniques: Strengthened knowledge of techniques to protect networks against sophisticated attacks.
- Framework integration (Kill Chain, MITRE ATT&CK, UKC)

## Practical Scenario
<b>Platform:</b> TryHackMe | <b>Type:</b> Practical Scenario | <b>Focus:</b> Unified Kill Chain Mapping, Threat Phase Analysis

## Summary:
This hands-on exercise simulated a complete cyberattack scenario. I deployed a static site environment where I matched specific attacker actions to their correct phases in the Unified Kill Chain. This simulated a real-world cyber intrusion, requiring deep understanding of adversary behavior across the extended attack lifecycle.

## Key Objectives:
- Understand and apply all 18 phases of the Unified Kill Chain
- Accurately classify adversary actions based on behavioral context
- Use threat intelligence and attack patterns to support analysis
- Strengthen my ability to detect, map, and report multi-phase attacks

## What I Did:
I completed a practical challenge by mapping attacker behaviors to their Unified Kill Chain phases. These included:
- <b>Reconnaissance</b> – The attacker uses tools to gather information about a system
- <b>Persistence</b> – The attacker installs a malicious script to allow them remote access at a later date
- <b>Command and Control (C2)</b> – The hacked machine is being controlled from an attacker's own server
- <b>Pivoting</b> – The attacker uses the hacked machine to access other servers on the same network
- <b> Action & Objectives</b> – The attacker steals a database and sells this to a 3rd party

<p align="center">
I matched <b>Reconnaissance</b> as the action of the attackers who's uses tools to gather information about a system: <br/>
<img src="https://github.com/AdamuHassanAli/Unified-Kill-Chain/blob/main/Images/001%20Reconnaissance.jpeg?raw=true"/>
<br/>
<br/>

<p align="center">
I matched <b> Persistence </b> as the action of the attackers who's installs a malicious script to allow them remote access at a later date : <br/>
<img src="https://github.com/AdamuHassanAli/Unified-Kill-Chain/blob/main/Images/002%20Persistance.jpeg?raw=true"/>
<br/>
<br/>

<p align="center">
I matched <b>  Command and Control </b> as the action of the attacker who's The hacked machine is being controlled from an attacker's own server : <br/>
<img src="https://github.com/AdamuHassanAli/Unified-Kill-Chain/blob/main/Images/003%20Command%20%20&%20Control.jpeg?raw=true"/>
<br/>
<br/>

 <p align="center">
I matched <b> Pivoting </b> as the action of the attacker who's The attacker uses the hacked machine to access other servers on the same network : <br/>
<img src="https://github.com/AdamuHassanAli/Unified-Kill-Chain/blob/main/Images/004%20Pivoting.jpeg?raw=true"/>
<br/>
<br/>

 <p align="center">
I matched <b>  Action & Objectives </b> as the action of the attacker who's steals a database and sells this to a 3rd party : <br/>
<img src="https://github.com/AdamuHassanAli/Unified-Kill-Chain/blob/main/Images/005%20Action%20&%20Objectives.jpeg?raw=true"/>
<br/>
<br/>

 <p align="center">
I Successfuly <b> Catched the Flag  </b> of the Lab Activity: <br/>
<img src="https://github.com/AdamuHassanAli/Unified-Kill-Chain/blob/main/Images/006%20The%20Flag%20Cacthed.jpeg?raw=true"/>
<br/>
<br/>
 
## Outcome: 
Completing this lab has significantly improved my capability to understand and counteract sophisticated cyber threats. By mastering the Unified Kill Chain framework, I am better equipped to anticipate attacker moves, implement effective defenses, and contribute to a proactive cybersecurity posture within any organization.



