## Olayinka Daniel Oyetade

SOC Analyst — Toronto, Canada  
Splunk · Sysmon · MITRE ATT&CK · Incident Response · AWS Security

---

### About

I'm a SOC analyst with hands-on alert triage experience, sharpened through 
self-directed lab work in detection engineering and cloud security.

I build the kind of detection environments I'd defend in production — 
ingesting endpoint logs, writing SPL queries mapped to MITRE ATT&CK, 
documenting investigations, and validating coverage by attacking my own labs.

What I'm focused on: helping SOC teams triage faster, document cleaner, 
and extend detection visibility across endpoint and cloud.

---

### Experience

**Security Operations Analysts — 1 year **

- Triaged **20–50 security alerts per day** in Splunk, investigating endpoint, 
  network, and authentication events to separate true positives from benign activity.
- Drove investigations end-to-end: alert review, log correlation across sources, 
  IOC enrichment, and escalation decisions.
- Documented incidents in **ServiceNow** — timelines, affected assets, indicators 
  of compromise, investigation notes, and recommended response. Tickets were 
  clear enough for senior analysts to escalate without follow-up.
- Operated within an established SOC workflow: SLA-driven triage, escalation 
  paths, shift handoffs, and weekly threat briefings.

---

### Featured Projects

#### Splunk Detection Lab

A Windows endpoint detection environment built with **Splunk, Sysmon, and Windows 
Event Logs** to simulate SOC-style investigations end-to-end.

- Ingested Sysmon and Windows Event Logs into Splunk for centralized analysis.
- Built dashboards covering process execution, PowerShell activity, authentication 
  events, persistence, and lateral movement.
- Authored SPL queries mapped to MITRE ATT&CK techniques:
  - **T1059** — Command and Scripting Interpreter
  - **T1003** — Credential Access (LSASS)
  - **T1021** — Remote Services / Lateral Movement
  - **T1547** — Boot or Logon Autostart Execution
  - **T1055** — Process Injection
- Documented each detection with investigation steps, expected log signatures, 
  false positive considerations, and response recommendations.

#### Threat Intelligence Automation

A Python-based IOC enrichment pipeline designed to accelerate alert investigation.

- Enriches IPs, domains, file hashes, and URLs against VirusTotal, AbuseIPDB, 
  and URLhaus.
- Applies risk scoring across multiple sources to prioritize indicators.
- Persists results to SQLite for audit trails and repeatable review.
- Designed around real SOC triage workflows — built to plug into investigation, 
  not exist in isolation.

#### AWS Security Foundations

Hands-on cloud security labs focused on visibility, logging, and detection.

- Working knowledge of IAM, S3 security, CloudTrail, CloudWatch, and VPC Flow Logs.
- Reviewed cloud activity logs to identify anomalous access patterns.
- Building toward GuardDuty-based cloud threat detection and Terraform-deployed 
  lab environments.

---

### Skills

**SIEM & Detection**  
Splunk · SPL · Sysmon · Windows Event Logs · Dashboards · Alerts · 
MITRE ATT&CK mapping · Detection logic

**Incident Response**  
Alert triage · IOC enrichment · Escalation decisions · ServiceNow documentation · 
Timeline reconstruction

**Cloud Security**  
AWS IAM · EC2 · S3 · CloudTrail · CloudWatch · VPC Flow Logs · 
Shared responsibility model

**Scripting**  
Python · PowerShell · Bash

**Frameworks**  
MITRE ATT&CK · NIST CSF · Cyber Kill Chain

**Currently learning**  
Terraform · AWS GuardDuty · Sigma rules · Detection-as-Code · CompTIA Security+

---

### What I bring on day one

- **Alert triage capacity from hour one.** I've handled 20–50 alerts daily in a 
  live SOC. New analysts typically need 4–6 weeks of ramp before contributing to 
  the queue. I shorten that window.
- **Documentation that doesn't need rewriting.** My ServiceNow tickets were 
  written to a standard senior analysts could escalate from directly. Clean 
  documentation reduces context loss across shifts.
- **Splunk fluency.** SPL queries, dashboard building, and alert investigation — 
  no hand-holding required for day-to-day work.
- **Cloud-aware from the start.** Most junior SOC candidates think in on-prem 
  terms. I'm already comfortable with AWS logging sources (CloudTrail, VPC Flow), 
  which matters for any team operating in or migrating to cloud.
- **Lab-first mindset.** Every concept I learn, I build. If your team adopts a 
  new tool or detection technique, I'm the analyst who'll spin up a lab over 
  the weekend to test it.

---

### Currently

 Toronto, Canada  
 https://olayinkaoyetade.com
 [LinkedIn](your-linkedin-url-here)  
 olayinkaoyetade2914@gmail.com

Open to **Tier 1 / Junior SOC Analyst** roles in the Toronto area, on-site or hybrid.
