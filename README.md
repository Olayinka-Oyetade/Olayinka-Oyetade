# Olayinka Daniel Oyetade

**SOC Analyst | Toronto, Canada**

Splunk · Microsoft Sentinel · Microsoft Defender for Endpoint · Sysmon · MITRE ATT&CK · Incident Response · AWS Security

[olayinkaoyetade.com](https://olayinkaoyetade.com) · [LinkedIn](https://www.linkedin.com/in/olayinka-oyetade-0120171a2/) · olayinkaoyetade2914@gmail.com

**Tier 1 / Junior SOC Analyst** roles in Toronto, on-site or hybrid.

---

### About

I'm a SOC analyst with hands-on alert triage experience, sharpened through self-directed lab work in detection engineering and cloud security.

I build the detection environments I'd defend in production: ingesting endpoint logs, writing SPL and KQL queries mapped to MITRE ATT&CK, documenting investigations, and validating coverage by attacking my own labs.

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

**[Endpoint Detection Engineering | Splunk, Sysmon, MITRE ATT&CK](https://github.com/Olayinka-Oyetade/endpoint-detection-engineering)**

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

**[Microsoft Sentinel Threat Detection | Defender for Endpoint + KQL](https://github.com/Olayinka-Oyetade/sentinel-threat-detection)**

A cloud-native SIEM and XDR lab using Microsoft Sentinel and Microsoft Defender for Endpoint to investigate endpoint and identity threats.

- Connected Microsoft Defender for Endpoint as a data source into Microsoft Sentinel for unified detection visibility.
- Authored KQL detection rules covering credential dumping, suspicious PowerShell execution, and privilege escalation attempts.
- Built investigation workbooks for incident triage, alert correlation, and timeline reconstruction.
- Practiced full incident lifecycle: detection, investigation, containment recommendations, and structured documentation.
- Mapped detections to MITRE ATT&CK techniques for coverage visibility.

**[IOC Enrichment Pipeline](https://github.com/Olayinka-Oyetade/ioc-enrichment-pipeline)**

A Python-based IOC enrichment pipeline designed to accelerate alert investigation.

- Enriches IPs, domains, file hashes, and URLs against VirusTotal, AbuseIPDB, and URLhaus.
- Applies risk scoring across multiple sources to prioritize indicators.
- Persists results to SQLite for audit trails and repeatable review.
- Built around real SOC triage workflows, designed to plug into investigation rather than exist in isolation.

**[AWS Threat Detection | CloudTrail, GuardDuty, VPC Flow](https://github.com/Olayinka-Oyetade/aws-threat-detection)**

Hands-on cloud security project focused on visibility, logging, and detection across AWS services.

- Configured CloudTrail, CloudWatch, and VPC Flow Logs for centralized cloud activity monitoring.
- Reviewed cloud activity logs to identify anomalous access patterns and IAM abuse.
- Built toward GuardDuty-based threat detection across the AWS environment.
- Working knowledge of IAM, S3 security, EC2 hardening, and shared responsibility model.

---

### Skills

**SIEM**
Splunk, SPL, Microsoft Sentinel, KQL, Dashboard building, Alert tuning, Workbooks

**EDR / XDR**
Microsoft Defender for Endpoint, Microsoft Defender XDR, Sysmon, Endpoint telemetry analysis

**Incident Response**
Alert triage, IOC enrichment, Escalation decisions, ServiceNow documentation, Timeline reconstruction, Containment recommendations

**Detection Engineering**
MITRE ATT&CK mapping, Detection logic, False positive analysis, Rule tuning

**Cloud Security**
AWS IAM, EC2, S3, CloudTrail, CloudWatch, VPC Flow Logs, Shared responsibility model

**Scripting**
PowerShell, Bash

**Frameworks**
MITRE ATT&CK, NIST CSF, Cyber Kill Chain

**Currently learning**
Terraform, AWS GuardDuty, Sigma rules, CompTIA Security+

---

### What I bring

- **Alert triage from hour one.** I've handled 20 to 50 alerts daily in a live SOC. Comfortable picking up the queue without extended ramp-up.
- **SIEM and EDR fluency.** Comfortable writing SPL and KQL, building dashboards, and investigating alerts across Splunk, Microsoft Sentinel, and Defender for Endpoint without hand-holding.
- **Documentation that holds up.** My ServiceNow tickets were written to a standard senior analysts could escalate from directly. Clean documentation reduces context loss across shifts.
- **Cloud-aware.** Comfortable with AWS logging sources (CloudTrail, VPC Flow) from day one, which matters for any team operating in or migrating to cloud.
- **Builds to understand.** Every concept I work with, I lab. New tool or detection technique on the team? I'll spin up an environment to test it.
