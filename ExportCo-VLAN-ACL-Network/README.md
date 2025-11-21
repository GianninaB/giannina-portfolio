# ExportCo — VLAN & ACL Network Security Project  
**By Giannina Bariani**  

This Capstone Project demonstrates the practical application of secure network design using VLAN segmentation, ACL-based access control, SSH hardening, and risk assessment for a small export company. The environment was built and tested in Cisco Packet Tracer with full documentation and validation.

---

## 🔹 Executive Summary
ExportCo is a 50-employee logistics company handling sensitive data such as client information, invoices, and financial records.  
The original network was **flat, unsegmented, and lacked access controls**, exposing internal data to unauthorized users.

This project redesigned the infrastructure using:
- VLAN segmentation (HR, Marketing, Finance)  
- Router-on-a-stick inter-VLAN routing  
- ACLs enforcing least privilege  
- Secure administrative access (SSH v2)  
- Validation through ping, traceroute, and Wireshark simulation  
- Risk assessment matrix and Incident Response Playbook  

The final design aligns with **NIST CSF**, **CIS Controls**, and secure networking best practices.

---

## 🔹 Objectives
1. Create VLANs for HR, Marketing, and Finance  
2. Implement inter-VLAN routing using sub-interfaces  
3. Apply ACLs to restrict inter-department access  
4. Replace Telnet with SSH for secure administration  
5. Validate segmentation and security controls  
6. Perform a pre- and post-segmentation risk assessment  
7. Document all configurations and results professionally  

---

## 🔹 Network Design
**Department VLANs:**
- VLAN 10 — HR (192.168.10.0/24)  
- VLAN 20 — Marketing (192.168.20.0/24)  
- VLAN 30 — Finance (192.168.30.0/24)  

**Key features:**
- Router-on-a-stick configuration  
- Switch trunking  
- Firewall at perimeter  
- Segregated Guest VLAN for unmanaged devices  

(See full PDF report for diagrams and configurations.)

---

## 🔹 Implementation

### **VLAN Configuration (Switch)**

### **Router Sub-Interfaces (Router-on-a-stick)**

### **ACL Example — Blocking Marketing → Finance**

### **SSH Configuration**

---

## 🔹 Validation & Testing
Testing was performed using:
- **Ping** (same-VLAN communication)  
- **Traceroute**  
- **ACL enforcement**  
- **SSH login verification**  
- **Wireshark Simulation Mode** (Packet Tracer)  

**Results:**
- Segmentation successful  
- ACL blocked unauthorized cross-VLAN traffic  
- SSH remote administration encrypted and functional  

---

## 🔹 Risk Assessment (Pre vs Post Segmentation)
| Threat | Likelihood | Impact | Status | Mitigation |
|-------|------------|--------|--------|------------|
| Flat network allows unauthorized access | High | Critical | Mitigated | VLANs + ACLs |
| Telnet remote access | High | High | Mitigated | SSH v2 |
| No segmentation | High | High | Mitigated | VLANs |
| Guest devices accessing LAN | Medium | High | Partially mitigated | Guest VLAN |

Full matrix available in the PDF report.

---

## 🔹 Incident Response Playbook
Built using NIST 800-61 lifecycle:

1. **Identification**  
2. **Containment**  
3. **Eradication**  
4. **Recovery**  
5. **Lessons Learned**  

Includes isolation steps, MFA recommendation, and account lockdown procedures.

---

## 🔹 Deliverables
- ✔️ Full PDF report  
- ✔️ Cisco Packet Tracer `.pkt` file  
- ✔️ VLAN + ACL configurations  
- ✔️ Wireshark simulation screenshots  
- ✔️ Network diagram  
- ✔️ Risk Matrix  
- ✔️ IR Playbook  

---

## 📄 Full Report
**ExportCo Network Security Project — PDF**  
(Upload your renamed PDF here)

---

## ✅ Summary
The ExportCo project transformed a vulnerable flat network into a segmented, controlled, and secure environment using VLANs, ACLs, SSH, and risk-based decision making.  
It demonstrates hands-on skills in **network security**, **architecture**, **risk management**, and **incident response**.

