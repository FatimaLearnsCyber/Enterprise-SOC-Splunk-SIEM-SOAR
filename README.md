# Enterprise SOC with Splunk SIEM + Shuffle SOAR

**Enterprise-grade Blue Team Project** showcasing SIEM + SOAR engineering for real-world SOC workflows.

This project demonstrates how to build a **Enterprise high-class SOC lab** using Splunk, Sysmon, and Shuffle SOAR for automated detection, alerting, enrichment, and incident response.  
Designed to highlight **threat detection engineering, MITRE ATT&CK mapping, and security automation**.

---

## Project Overview

- **Splunk SIEM:** Installed & configured on Windows VM  
- **Sysmon:** Logging enriched Windows events (process creation, network connections, registry events)  
- **Detection Rules:** Custom SPL queries mapped to MITRE ATT&CK  
- **Alerting:** Email notifications + scheduled correlation searches  
- **SOAR Automation (Shuffle):** Alert enrichment & automated response  
- **Documentation:** Full step-by-step with screenshots for recruiters and technical validation  

---

## Current Progress

- Installed & configured **Splunk SIEM**  
- Enabled **Sysmon logging**  
- Wrote first detection rule: **Encoded PowerShell execution**  
- Configured **alert scheduling (every 5/15 min)**  
- Integrated **email notifications** (SMTP tested)  
- Built detection for **rundll32 suspicious execution**  

---

## Next Steps

- Expand SPL detections (Mimikatz, persistence, network exfil, etc.)  
- Connect Splunk → Shuffle SOAR for enrichment & automated actions  
- Build SOC dashboards in Splunk  
- Add playbooks for automated response (VirusTotal, AbuseIPDB, AD actions)  
- Finalize full documentation with diagrams & demo  

---

##  Documentation

Screenshots & step-by-step guides are stored in `docs/`  
Example:  
- Splunk installation setup  
- Sysmon configuration  
- Detection queries  
- Triggered alerts & email notifications  

---

## Resume-Ready Impact

This project demonstrates:  

- **Detection Engineering** → Writing custom correlation searches in Splunk  
- **SIEM Implementation** → Configuring alerts, dashboards, log sources  
- **SOAR Integration** → Automating triage & response with Shuffle  
- **MITRE ATT&CK Mapping** → Aligning detections to real adversary techniques  

---

##  Connect

If you found this useful or want to collaborate:  
https://www.linkedin.com/in/fatimamuhammad/  
Star this repo & follow for updates
