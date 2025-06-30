# 🛡️ Botium-Toys-Security-Audit
## 📑 Table of Contents

- [Introduction](#introduction)
- [Backdrop](#backdrop)
- [Internal Security Audit Flow](#internal-security-audit-flow)
- [Controls Assessment](#controls-assessment)
- [Compliance Checklist](#compliance-checklist)
- [Stakeholder Memorandum](#stakeholder-memorandum)
- [Conclusion](#conclusion)
- [Lessons Learned](#lessons-learned)

- --
 ## Introduction
- An internal security audit was conducted on a fictional toy company called Botium Toys as part of the [Google Cybersecurity Professional Certificate](#https://www.coursera.org/google-certificates/cybersecurity-certificate).
This project aimed to assess the organization’s existing security controls, identify critical vulnerabilities, and determine whether its security framework aligns with the NIST Cybersecurity Framework (CSF). The audit process included using risk matrix tools and adhering to OWASP security principles to evaluate and prioritize risks effectively. The audit concludes with a set of actionable recommendations and a formal report intended for organizational stakeholders, aimed at improving the company’s overall security posture.
----
 ## Backdrop
 
Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and a warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She's worried about maintaining compliance and business operations as the company grows without a clear plan. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing, accepting online payments, and conducting business in the European Union (EU).   
The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of its security posture.

----

Scope of this Project: 
1. To define the Entire Security Program.
2. Their Entire assets, like employee equipment and devices, their internal network, and their systems need to be assessed.
3. Review their internal process and procedure related to compliance and controls.
   
Goals are as follows:
1. Identify and asses existing assets.
2. Complete a comprehensive control and compliance checklist.
3. Establish Systems aligned with the company's best practices.
4. Ensure the established systems help build a strong security posture.
  ----

## Internal Security Audit Flow
1. Analyze scope, goal, and risk assessment.
2. Complete control Assessment Checklist
3. Compliance Checklist
4. Recommendation
5. Communicate with stakeholders
----

 # Controls Assessment
 ## Current Assets
  Assets managed by the IT Department include: 
  
●	On-premises equipment for in-office business needs  
●	Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
●	Storefront products available for retail sale on site and online; stored in the company’s adjoining warehouse
●	Management of systems, software, and services: accounting, telecommunication, database, security, e-commerce, and inventory management
●	Internet access
●	Internal network
●	Data retention and storage
●	Legacy system maintenance: end-of-life systems that require human monitoring 

## Controls Categories
Control assessments were conducted under three main categories.


### 🧑‍💼 Administrative Controls

Administrative controls involve the **human component** of cybersecurity, including **policies, procedures, and practices**. These controls help determine whether employees are aligned with security regulations and fulfilling their responsibilities to keep the organization safe and secure.

📝 The table below presents the **Administrative Control Assessment Report** for Botium Toys.
| Control Name | Type | Status | Priority |
|--------------|------|--------|----------|
| Least Privilege | Preventative | ✅ | High |
| Disaster Recovery Plans | Corrective | ✅ | High |
| Password Policies | Preventative | ✅ | High |
| Access Control Policies | Preventative | ✅ | High |
| Account Management Policies | Preventative | ✅ | High |
| Separation of Duties | Preventative | ✅ | High |

### ⚙️ Technical Controls
Technical controls consist of solutions such as firewalls, intrusion detection systems (IDS), intrusion prevention systems (IPS), antivirus (AV) products, encryption, etc. Technical controls can be used in a number of ways to meet organizational goals and objectives.

| Control Name | Type | Status | Priority |
|--------------|------|--------|----------|
| Firewall | Preventative | Already in place | - |
| Intrusion Detection System | Detective | ✅ | High |
| Encryption | Deterrent | ✅ | High |
| Backups | Corrective | ✅ | High |
| Password Management System | Corrective | ✅ | High |
| Antivirus Software | Corrective | ✅ | High |
| Legacy System Monitoring | Preventative/Corrective | ✅ | High |

### 🛡️ Physical Controls

Physical/Operational controls include door locks, cabinet locks, surveillance cameras, badge readers, etc. They are used to limit physical access to physical assets by unauthorized personnel. 

| Control Name | Type | Status | Priority |
|--------------|------|--------|----------|
| Time-Controlled Safe | Deterrent | ✅ | Low |
| Adequate Lighting | Deterrent | ✅ | Low |
| CCTV Surveillance | Preventative/Detective | ✅ | Medium–High |
| Locking Cabinets | Preventative | ✅ | Medium–High |
| Alarm Signage | Deterrent | ✅ | Low |
| Locks | Preventative | ✅ | High |
| Fire Detection | Preventative/Detective | ✅ | Medium |

---

## 📝 Compliance Checklist

### 📌 GDPR (General Data Protection Regulation)
- Applies due to EU customer data handling  
- 72-hour breach notification requirement  
- Data privacy by design

### 💳 PCI DSS (Payment Card Industry Data Security Standard)
- Required for online & in-store payment processing  
- Risks: fines, audits, legal consequences  
- Mandatory for customer credit card data handling

### 📋 SOC 1 & SOC 2
- User access, data confidentiality, and audit compliance  
- SOC 1 → Financial reporting controls  
- SOC 2 → Security, availability, integrity, privacy

---

## 🧾 Stakeholder Memorandum

**TO:** IT Manager, Stakeholders  
**FROM:** [Shaiqua Tashbih]  
**DATE:** [30/06/2025]  
**SUBJECT:** Internal IT Audit – Key Findings & Recommendations

### 🚨 Critical Findings:
- No formal password/account/access policies  
- Lack of IDS, encryption, AV software  
- No backup or disaster recovery plans  
- Missing physical protections (locks, CCTV)  
- GDPR & PCI compliance not fully addressed

### ✅ Recommendations:
- Prioritize policy creation & least privilege model  
- Set up IDS, AV, encryption, backup strategy  
- Document playbooks and recovery plans  
- Install physical controls like CCTV & locks  
- Ensure GDPR/PCI compliance ASAP

---

## 🔚 Conclusion

This mock security audit was an excellent exercise in applying risk analysis, control assessment, and compliance alignment. I developed stronger skills in threat modeling and stakeholder communication.

---

## 🧠 Lessons Learned

- Improved clarity and brevity in stakeholder reports  
- Better understanding of SOC1/SOC2’s relevance  
- Practice balancing technical detail with executive summary




