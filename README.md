# Windows 10 STIG Remediation Scripts

This repository contains a growing collection of PowerShell scripts created to automate the implementation and remediation of **DISA STIG (Security Technical Implementation Guide)** controls for Windows 10 systems.

These scripts were developed as part of my **Cybersecurity Support Internship** with the Josh Madakor CyberRange, where I focus on hands-on security hardening, vulnerability management, and compliance automation using PowerShell and Tenable.

---

## 📌 Purpose

Each script targets a specific Windows 10 STIG ID and aims to:
- Detect system misconfigurations
- Remediate non-compliant settings
- Help ensure systems align with DISA compliance standards

---

## 🧰 Tools Used
- **PowerShell**
- **Tenable.io**
- **Azure VMs**
- **DISA STIGs v3r1 for Windows 10**

---

## 📁 STIG Remediation Scripts

| STIG ID           | Description                                                | Script Link |
|-------------------|------------------------------------------------------------|-------------|
| `WN10-AU-000500`  | Set Windows Application Event Log Size to Minimum 32MB     | [View Script](./WN10-AU-000500/WN10-AU-000500.ps1) |
| _(More coming soon)_ | | |

---

## 🔧 How to Use

Each folder contains:
- `.ps1` PowerShell script
- Inline documentation (`.SYNOPSIS`, `.NOTES`, etc.)
- Tested on Azure-hosted Windows 10 VMs
- Can be executed locally or remotely with administrative privileges

Example:
```powershell
.\WN10-AU-000500.ps1
