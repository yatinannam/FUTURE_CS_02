# 🛡️ Security Alert Monitoring & Incident Response

This project was developed as **Task 2** of the **Future Interns Cybersecurity Internship Program**.  
It involved using **Splunk SIEM** to monitor simulated web access logs, identify suspicious activity, classify potential incidents, and document a complete **incident response report**.

---

## 🚀 Features

- Monitored simulated security events using Splunk Free Trial  
- Identified suspicious patterns from sample logs  
- Simulated:
  - Reconnaissance attempts (identical timestamps)  
  - Suspicious URL access  
- Classified each incident with severity and attack type  
- Provided recommendations for SOC remediation  
- Documented analysis with **screenshots and full report**

---

## 🛠️ Tools & Setup

- **OS**: Windows 10  
- **SIEM Tool**: Splunk Enterprise (Free Trial)  
- **Log Data**: Buttercup Games sample log file  
- **Search Queries**: `index=*`, `table _time, clientip, uri_path, status`

---

## 🧪 How It Works

1. Installed Splunk locally and launched via `127.0.0.1:8000`  
2. Uploaded sample `.log` file using “Add Data” feature  
3. Ran basic search and filtered for key fields  
4. Identified patterns like:
   - Multiple identical timestamps (possible automation)  
   - Suspicious URIs and HTTP status codes  
5. Documented findings in a structured report with screenshots  
6. Provided classification and remediation recommendations

---

## 📄 Report Included

> The project includes a **PDF incident response report** detailing both incidents, screenshots, classifications, and suggestions for mitigation.

📄 **File:** [`Incident_Response_Report_Splunk.pdf`](./Incident_Response_Report_Splunk.pdf)

---

## 📁 Folders

- `screenshots/` – Visuals from Splunk dashboard  
- `Incident_Response_Report_Splunk.pdf` – Final incident response report   
- `sample_log_file.log` – Sample data used for monitoring

---

## 🔐 Incidents Documented

- **Incident 1:** Reconnaissance Activity  
  - Identical timestamps across multiple logs  
  - Indicates possible automation or scanning
    
- **Incident 2:** Suspicious URL Access  
  - Malformed/unauthorized endpoints  
  - Potential brute force or access control test

---

## 📋 Skills Demonstrated

- SIEM Setup & Log Ingestion  
- Basic Splunk Query Language (SPL)  
- Incident Classification & Triage  
- Report Writing & Recommendations

---

## 📎 Summary

This task simulated a Security Operations Center (SOC) experience and helped in understanding the basics of SIEM monitoring, threat detection, and documentation.

---

