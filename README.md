# FOUNDATIONS_CYBERSECURITY
## Overview
This write-up documents the foundational topics I completed at the start of my cybersecurity journey.  
The goal was to understand core security concepts, set up a safe practice environment, and begin learning with the right mindset.

## Topics Completed
- Starting Out in Cyber Security
- Tutorial: How to use AttackBox
- Local Machine + OpenVPN setup
- Learning Cyber Security
- Security Principles
- The CIA Triad

## 1) Starting Out in Cyber Security
I began with an introduction to cybersecurity as a field, including common domains such as:

Network Security: Protects networks and data in transit from unauthorized access, misuse, or attacks (e.g., firewalls, IDS/IPS, segmentation, secure protocols).

Web Security: Protects websites and web applications from vulnerabilities like SQL injection, XSS, CSRF, and broken authentication.

Cloud Security: Secures cloud-based infrastructure, apps, and data using proper configuration, identity/access control, encryption, and continuous monitoring.

Defensive Security (Blue Team): Focuses on prevention, detection, and response to attacks—monitoring logs, hardening systems, managing incidents, and improving resilience.

Offensive Security (Red Team): Simulates real attackers to find weaknesses before criminals do—through penetration testing, adversary emulation, and security assessments (with permission).

### Key takeaway
Cybersecurity is not just “hacking”; it is about protecting systems, data, and users through prevention, detection, and response.

## 2) Tutorial on Using AttackBox
I learned how to use AttackBox as a browser-based lab machine for security training.
<img width="1366" height="675" alt="Screenshot (446)" src="https://github.com/user-attachments/assets/a2d73a16-bd5c-4160-ace7-572f899a451b" />
<img width="1366" height="634" alt="Screenshot (447)" src="https://github.com/user-attachments/assets/7bcc61a4-b710-409b-b239-b724f9f6bd7b" />



### What I understood
- AttackBox provides a pre-configured environment with common security tools.
- It helps avoid local installation issues when starting out.
- It is useful for hands-on labs and CTF-style practice.

### Key takeaway
Using a ready lab environment allows me to focus on learning concepts and tool usage rather than setup complexity.

## 3) Local Machine + OpenVPN
I practiced connecting my local machine to training labs through OpenVPN.
<img width="1366" height="681" alt="Screenshot (449)" src="https://github.com/user-attachments/assets/c3acb681-b2a5-4d9a-b170-ffd5206b28f1" />


### What I did
- Opened and connected VPN profile
  I used sudo openvpn <openvpnfile>
- Verified connection status
  <img width="1366" height="768" alt="Screenshot_2026-04-24_09_53_59" src="https://github.com/user-attachments/assets/ad33e970-1b1d-4d52-bfab-a057621bc67e" />

  <img width="1366" height="768" alt="Screenshot_2026-04-24_09_56_53" src="https://github.com/user-attachments/assets/00acebf2-4e2b-41bf-bae3-7f588faee1af" />

- Accessed lab targets through the VPN tunnel
  <img width="1366" height="768" alt="Screenshot_2026-04-24_09_57_32" src="https://github.com/user-attachments/assets/49b7d398-3e6f-4a9b-bd73-4f77a1ff8881" />


### Why this matters
VPN creates a secure tunnel between my machine and the lab environment, enabling safe and isolated practice.

## 4) Learning Cyber Security (Beginner Path)
I covered beginner learning structure and how to build practical skills gradually.

### Learning approach I’m following
- Learn theory first (security concepts)
- Practice in legal training labs
- Document progress after every session
- Focus on consistency over speed

## 5) Security Principles
I studied core security principles that guide real-world security decisions.

### Principles covered
- Confidentiality: prevent unauthorized access to information
- Integrity: protect data from unauthorized changes
- Availability: ensure systems/data are accessible when needed
- Least Privilege: users/processes get only the access they need
- Defense in Depth: use multiple layers of security controls

### Key takeaway
Strong security is built on layered controls and clear access boundaries, not a single tool.

## 6) The CIA Triad
I learned the CIA Triad as a foundational model in cybersecurity:

- **Confidentiality**: only authorized users can view data  
- **Integrity**: data remains accurate and unaltered  
- **Availability**: systems and data are accessible when required

### Practical examples
- Confidentiality: encryption, MFA, access controls
- Integrity: hashing, file integrity monitoring, change controls
- Availability: backups, redundancy, disaster recovery plans

## Challenges Faced
- Understanding many new terms in a short time
- Initial VPN/AttackBox workflow confusion
- Connecting theory to practical examples

## How I Solved Them
- Repeated core modules
- Took short notes after each lesson
- Focused on one concept at a time
- Practiced setup steps more than once

## Ethical Commitment
I will only practice in legal, authorized environments such as training labs, CTF platforms, and systems I own or have explicit permission to test.


## Reflection
This foundation phase helped me understand the “why” behind cybersecurity before diving deep into tools and attacks.  
I now have a working lab setup and a clearer roadmap for structured learning.
