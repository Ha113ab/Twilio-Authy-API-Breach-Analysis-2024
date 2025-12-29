# Twilio Authy API Breach Analysis (2024)

## 📋 Overview  
This repository contains a detailed case study and analysis of the **Twilio Authy API breach** that occurred in July 2024. The breach exposed over **33 million phone numbers** and sensitive metadata due to an unsecured API endpoint. This project was developed as part of a **Cybersecurity Intrusion Detection & Analysis** capstone project.

## 🎯 Objectives  
- Analyze the technical vulnerabilities that led to the breach  
- Map attack techniques to the **MITRE ATT&CK® Framework**  
- Assess business impact and regulatory implications  
- Recommend technical and strategic mitigations  
- Create executive-level reporting for cybersecurity leadership  

## 📁 Repository Structure  
─ 📄 Report/
│ ├── Final_Project_Report.docx # Full written analysis
│ └── Final_Project_Report.pdf # PDF version
├── 🖥️ Presentation/
│ └── Final_Project_Presentation.pptx # Summary slide deck
├── 📊 Artifacts/
│ ├── affected_products.png # CPE listings
│ └── cve_details.png # CVE-2024-39891 breakdown
├── 📋 Executive_Summary/
│ └── Executive_Brief.md # C-level actionable summary
└── 📖 README.md # This file




## 🔍 Key Findings  
- **Primary Vulnerability**: Unauthenticated API endpoint enabling phone number enumeration  
- **Secondary Issues**: Lack of rate limiting & sensitive metadata exposure  
- **CVSS Score**: 5.3 (Medium) – but with severe business impact  
- **Data Exposed**: 33,420,546 records including phone numbers, account IDs, statuses, and device counts  

## 🛡️ Mitigation Strategies  
### Technical:
- Implement strict authentication (OAuth 2.0, API keys)  
- Enforce multi-factor rate limiting and bot detection  
- Apply data minimization principles to API responses  

### Strategic:
- Establish an API Security Center of Excellence  
- Adopt shift-left security practices  
- Invest in API Security Posture Management (APM) tools  

## 🧠 Tools & Frameworks Used  
- **MITRE ATT&CK®** – Attack mapping  
- **OWASP API Security Top 10** – Best practices  
- **NIST SP 800-204** – Microservices security  
- **GDPR/CCPA** – Regulatory compliance analysis  

## 👨‍💻 Author  
**Haileab Tadele Bekele**  
Cybersecurity Student | Intrusion Detection & Analysis  
[LinkedIn](#) | [GitHub](#)  

## 📚 References  
All sources and citations are included in the full report. Key references include:
- Security Boulevard (2024)  
- TechCrunch (2024)  
- MITRE ATT&CK® Framework  
- OWASP API Security Top 10  
- NIST SP 800-204  

## 📄 License  
This project is for educational purposes. All referenced materials belong to their respective owners.
