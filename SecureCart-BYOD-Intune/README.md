# SecureCart — BYOD & Intune Compliance Project  
**By Giannina Bariani**

This project simulates a real Bring Your Own Device (BYOD) scenario for a fictional company (SecureCart), showcasing how Intune and Entra ID can secure personal devices used for work by enforcing compliance requirements, Conditional Access, and endpoint protection.

---

## 🔹 Overview
SecureCart allows employees to use their personal Windows devices for work.  
To protect corporate data and enforce a zero-trust model, Microsoft Intune and Entra ID were used to deploy:

- BitLocker encryption policies  
- Password and security baseline configurations  
- Firewall & antivirus enforcement  
- Device health and compliance checks  
- Conditional Access requiring MFA + Compliant Device  
- Access blocking on non-compliant devices  

This project fully demonstrates a **real BYOD implementation from start to finish**.

---

## 🔹 Tasks Performed

### **1. Device Enrollment**
- Added a personal Windows device to Intune  
- Verified management status (MDM = Intune)  
- Synced device to apply baseline and compliance rules  

### **2. Compliance Policies**
Enforced critical security requirements:

- BitLocker encryption required  
- Firewall must be ON  
- Antivirus (Windows Defender) enabled  
- Secure password rules (12+ characters)  
- Screen lock after inactivity  
- Device must not be jailbroken or tampered  
- Immediate noncompliance actions  

### **3. Configuration Profiles**
Pushed security settings including:

- Password complexity  
- Idle lock-screen timeout  
- Defender antivirus configuration  
- Firewall state  
- Device restriction policies  

### **4. Conditional Access (Entra ID)**
Created a policy requiring:

- **MFA authentication**  
- **Compliant device**  
- Access only from approved apps  
- Risk-based restrictions  
- Blocking access from unmanaged or non-compliant devices  

### **5. Testing & Validation**
Validated the full BYOD workflow:

- ✔ Access allowed → compliant device  
- ❌ Access blocked → non-compliant device  
- ✔ Authentication flow with MFA  
- ❌ OneDrive/Outlook/Teams denied when device fails requirements  

Included screenshot evidence of every test.

---

## 🔹 Tools Used
- Microsoft Intune  
- Microsoft Entra ID (Azure AD)  
- Compliance Policies  
- Configuration Profiles  
- Conditional Access  
- Windows Security Center  

---

## 🔹 Deliverables Included
- BYOD project PDF  
- Screenshot evidence:  
  - Compliance policies  
  - Conditional Access  
  - BitLocker  
  - Firewall  
  - Device status  
  - MFA workflow  
- BYOD validation video  
- Enrollment & sync steps  

---

## 🎥 BYOD Validation Video (Compliant vs Non-Compliant)

This video demonstrates:

- Device enrollment  
- Compliance evaluation  
- BitLocker & firewall validation  
- MFA login  
- Access allowed vs blocked  

▶ **Watch the full video:**  
https://drive.google.com/file/d/1XN3vAAlTse8QuDdt7nIGr8lnoCurAZ2P/view?usp=drive_link

---

## 📄 Full Report
Upload here:  
**BYOD-Intune-ConditionalAccess-GianninaBariani.pdf**

---

## ✅ Summary
This project demonstrates end-to-end skills in **endpoint security**, **Intune administration**, **Conditional Access**, and **Zero Trust enforcement**.  
It reflects real industry practices for protecting company data in BYOD environments and is directly applicable to roles in:

- SOC Analyst  
- Endpoint Security  
- IAM / Entra ID  
- IT Support / MDM Administrator  
