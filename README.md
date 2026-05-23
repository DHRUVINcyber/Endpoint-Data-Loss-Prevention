# 🔐 Endpoint Data Loss Prevention (DLP)

## 📌 Overview
A complete DLP security architecture built to prevent sensitive data 
from unauthorized access, exfiltration, or breaches using **Wazuh SIEM**.

## 🛠️ Tools & Technologies
- Wazuh (SIEM/Security Monitoring)
- Windows 10/11 Endpoints
- VirtualBox / VMware
- PowerShell
- Local Security Policy (Audit PNP Activity)

## 🎯 Key Features
- Real-time USB detection & alerting
- Custom Wazuh rules for data exfiltration
- Continuous DLP Security Controls Validation
- Compliance with GDPR & HIPAA

## 🚀 How It Works
1. Wazuh agent installed on Windows endpoint
2. Local Security Policy configured for PNP/USB logging
3. Custom rules added in `/var/ossec/etc/rules/local_rules.xml`
4. Alerts triggered on Wazuh dashboard upon USB connection

## 📄 Project Report
See the full report: [DATA_LOSS_PREVENTION.docx]

## 📚 References
IEEE, GDPR, CoBAn model, Wazuh documentation
