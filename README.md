# 🚨 Incident Response: RDP Brute-Force Attack Simulation

## 🎯 Objective
To simulate and investigate a brute-force attack on a Windows system using Event Viewer logs, and demonstrate basic incident response procedures.

---

## 🧪 Detection

Multiple failed login attempts were detected in Windows Event Logs under Event ID **4625**.

These events indicate unsuccessful login attempts to the system, which may suggest unauthorized access attempts.

---

## 🔍 Investigation

- Event ID: 4625 (Failed Login)
- Target Account: bourne
- Number of Attempts: 5
- Time Frame: within 2 minutes

### Observations:
- Repeated failed login attempts were recorded in a short period
- The activity followed a consistent pattern
- Indicates possible automated login attempts

## 🚨 Conclusion

The observed activity is consistent with a **brute-force attack**, where repeated login attempts are made to gain unauthorized access to the system.

---

## 🛡️ Response Actions

- Monitored login activity using Event Viewer
- Identified repeated failed login attempts
- Recommended restricting Remote Desktop (RDP) access
- Suggested blocking suspicious IP addresses via firewall

---

## 🔧 Prevention & Mitigation

- Enable account lockout policies after multiple failed attempts
- Use strong passwords
- Enable Multi-Factor Authentication (MFA)
- Restrict or disable Remote Desktop (RDP) if not required
- Configure firewall rules to limit access

---

## ✅ Outcome

The simulated attack was successfully identified and analyzed.  
Appropriate mitigation strategies were recommended to prevent future occurrences.

---

## 🧠 Key Skills Demonstrated

- Log Analysis  
- Threat Detection  
- Incident Investigation  
- Basic Incident Response  
- Windows Security Monitoring  
