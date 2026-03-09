# 🛡️ Incident Response Plan
This Incident Response Plan serves as a practical application of the **NCSC framework**, produced as a formal requirement for the **NCFE Level 3 in Cyber Security Practices**.

---

## 📖 1. Purpose and Scope

* **Purpose:** To provide a clear and effective way to detect, respond, and recover from any cyber security incidents that could harm an organisation's data or system.
* **Scope:** The plan applies to all systems, data, networks, and people who work for or with the organisation.
* **Inclusions:** This includes staff, contractors, and third parties that use IT or handle data.

## ⚖️ 2. Legal & Regulations Context

* **UK GDPR/Data Protection Act 2018:** Requires an organisation to report data breaches and protect personal information.
* **NIS Regulations:** Applies to key services including energy, transport, and healthcare, as well as digital service providers.
* **Objective:** To ensure organisations have strong cyber security defences.
* **Cyber Essentials/Plus:** Security controls that organisations can follow to protect against common cyber threats.
* **NCSC Guidance:** Official UK advice to help individuals or organisations handle and respond to incidents.



---

## 👥 3. Incident Response Team (IRT)

| Role | Responsibilities | Back Up |
| --- | --- | --- |
| **CISO or Head of InfoSec** | Leads the response team and reports to shareholders | IT Manager 
| **Security Analyst** | Detects, investigates, and triages suspected threats | Security Engineer 
| **IT Operation Lead** | Supports containment, eradication, and recovery | Systems Admin 
| **DPO (Data Protection Officer)** | Assesses the implications of data protection | Legal Advisor 
| **Communications Officer** | Handles stakeholder and media communications | HR or PR 
| **Legal/Compliance Officer** | Communicates with regulators and ensures compliance | DPO 

 ---

## 📞 4. Contact Details and Escalation
This section ensures stakeholders can be contacted quickly to enable effective decision-making.

### Internal Contacts 🏢

| Role | Responsibility | Contact Details | Availability |
| --- | --- | --- | --- |
| **CISO** | Leads response; authorises decisions; updates management | 07896504521 / ciso@email.com | <br>$24/7$ 
| **IT Manager** | Oversees technical activities; ensures system stability | 07896504535 / itman@email.com | On-Call 
| **Security Analyst** | Monitors for threats; determines scope and severity | 07896504530 / secan@email.com | On-Call 
| **Systems Admin** | Contains affected systems; removes threats; restores service | 07896504503 / systemadmin@email.com | On-Call 
| **DPO** | Assesses data protection and liaises with the ICO | 07896504568 / dpo@email.com | 09:00-17:30 
| **Comms Officer** | Handles stakeholder and media communications | 07896504587 / comoffice@email.com | 09:00-17:30 
| **Legal Officer** | Communicates with regulators and ensures compliance | 07896504589 / legalofficer@email.com | On-Call 

 ### External Contacts 🌐

| Organisation | Purpose | Contact Method | Notes |
| --- | --- | --- | --- |
| **ICO** | Data compromise notification | Reporting portal online | Notify within 72 hours 
| **Police/Action Fraud** | Criminal cyber incidents | 101/Action Fraud | For fraud or extortion 
| **Cyber Insurance** | Incident notification | Policy helpline | Notify ASAP 
| **IR Supplier** | Specialised support | Contract details | For outside support 
| **Key Vendors** | Service availability | Account Manager | If vendor systems affected 

 > 
> **Contact List Maintenance:** Both digital and hard copies must be kept; hard copies in a secure but accessible location. This is reviewed **quarterly** by the Incident Response Lead.
> 
> 

---

## 🏷️ 5. Incident Categories

| Category | Description |
| --- | --- |
| **A- Critical Data Breach** | The loss or theft of PII or SPII 
| **B- Malware/Ransomware** | System infected with malicious software 
| **C- System Intrusion** | Unauthorised access to the system 
| **D- Denial of Service** | Attack affecting service availability 
| **E- Insider Threat** | Malicious or negligent staff activity 
| **F- Phishing/Social Engineering** | Attempts to deceive staff for access or data 
| **G- Physical Security Breach** | Loss or theft of physical assets 

---

## 🔄 6. Incident Response Process

### Phase 1: Prepare 🛠️

* Adopt NCSC Cyber Essentials for minimum standards.
* Include regular staff training on cyber awareness.
* Test and maintain tools like antivirus, logging, and SIEM.
* Update business continuity plans and conduct risk assessments.
* Ensure the IRT Contact List is up to date.

### Phase 2: Detect and Report 🔍

* Use monitoring tools such as SIEM and IDS/IPS.
* Staff must report unusual activity (e.g., phishing) ASAP.
* Use internal ticketing systems to log incidents.
* Record Indicators of Compromise (IoCs) and initial scope.

### Phase 3: Assess and Decide ⚖️

* Classify severity: Minor, Moderate, Major, or Critical.
* Determine data impact, including personal data.
* Notify the DPO immediately if personal data is breached.
* Ask: Contain or shut down? Notify stakeholders or wait?.

### Phase 4: Respond and Recover 🏗️

* **Containment:** Isolate affected systems, accounts, or networks.
* **Eradication:** Remove malware, backdoors, or malicious access.
* **Recovery:** Restore from secure backups; test and monitor re-entry.
* **Notification:** Notify the ICO within 72 hours for data breaches and inform data subjects as required.

---

## 📝 7. Post-Incident Review (Post-Mortem)

Conducted within **5-10 working days** post-incident to identify root causes and evaluate team effectiveness.

1. Assemble the team and stakeholders.
2. Review the incident timeline and actions taken.
3. Conduct Root Cause Analysis (what went wrong and why?).
4. Assess internal and external communication.
5. Document technical and procedural lessons learned.
6. Update the IR plan, staff training, and technical controls.
7. Share findings with leadership to raise awareness.

---

## 📢 8. Communication Plans

| Stakeholder | Notification Timeframe | Responsible Party |
| --- | --- | --- |
| **Senior Management** | Within 2 hours of a critical incident | IRT Lead 
| **ICO** | Within 72 hours of data compromise | DPO 
| **Data Subject** | Promptly if high risk to rights | DPO/Comms 
| **Press/Public** | If appropriate and approved by the board | Comms Officer 
| **Law Enforcement** | If incident involves criminal activity | Legal/DPO 

 ---

## 📂 9. Documentation Requirements

Records must be maintained for:

* Detection date/time and identification method.
* Scope of attack and affected systems.
* Containment and eradication steps.
* Communications and notifications made.
* Root cause analysis and post-incident outcomes.
* Documents must be stored securely for audit/regulatory review.

---

## 🛠️ 10. Tools, Training & Maintenance

* **Endpoint Protection:** Sophos, CrowdStrike, Microsoft Defender.
* **SIEM:** Splunk, Azure Sentinel, Elastic.
* **Backup:** Veeam, Acronis, Cloud options.
* **Intelligence:** NCSC alerts and commercial feeds.
* **Secure Comms:** ProtonMail, Office 365 ATP.
* **Training:** Biannual exercises (breaches/ransomware).
* **Simulations:** Quarterly phishing simulations.
* **Maintenance:** Annual review of DR/BCP plans and the IR plan.


