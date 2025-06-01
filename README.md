# 🔐 Cybersecurity Lab Projects – Mamoudou Barry

Welcome to my SOC Analyst Lab Projects portfolio. This repository contains real-world, enterprise-grade projects built using a custom virtual home lab environment. The purpose of these projects is to demonstrate hands-on cybersecurity skills relevant to SOC roles and blue team operations, including intrusion detection, network traffic analysis, firewall configuration, and SIEM alerting.

---

## 👨🏽‍💻 About Me

I’m **Mamoudou Barry**, a cybersecurity professional with 3+ years of experience in software engineering and a deep focus on cloud security and threat detection. I’ve transitioned into cybersecurity with a passion for defending systems, analyzing network traffic, and responding to real-world security events. 

I hold an **AWS Cloud Practitioner certification** and am actively pursuing **CompTIA Security+**. I’ve completed secure cloud application deployments and ethical hacking labs in a controlled environment to understand adversary behavior and defensive engineering.

---

## 🧠 Skills & Tools

- **Security Monitoring & Analysis**: Wireshark, tcpdump, Graylog, pfSense IDS/IPS (Snort & Suricata)
- **Offensive Security Tools**: Nmap, Hydra, Metasploit, Msfvenom, Burp Suite
- **Cloud Security**: AWS IAM, EC2, Lambda, S3, VPC, API Gateway, CloudTrail, CloudWatch
- **Programming**: Python, Java, TypeScript
- **Infrastructure**: Docker, Git, Linux, REST APIs, SQLite, MySQL

---

## 🧪 Lab Environment

My lab is built with **VMware Workstation on Windows 11** and includes the following virtual machines:

- `pfSense` (2 NICs: NAT + Host-Only) with Suricata and Snort installed
- `Kali Linux` (1 NIC: Host-Only) for attacker simulations
- `Ubuntu` (1 NIC: Host-Only) for SIEM (Graylog), servers, or analysis
- `Windows 10` (1 NIC: Host-Only) for victim/end-user simulation

---

## 📁 Projects

| Project | Description |
|--------|-------------|
| [Centralized Log Monitoring & Threat Detection](./Centralized%20Log%20Monitoring%20%26%20Threat%20Detection) | Collect and analyze logs from multiple systems (pfSense, Windows, Ubuntu) using Graylog SIEM. Visualize login attempts, system events, and firewall logs in real-time. |
| [Detect and Investigate Network Scanning](./Detect%20and%20Investigate%20network%20scan) | Analyze PCAP files captured during Nmap scans using Wireshark and tcpdump. Identify scanning techniques, targeted ports, and infer attacker intent. |
| [Firewall Rule Testing](./Firewall-Rule-Testing) | Configure and validate pfSense firewall rules to block unauthorized access. Use Nmap from Kali to simulate attacks and verify dropped traffic using pfSense logs. |

---

## 📫 Contact

- 🖇 [LinkedIn](https://www.linkedin.com/in/YOUR-LINKEDIN-USERNAME)
- 📧 Email: mamoudoudjogobarry@gmail.com

---

> 🔐 This repository is meant for educational and professional demonstration purposes only. All tests and attacks were performed in a fully isolated lab.
