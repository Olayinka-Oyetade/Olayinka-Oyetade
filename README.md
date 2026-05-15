# Olayinka Daniel Oyetade

**SOC Analyst | Toronto, Canada**

Splunk · Sysmon · MITRE ATT&CK · Incident Response · AWS Security . EDR/XDR(Microsoft Defender for Sentinel)

[olayinkaoyetade.com](https://olayinkaoyetade.com) · [LinkedIn](https://www.linkedin.com/in/olayinka-oyetade-0120171a2/) · contact@olayinkaoyetade2914@gmail.com

Open to **Tier 1 / Junior SOC Analyst** roles in Toronto, on-site or hybrid.

---

### About

I'm a SOC analyst with hands-on alert triage experience, sharpened through self-directed lab work in detection engineering and cloud security.

I build the detection environments I'd defend in production: ingesting endpoint logs, writing SPL queries mapped to MITRE ATT&CK, documenting investigations, and validating coverage by attacking my own labs.

What I'm focused on: helping SOC teams triage faster, document cleaner, and extend detection visibility across endpoint and cloud.

---

### Experience

**SOC Analyst Intern, 1 year**

- Triaged **20 to 50 security alerts per day** in Splunk, investigating endpoint, network, and authentication events to separate true positives from benign activity.
- Drove investigations end to end: alert review, log correlation across sources, IOC enrichment, and escalation decisions.
- Documented incidents in **ServiceNow** with timelines, affected assets, indicators of compromise, investigation notes, and recommended response. Tickets were clear enough for senior analysts to escalate without follow-up.
- Operated within an established SOC workflow: SLA-driven triage, escalation paths, shift handoffs, and weekly threat briefings.

---

### Featured Projects

**[Endpoint Detection Engineering | Splunk, Sysmon, MITRE ATT&CK](https://github.com/Olayinka-Oyetade/splunk-detection-lab)**

A Windows endpoint detection environment built with Splunk, Sysmon, and Windows Event Logs to simulate SOC-style investigations end to end.

- Ingested Sysmon and Windows Event Logs into Splunk for centralized analysis.
- Built dashboards covering process execution, PowerShell activity, authentication events, persistence, and lateral movement.
- Authored SPL queries mapped to MITRE ATT&CK techniques:
  * **T1059** Command and Scripting Interpreter
  * **T1003** Credential Access (LSASS)
  * **T1021** Remote Services / Lateral Movement
  * **T1547** Boot or Logon Autostart Execution
  * **T1055** Process Injection
- Documented each detection with investigation steps, expected log signatures, false positive considerations, and response recommendations.

**[Threat Intelligence Automation](https://github.com/Olayinka-Oyetade/threat-intel-automation)**

A Python-based IOC enrichment pipeline designed to accelerate alert investigation.

- Enriches IPs, domains, file hashes, and URLs against VirusTotal, AbuseIPDB, and URLhaus.
- Applies risk scoring across multiple sources to prioritize indicators.
- Persists results to SQLite for audit trails and repeatable review.
- Built around real SOC triage workflows, designed to plug into investigation rather than exist in isolation.

**[AWS Security Foundations](https://github.com/Olayinka-Oyetade/aws-security-foundations)**

Hands-on cloud security labs focused on visibility, logging, and detection.

- Working knowledge of IAM, S3 security, CloudTrail, CloudWatch, and VPC Flow Logs.
- Reviewed cloud activity logs to identify anomalous access patterns.
- Building toward GuardDuty-based cloud threat detection.

---

### Skills

**SIEM & Detection**
Splunk, SPL, Sysmon, Windows Event Logs, Dashboards, Alerts, MITRE ATT&CK mapping, Detection logic

**Incident Response**
Alert triage, IOC enrichment, Escalation decisions, ServiceNow documentation, Timeline reconstruction

**Cloud Security**
AWS IAM, EC2, S3, CloudTrail, CloudWatch, VPC Flow Logs, Shared responsibility model

**Scripting**
Python, PowerShell, Bash

**Frameworks**
MITRE ATT&CK, NIST CSF, Cyber Kill Chain

**Currently learning**
Terraform, AWS GuardDuty, Sigma rules, CompTIA Security+

---

### What I bring

- **Alert triage from hour one.** I've handled 20 to 50 alerts daily in a live SOC. Comfortable picking up the queue without extended ramp-up.
- **Documentation that holds up.** My ServiceNow tickets were written to a standard senior analysts could escalate from directly. Clean documentation reduces context loss across shifts.
- **Splunk fluency.** SPL queries, dashboard building, and alert investigation without hand-holding for day-to-day work.
- **Cloud-aware.** Comfortable with AWS logging sources (CloudTrail, VPC Flow) from day one, which matters for any team operating in or migrating to cloud.
- **Builds to understand.** Every concept I work with, I lab. New tool or detection technique on the team? I'll spin up an environment to test it.
