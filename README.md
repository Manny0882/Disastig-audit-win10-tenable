# DISA STIG Vulnerability and Compliance Audit - Windows 10

This project showcases an authenticated vulnerability and compliance audit on a Windows 10 system using Tenable/Nessus with the **DISA STIG** template. It covers both vulnerability findings and detailed STIG compliance checks.

---

## 🧪 Scan Setup

- **Tool Used**: Tenable (Nessus Pro)
- **Scan Template**: DISA STIG - Windows 10
- **Scan Type**: Authenticated
- **Scanner**: LOCAL-SCAN-ENGINE-01
- **Target**: `10.1.0.49`
- **Date**: April 23, 2025 – 7:02 AM

---

## 📊 Vulnerability Summary

| Severity  | Count |
|-----------|-------|
| Critical  | 2     |
| High      | 16    |
| Medium    | 31    |
| Low       | 3     |
| Info      | 128+  |
| **Total** | **180** findings |

---

## ✅ Compliance Audit Summary

| Result     | Count |
|------------|-------|
| Passed     | 98    |
| Failed     | 146   |
| Warning    | 18    |
| **Total**  | **262** checks |

---

## 🚨 Key Failed Compliance Checks

- `WN10-AU-000035`: Audit user account management must be configured.
- `WN10-SO-000010`: Guest account must be disabled.
- `WN10-CC-000005`: Camera access from lock screen must be disabled.
- `WN10-CC-000205`: Windows Telemetry must not be set to Full.
- `WN10-CC-000052`: ECC Curve prioritization must be configured.
- `WN10-CC-000326`: PowerShell script block logging must be enabled.

---

## 📁 Included Files

- 🔍 Screenshot of vulnerabilities
- 📋 Screenshot of audit findings
- ✅ Summary and key results
- (Optional) PDF or exported scan results

---

## 🎯 Objective

Demonstrate the ability to:
- Launch and complete authenticated scans
- Apply DISA STIG compliance templates
- Identify critical misconfigurations
- Interpret results and suggest hardening actions

---

## 🔐 Note

This scan was conducted in a safe lab environment for educational purposes only.
