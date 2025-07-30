# Elastic SIEM Lab – Basic SOC Simulation

**Hands-On Project: Building a Simple SIEM with Elasticsearch, Logstash, and Kibana (ELK Stack)**  
🔗 [Original Lab Guide](https://medium.com/@aali23/a-simple-elastic-siem-lab-6765159ee2b2)

## Overview

As part of my journey toward breaking into cybersecurity, I wanted hands-on experience with how Security Operations Centers (SOCs) detect and investigate threats. Following a Medium lab guide, I set up a simple **Elastic SIEM environment** using the ELK Stack to visualize and analyze security event data in real time.

This project helped me better understand how **logs become insight** and how defenders use dashboards and queries to monitor for suspicious activity. It was my first time working with log pipelines, and it gave me practical exposure to tools used by real-world SOC teams.

---

## What I Learned

###  SIEM Environment Setup
- Installed and configured **Elasticsearch**, **Logstash**, and **Kibana** on an Ubuntu VM
- Set up a basic **Logstash pipeline** to ingest and parse Windows event logs
- Deployed **Winlogbeat** on a Windows endpoint to forward logs to Logstash

###  Log Visualization
- Built **Kibana dashboards** to monitor real-time logs
- Queried for events like:
  - Failed login attempts
  - New user creation
  - Unexpected service installations
- Applied filters and search queries to isolate abnormal activity

### Security Concepts Practiced
- Gained exposure to **log analysis**, **event correlation**, and **SIEM dashboards**
- Saw how logs reveal behaviors tied to insider threats, privilege escalation, and lateral movement
- Simulated real-world detection use cases in a safe environment

---

##  Tools & Technologies

| Tool         | Purpose                              |
|--------------|--------------------------------------|
| Elasticsearch | Stores and indexes log data         |
| Logstash      | Parses and processes incoming logs  |
| Kibana        | Visualizes and queries logs         |
| Winlogbeat    | Ships Windows Event Logs to Logstash |
| Ubuntu/Linux  | Hosted the ELK stack                |
| Windows       | Log source endpoint                 |

---

##  Key Takeaways

- Built a functional SIEM lab from scratch
- Learned how to collect, parse, and analyze log data
- Strengthened my skills in both Linux and Windows environments
- Understood how SIEM tools help defenders investigate and detect real threats

---

##  Author

**Mekhi Sams**  
Aspiring Cybersecurity Professional | CompTIA Security+ Certified  
[LinkedIn](https://www.linkedin.com/in/mekhi-sams-98010723b/)


