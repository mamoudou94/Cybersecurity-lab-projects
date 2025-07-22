# 🔐 Cybersecurity Lab Projects – Mamoudou Barry

Welcome to my SOC Analyst Lab portfolio. This repository showcases real-world, enterprise-grade projects built within a custom virtual home lab. Each project demonstrates operational cybersecurity skills relevant to SOC, blue team, and security engineering roles—including intrusion detection, alert triage, secure cloud architecture, and SIEM alerting with threat correlation.

---

## 👨🏽‍💻 About Me

I’m **Mamoudou Barry**, a cybersecurity professional with 3+ years of software engineering experience, transitioning into threat detection and defensive security engineering. I specialize in secure coding, SIEM pipelines, and operational alert handling across on-prem and cloud environments.

I hold certifications in **AWS Cloud Practitioner** and **CompTIA Security+**, and I’m actively pursuing **CySA+** to deepen my threat analysis and incident response capabilities. My work includes cloud-native development, secure REST APIs, adversary simulations, and alert triage using Elastic and Splunk.

---

## 🧠 Skills & Tools

- **Threat Detection & Analysis**: Security Onion (Elastic Stack, Kibana), Splunk, Suricata, Wireshark, Tcpdump, Graylog
- **SIEM & Alerting**: SPL queries, Elastic rules, pfSense IDS/IPS, log correlation and dashboarding
- **Offensive Security Simulation**: Nmap, Hydra, Msfvenom, Metasploit, Burp Suite
- **Cloud Security & Architecture**: AWS IAM, EC2, Lambda, S3, VPC, API Gateway, CloudTrail, CloudWatch
- **Programming & DevSecOps**: Python, Java, TypeScript, Docker, Linux, REST APIs, CI/CD
- **Database & Storage**: MySQL, SQLite

---

## 🧪 Lab Environment

Built on **VMware Workstation (Windows 11)** with the following virtualized systems:

- `Security Onion`: Elastic Stack (Kibana, Elasticsearch, Logstash, Wazuh) for alerting, triage, and case creation
- `pfSense`: Dual NIC setup (NAT + Host-Only) with IDS/IPS (Snort, Suricata)
- `Kali Linux`: Attacker simulation environment (host-only)
- `Ubuntu`:  Victim & SIEM pipeline (Splunk, Graylog), syslog forwarding, and plugin analysis
- `Windows 10`: Victim simulation for phishing and lateral movement testing

---

## 📁 Projects

| Folder Name                                         | Description |
|----------------------------------------------------|-------------|
| Centralized Log Monitoring & Threat Detection       | Built Splunk and Graylog SIEM pipelines with pfSense log ingestion. Created SPL queries to detect brute-force attacks and access anomalies. |
| Elastic Alert Triage & Case Management              | Triaging alerts generated in Security Onion using Elastic/Kibana. Creating and managing incident cases based on threat signatures. |
| Network Scan Detection & Analysis                   | Captured and investigated Nmap traffic using Wireshark and tcpdump. Identified scan types and attacker behavior. |
| Firewall Rule Testing & Validation                  | Configured pfSense firewall policies. Simulated intrusions to test and validate detection in Suricata and Snort. |
| Ethical Phishing Simulation                         | Used Msfvenom payloads and Metasploit in a secure environment to simulate phishing attacks and validate detection pipelines. |

---

## 📫 Contact

- 🖇 [LinkedIn](https://www.linkedin.com/in/mamoudou-barry-5a211321a)
- 📧 Email: mamoudoudjogobarry@gmail.com

---

> ⚠️ All simulations were performed in a fully isolated environment for educational and professional validation only. Projects reflect hands-on implementation aligned with SOC, SIEM roles.
