# 🛡️ Threat Intelligence Tools Lab

This repository documents my hands-on experience with various OSINT and threat intelligence tools as part of the TryHackMe **Threat Intelligence Tools** room. These tools help analysts identify, analyze, and triage malicious emails, domains, and malware.

## 🔍 Covered Topics

- What is Threat Intelligence?
- Common Malware Families (e.g., Dridex)
- Identifying malicious attachments

## 🧰 Tools Explored

| Tool           | Purpose                                         |
|----------------|--------------------------------------------------|
| `urlscan.io`   | Visualizes website screenshots and scan results |
| `Abuse.ch`     | Tracks malware infrastructure (IP, domain, hash)|
| `PhishTool`    | Analyzes phishing emails and attachments        |
| `Cisco Talos`  | Provides domain/IP reputation                   |
| `YARA`         | Detects malware using pattern-based rules       |

## 📁 Lab Scenarios

### Scenario 1 – Email Analysis
- Extracted recipient address
- Identified malicious ZIP attachment
- Verified detection alias on VirusTotal

### Scenario 2 – Excel Malware
- Malicious `.xls` named `Sales_Receipt 5606.xls`
- Identified malware family as `Dridex`
- Discussed Excel macro-based trojans

## 🧠 Key Takeaways

- Always analyze attachments before opening.
- Use VirusTotal hashes when your machine is offline.
- Understand malware families to better predict behavior and risks.

---

## 📚 Reference Links

- [https://www.virustotal.com](https://www.virustotal.com)
- [https://www.abuse.ch](https://www.abuse.ch)
- [https://www.urlscan.io](https://www.urlscan.io)
- [https://www.talosintelligence.com](https://www.talosintelligence.com)

---

## 💡 About This Project

Built as part of the **TryHackMe - Threat Intelligence Tools** room.  
Great for beginners exploring threat hunting, SOC analysis, and malware triage.





