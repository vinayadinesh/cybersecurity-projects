
# Security Log Analysis & Threat Investigation

### Elasticsearch, Kibana & Apache NiFi

![Status](https://img.shields.io/badge/Status-Completed-success)
![Category](https://img.shields.io/badge/Category-Blue_Team-blue)
![Type](https://img.shields.io/badge/Type-Hands--on_Project-orange)

## 📌 Project Overview

This project was developed as part of my cybersecurity learning journey to gain practical experience in centralized log management, security event monitoring, and threat investigation.

The project focuses on building a log ingestion pipeline using Apache NiFi, indexing logs in Elasticsearch, and utilizing Kibana for visualization and security event analysis.

Through this project, I explored how raw log data can be transformed into meaningful security insights.

## 🎯 Project Objectives

- Build a centralized log ingestion pipeline.
- Understand log collection, processing, and indexing.
- Create dashboards and visualizations using Kibana.
- Analyze Windows security event logs.
- Investigate potentially suspicious activities.
- Map identified activities to the MITRE ATT&CK framework.

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Apache NiFi | Log ingestion and processing |
| Elasticsearch | Log indexing, storage, and searching |
| Kibana | Data visualization and log analysis |
| Syslog | Log collection |
| Windows EVTX | Security event investigation |
| MITRE ATT&CK | Threat technique mapping |

## 🔍 Security Investigation

As part of the investigation, I analyzed sample Windows security event logs to identify activities associated with account and group enumeration.

| Indicator | Details |
|---|---|
| Event ID | 4799 |
| Activity | Security-enabled local group membership enumeration |
| MITRE ATT&CK Tactic | Discovery |
| Technique | Permission Groups Discovery |
| Sub-technique | T1069.001 — Local Groups |

The investigation demonstrates how Windows security events can provide visibility into activities potentially associated with adversary discovery techniques.

However, group enumeration alone does not confirm malicious activity and requires additional contextual analysis.

## 📄 Project Report

The complete technical report contains:

- Project introduction and executive summary
- Environment setup
- Installation and configuration
- Apache NiFi pipeline implementation
- Elasticsearch integration
- Kibana dashboards and visualizations
- Windows security log analysis
- Investigation findings
- MITRE ATT&CK mapping
- Implementation screenshots

### [📥 View Full Technical Project Report (PDF)](./Project-Report.pdf)

## 🧠 Skills Demonstrated

- Centralized log management
- Security event monitoring
- Log ingestion and processing
- Security data visualization
- Windows event log analysis
- Threat investigation
- MITRE ATT&CK mapping
- Technical report preparation

## 💡 Learning Outcomes

This project helped me understand the relationship between log collection, data processing, visualization, and security investigations.

It also strengthened my understanding of how security analysts can use event logs to identify potentially suspicious behavior and contextualize findings using established threat intelligence frameworks.

## 🚀 Future Improvements

- Integrate real-time endpoint log sources.
- Develop automated detection rules.
- Implement security alerting mechanisms.
- Explore multi-source event correlation.
- Expand investigation use cases.

## ⚖️ Disclaimer

This project was conducted for educational purposes using a controlled lab environment and sample security logs.

---

**Project Status:** Completed

