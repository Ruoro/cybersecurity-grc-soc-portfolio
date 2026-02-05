# Organization Profile

## Organization Overview

**Name (Fictional):** Aurelius Health Services Ltd.

**Industry:** Healthcare Technology & Managed Clinical Services

**Headquarters:** Nairobi, Kenya

**Operating Regions:** East Africa (Kenya, Uganda, Tanzania)

**Business Model:**
Aurelius Health Services provides a cloud-based patient management platform used by private hospitals and clinics. The company also offers managed IT and analytics services to healthcare providers.

---

## Organization Size & Structure

* **Employees:** ~320 total

  * Engineering & IT: 70
  * Operations & Support: 110
  * Clinical Services Liaison: 60
  * Sales & Marketing: 40
  * Finance, HR, Legal: 40

* **Customers:** ~85 healthcare organizations

* **Endpoints:** ~450 (laptops, desktops)

* **Servers:** ~60 (cloud-hosted)

---

## Technology Stack

### Infrastructure

* **Cloud Provider:** AWS
* **Architecture:** Hybrid (cloud-native applications with limited on-prem systems at partner hospitals)
* **Core Services:**

  * EC2, RDS (PostgreSQL), S3
  * AWS IAM
  * AWS CloudTrail & CloudWatch

### Applications

* **Primary Application:** Web-based Electronic Medical Records (EMR) system
* **APIs:** RESTful APIs for hospital system integrations
* **Authentication:**

  * SSO using Azure AD (OIDC)
  * MFA enforced for staff and administrators

### Endpoints & Productivity

* Windows 10/11 laptops
* Microsoft 365 (Exchange Online, SharePoint, OneDrive)
* Intune for endpoint management

### Security Tooling (Assumed)

* Endpoint Detection & Response (EDR)
* Centralized log collection (SIEM)
* Vulnerability scanning (monthly)
* Email security gateway

---

## Data Types Processed

### High-Sensitivity Data

* Protected Health Information (PHI)
* Patient medical records
* Diagnostic results
* Prescription data

### Medium-Sensitivity Data

* Employee personal data
* Customer contracts
* Financial records

### Low-Sensitivity Data

* Marketing website content
* Public documentation

---

## Regulatory & Compliance Context

* Local health data protection laws
* ISO/IEC 27001 alignment required for enterprise customers
* SOC 1 Type I readiness required for financial assurance to partners
* Alignment with NIST Cybersecurity Framework for internal maturity tracking

---

## Threat Landscape

* Targeted phishing and credential theft
* Ransomware affecting healthcare environments
* Insider threats (privileged IT access)
* Third-party risk from hospital integrations
* API abuse and misconfiguration

---

## Security Maturity (Baseline Assumption)

* Formal security program exists but is still maturing
* Policies documented but unevenly enforced
* Logging enabled but not fully optimized
* Incident response processes exist but are lightly tested
* Risk assessments performed annually

---

## Purpose of This Profile

This organization profile serves as the **single reference context** for all GRC and SOC artifacts in this repository. All controls, risks, incidents, detections, and reports assume this organizational environment unless explicitly stated otherwise.
