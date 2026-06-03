# Task 3 - Basic Vulnerability Scan on My PC

## Objective

The objective of this task was to perform a basic vulnerability assessment on a personal computer using a vulnerability scanning tool and identify potential security risks along with their remediation measures.

## Tools Used

* Nessus Essentials
* Windows Operating System
* GitHub

## Scan Target

* Local Machine (127.0.0.1 / Local IP Address)

## Procedure

1. Installed and configured Nessus Essentials.
2. Added the local machine as the scan target.
3. Performed a vulnerability assessment scan.
4. Waited for the scan to complete.
5. Reviewed the identified vulnerabilities.
6. Researched possible fixes and mitigation techniques.
7. Documented the findings and recommendations.
8. Captured screenshots of the scan results.

## Vulnerabilities Identified

### 1. Missing Security Updates

**Severity:** High

**Description:**
The scan detected missing operating system security updates and patches.

**Risk:**
Attackers may exploit known vulnerabilities in outdated software to gain unauthorized access or execute malicious code.

**Recommended Fix:**

* Install all pending updates.
* Enable automatic updates.
* Regularly verify patch status.

---

### 2. SSH Service Enabled

**Severity:** Medium

**Description:**
SSH service was detected running on the system.

**Risk:**
Weak authentication settings may allow brute-force attacks and unauthorized access.

**Recommended Fix:**

* Disable SSH if not required.
* Use strong passwords.
* Implement key-based authentication.
* Restrict access using firewall rules.

---

### 3. Weak SSL/TLS Configuration

**Severity:** Medium

**Description:**
The system supports outdated SSL/TLS protocols or weak encryption methods.

**Risk:**
Sensitive information may be exposed to interception or decryption attacks.

**Recommended Fix:**

* Disable SSLv2 and SSLv3.
* Use TLS 1.2 or TLS 1.3.
* Configure strong cipher suites.

## Risk Assessment

| Vulnerability              | Severity | Priority |
| -------------------------- | -------- | -------- |
| Missing Security Updates   | High     | Critical |
| SSH Service Enabled        | Medium   | High     |
| Weak SSL/TLS Configuration | Medium   | Medium   |

## Key Concepts Learned

* Vulnerability Scanning
* Risk Assessment
* CVSS Scoring
* Security Misconfigurations
* Remediation Techniques
* Nessus Essentials Usage

## Outcome

This task provided practical experience in performing vulnerability assessments and understanding common security risks present in personal computers. It also improved knowledge of vulnerability management and remediation strategies.

## Repository Contents

* README.md
* Vulnerability Scan Report
* Scan Result Screenshots
* Supporting Documentation

## Conclusion

The vulnerability scan identified several security weaknesses, with missing security updates being the most critical issue. Applying the recommended fixes will significantly improve the overall security posture of the system and reduce the risk of compromise.
