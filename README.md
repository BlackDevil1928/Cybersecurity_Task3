# Basic Vulnerability Scan on My PC

## 📝 Task Overview
This task was part of the Cyber Security Internship program, aimed at gaining hands-on experience with vulnerability scanning tools. The goal was to perform a basic vulnerability scan on a personal computer using free tools like **Nessus Essentials** or **OpenVAS**, identify common vulnerabilities, and understand how to interpret the results.

---

## 🛠 Tools Used
- **Tool:** Nessus Essentials
- **Platform:** Windows 10 (or your OS)
- **Scan Target:** Localhost (127.0.0.1)

---

## * Steps Followed

1. **Downloaded and installed Nessus Essentials** from the Tenable website.
2. **Activated** it using a free license key sent via email.
3. Set the **scan target** as `127.0.0.1` (localhost).
4. Launched a **Basic Network Scan**.
5. Waited for the scan to complete (~45 mins).
6. **Reviewed and documented** the detected vulnerabilities.
7. Captured **screenshots** of the results.
8. Exported and saved the final scan report.

## Suggested Mitigations

  Disable SMBv1: Use sudo systemctl disable smbd and uninstall legacy support.

  Renew SSL Certificates: Replace expired certificates with valid ones from a trusted CA.

  Update OpenSSH: Run sudo apt update && sudo apt upgrade openssh-server.

  Close or Restrict RDP Port: If not needed, close port 3389. If needed, use VPN and IP whitelisting.

  Strengthen Password Policies: Enforce complexity rules, lockout thresholds, and expiration via PAM or passwd configs.
