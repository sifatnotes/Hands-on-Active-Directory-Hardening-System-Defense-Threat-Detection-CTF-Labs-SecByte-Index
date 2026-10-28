# Hands-on-Active-Directory-Hardening-System-Defense-Threat-Detection-CTF-Labs-SecByte-Index
A practical collection of cybersecurity CTF labs covering Active Directory defense (BloodHound for defenders, Golden Ticket, Kerberoasting, Pass-the-Hash detection) and system hardening across Windows and Linux environments.
# Active Directory Hardening, System Defense & Threat Detection CTF Labs

Welcome to the **Active Directory Hardening, System Defense & Threat Detection CTF Lab Collection**. This repository serves as a structured, searchable catalog of practical cybersecurity labs hosted on Learn SecByte.

This collection focuses on securing identity environments and operating systems—including **Active Directory Hardening**, **Auditing Attack Paths with BloodHound**, **Identity Threat Detection (Golden Ticket, Kerberoasting, Pass-the-Hash)**, and **OS Hardening for Windows & Linux**.

---

## Lab Collection Index

### 1. Active Directory Hardening & Identity Defense
* **Active Directory Hardening Fundamentals**  
  *Lab Link:* [https://learn.secbyte.org/ctf/active-directory-hardening-fundamentals](https://learn.secbyte.org/ctf/active-directory-hardening-fundamentals)  
  *Focus:* Enforcing group policy security baselines, restricting domain admin privileges, securing Kerberos parameters, and auditing AD trust relationships.

* **Active Directory Defense: Fortified**  
  *Lab Link:* [https://learn.secbyte.org/ctf/active-directory-defense-fortified](https://learn.secbyte.org/ctf/active-directory-defense-fortified)  
  *Focus:* Implementing Tiered Administration Models, securing Protected Users group settings, restricting NTLM authentication, and hardening domain controllers.

* **BloodHound for Defenders**  
  *Lab Link:* [https://learn.secbyte.org/ctf/bloodhound-for-defenders](https://learn.secbyte.org/ctf/bloodhound-for-defenders)  
  *Focus:* Using BloodHound and SharpHound to audit domain graph relationships, identify unintended privilege escalation paths, and remediate ACL misconfigurations.

### 2. Active Directory Attack Vector & Threat Detection
* **Kerberoasting Detection & Analysis**  
  *Lab Link:* [https://learn.secbyte.org/ctf/kerberoasting-detection-analysis](https://learn.secbyte.org/ctf/kerberoasting-detection-analysis)  
  *Focus:* Monitoring Event ID 4769 (TGS requests), identifying abnormal encryption types (RC4 usage), and detecting SPN scanning/ticket harvesting.

* **Pass-the-Hash (PTH) Detection Mastery**  
  *Lab Link:* [https://learn.secbyte.org/ctf/pth-detection-mastery](https://learn.secbyte.org/ctf/pth-detection-mastery)  
  *Focus:* Detecting NTLM hash reuse across network boundaries, analyzing Event ID 4624 (Type 3 logons), and implementing LSA Protection & Credential Guard.

* **Golden Ticket Detection**  
  *Lab Link:* [https://learn.secbyte.org/ctf/golden-ticket-detection](https://learn.secbyte.org/ctf/golden-ticket-detection)  
  *Focus:* Detecting forged Kerberos Ticket Granting Tickets (TGT), analyzing lifetime anomalies,krbtgt password rotation strategies, and event log correlation.

* **Credential Theft Detection**  
  *Lab Link:* [https://learn.secbyte.org/ctf/credential-theft-detection](https://learn.secbyte.org/ctf/credential-theft-detection)  
  *Focus:* Detecting LSASS memory dumper tools (Mimikatz, ProcDump), auditing handle access events (Event ID 10), and detecting SAM database extraction.

* **Privilege Escalation Detection**  
  *Lab Link:* [https://learn.secbyte.org/ctf/privilege-escalation-detection](https://learn.secbyte.org/ctf/privilege-escalation-detection)  
  *Focus:* Tracking unauthorized privilege assignments, token manipulation, UAC bypass attempts, and abnormal process creation under SYSTEM contexts.

* **Lateral Movement Detection Lab**  
  *Lab Link:* [https://learn.secbyte.org/ctf/lateral-movement-detection-lab](https://learn.secbyte.org/ctf/lateral-movement-detection-lab)  
  *Focus:* Detecting internal propagation via PsExec, WMI, WinRM, Remote Registry, and RDP session hijacking through host and network telemetry.

### 3. Operating System Hardening & Secure Baselines
* **Windows Hardening Foundations**  
  *Lab Link:* [https://learn.secbyte.org/ctf/windows-hardening-foundations](https://learn.secbyte.org/ctf/windows-hardening-foundations)  
  *Focus:* Applying Windows CIS Security Benchmarks, hardening local security policies, disabling vulnerable legacy features (SMBv1, LLMNR/NBT-NS), and BitLocker enforcement.

* **Linux Fortress Hardening**  
  *Lab Link:* [https://learn.secbyte.org/ctf/linux-fortress-hardening](https://learn.secbyte.org/ctf/linux-fortress-hardening)  
  *Focus:* Hardening Linux kernel parameters (sysctl), configuring SSH security options, enforcing PAM password policies, mounting restrictions, and AppArmor/SELinux profiles.

* **Hardened Horizons**  
  *Lab Link:* [https://learn.secbyte.org/ctf/hardened-horizons](https://learn.secbyte.org/ctf/hardened-horizons)  
  *Focus:* Designing end-to-end enterprise baseline security standards across mixed Windows and Linux environments to minimize overall attack surface.

---

## Learning Path

### Path A: Active Directory Security & Defense Lead
1. **Hardening & Tiering:** Start with [Active Directory Hardening Fundamentals](https://learn.secbyte.org/ctf/active-directory-hardening-fundamentals) and [Active Directory Defense: Fortified](https://learn.secbyte.org/ctf/active-directory-defense-fortified).
2. **Path Audit:** Identify structural risks using [BloodHound for Defenders](https://learn.secbyte.org/ctf/bloodhound-for-defenders).
3. **Identity Threat Detection:** Author detections in [Kerberoasting Detection & Analysis](https://learn.secbyte.org/ctf/kerberoasting-detection-analysis), [Pass-the-Hash Detection Mastery](https://learn.secbyte.org/ctf/pth-detection-mastery), and [Golden Ticket Detection](https://learn.secbyte.org/ctf/golden-ticket-detection).

### Path B: Host Defense & Threat Detection Engineer
1. **OS Hardening:** Secure systems via [Windows Hardening Foundations](https://learn.secbyte.org/ctf/windows-hardening-foundations), [Linux Fortress Hardening](https://learn.secbyte.org/ctf/linux-fortress-hardening), and [Hardened Horizons](https://learn.secbyte.org/ctf/hardened-horizons).
2. **Host Attack Detection:** Catch threat techniques in [Credential Theft Detection](https://learn.secbyte.org/ctf/credential-theft-detection), [Privilege Escalation Detection](https://learn.secbyte.org/ctf/privilege-escalation-detection), and [Lateral Movement Detection Lab](https://learn.secbyte.org/ctf/lateral-movement-detection-lab).

---

## How to Use the Labs

1. Select a practice scenario from the **Lab Collection Index**.
2. Click the corresponding link to open the exercise directly on Learn SecByte.
3. Review scenario directives, instruction details, and target system topology.
4. Apply system hardening baselines, audit domain graph relationships, or build detection rules to capture flags.

---

## Target Audience

* **Active Directory Administrators & Security Engineers:** Implement domain tiering models, harden Active Directory, and audit attack paths with BloodHound.
* **SOC Analysts & Threat Hunters:** Detect identity attacks (Kerberoasting, Pass-the-Hash, Golden Tickets) and internal lateral movement.
* **Systems Administrators & Blue Teamers:** Enforce enterprise-grade security baselines on Windows and Linux hosts.
* **Cybersecurity Students:** Acquire practical, hands-on experience in enterprise identity defense and system hardening.

---

## Disclaimer

All lab links in this repository direct to official training environments hosted on Learn SecByte. All materials and exercises are provided exclusively for authorized security training, defensive skill building, and educational research purposes.
