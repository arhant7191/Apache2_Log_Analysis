# 🧠 Apache2 Log Analysis

This project demonstrates how to detect and analyze malicious activities using Apache2 server logs in a simulated environment with **DVWA (Damn Vulnerable Web Application)**.  
It focuses on understanding Blue Team defensive techniques such as **log analysis, IP tracking, and error code monitoring** to identify intrusion attempts.

---

## 📂 Repository Structure

| Folder | Description |
|--------|-------------|
| **/practical-work** | Contains Apache log analysis commands and optional screenshots. |
| **/Apache2_Log_Analysis.pdf** | Contains the complete project report (PDF). |

---

## ⚙️ Tools & Environment
- **OS:** Kali Linux  
- **Web Server:** Apache2  
- **Testing Platform:** Damn Vulnerable Web Application (DVWA)  
- **Commands Used:** `tail`, `awk`, `grep`, `sort`, `uniq`

---

## 🔍 Key Objectives
1. Analyze access and error logs for suspicious activity.  
2. Detect attacks like SQL Injection and brute-force attempts.  
3. Identify malicious IPs and repetitive request patterns.  
4. Recommend security mitigations like Fail2Ban and ModSecurity.

---

## 💻 Practical Work
You can view all the log analysis commands here:  
👉 [Practical Work](practical_work)

---

## 📄 Full Report
👉 [Download Complete Report (PDF)](Apache2_Log_Analysis/Apache2 Log Analysis.pdf)

---

## 🔒 Mitigation Techniques
- Block malicious IPs using UFW or iptables  
- Install **Fail2Ban** to prevent brute force  
- Enable **ModSecurity (WAF)** for Apache  

---

## 👨‍💻 Author
**Arhant Suhas Gaikwad**  
BCA Student | Cybersecurity & Digital Forensics Enthusiast  
Tilak Maharashtra Vidyapeeth, Pune  
Guided by: **Dr. Anup Girdhar**  
September 2025
