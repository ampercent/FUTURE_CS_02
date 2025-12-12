# **Future Interns – SOC Analyst Internship**

## **Task 2: Security Alert Monitoring & Incident Response**

**Tools:** Splunk Enterprise (SIEM), Kali Linux
**Domain:** Security Operations Center (SOC)

---

## 📌 **Project Description**

This project simulates real-world SOC operations by using Splunk Enterprise to ingest, analyze, and visualize security logs in order to detect potential cyber threats.
Using a Kali Linux environment, I performed log analysis, built SIEM dashboards, classified security alerts, and prepared an incident response report based on observed malicious activity.

The objective was to identify high-risk events, determine their root cause, and produce actionable remediation steps following SOC best practices.

---

## 🔍 **Key Findings**

During the analysis of the provided log dataset, two major security incidents were identified:

### **1. Critical Malware Activity**

Multiple hosts generated malware alerts including:

* **Trojan detections**
* **Rootkit signatures**
* **Worm infection attempts**
* **Ransomware-like behavior**

The spread across several IP addresses suggests coordinated malicious activity or lateral movement within the environment.

### **2. Brute Force / Credential Attack Attempts**

Several failed login attempts were observed from suspicious IPs, indicating:

* Password-guessing attempts
* Possible credential stuffing
* Attempts to compromise user accounts (e.g., alice, bob, david)

This aligns with early-stage intrusion attempts seen in enterprise environments.

---

## 📊 **Work Performed**

* Successfully uploaded and ingested SOC log data into Splunk
* Executed targeted SPL queries to identify high-risk events
* Built a **custom SOC dashboard** containing:

  * Timechart of all events
  * Malware detection count
  * Event-type breakdown (login failures, file access, connections, malware)
* Conducted full alert triage and severity classification
* Prepared a structured incident timeline and response plan

---

## 📂 **Files Included**

### **1. SOC_Incident_Report.pdf**

A detailed incident response report including:

* Executive summary
* Alert details
* Timeline of malicious events
* Impact assessment
* Recommended remediation steps
* Embedded SIEM evidence screenshots

### **2. Screenshots Folder**

Contains Splunk evidence used during the investigation:

* Malware detection search results
* Repeated connection attempts
* Login failures
* Suspicious file access events
* Custom SOC dashboard overview

### **3. Alert_Classification_Log.xlsx**

Spreadsheet listing suspicious events, severity levels, and analyst notes.

---

## 🛡️ **Outcome**

This task demonstrates core SOC analyst skills:

* Threat detection
* SPL querying
* SIEM dashboard creation
* Incident classification
* Documentation and reporting

The completed investigation provides a realistic example of how SOC teams identify, interpret, and respond to cyber threats in an enterprise environment.

