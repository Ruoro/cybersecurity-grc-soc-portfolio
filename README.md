# Cybersecurity GRC & SOC Portfolio
### Overview
This repository contains practical demonstrations of Governance, Risk, and Compliance (GRC) frameworks and Security Operations Center (SOC) analysis techniques. The projects are based on controlled lab environments and simulated scenarios designed to reflect real-world cybersecurity tasks without actual organizational data or systems.

### Scope
**GRC Focus**: Implementation and documentation aligned with ISO 27001, NIST CSF/SP 800-53, and SOC 1 trust principles.

**SOC Focus**: Intermediate-level analysis including alert triage, log investigation, and incident response procedures.

**Environment**: All work conducted in isolated lab setups using deliberately created sample data, open-source tools, and simulated scenarios.


### What This Portfolio Demonstrates

#### GRC Competencies
**Risk Assessment**: Systematic identification, analysis, and evaluation of information security risks.

**Control Design & Mapping**: Selection and documentation of controls mapped to ISO 27001 Annex A and NIST 800-53.

**Policy Development**: Creation of foundational security policies and procedures.

**Compliance Artifacts**: Evidence preparation for control objectives relevant to SOC 1 reporting.

**Gap Analysis**: Comparative assessments between framework requirements and simulated environments.

#### SOC Analyst Competencies
**Alert Triage**: Methodical investigation of security alerts from simulated SIEM and EDR platforms.

**Log Analysis**: Examination of network, endpoint, and application logs to identify malicious activity.

**Incident Documentation**: Creation of clear, actionable incident reports and escalation summaries.

**Indicator of Compromise (IoC) Handling**: Process for identifying, documenting, and operationalizing IoCs.

**Basic Threat Hunting**: Hypothesis-driven searches across log data to uncover stealthy activity.

### Repository Artifacts

#### GRC Artifacts
`/grc/risk_register.xlsx` – Sample risk register with calculations and treatment plans.

`/grc/iso27001_gap_analysis.md` – Comparative analysis of lab environment against ISO 27001 controls.

`/grc/nist_control_mapping.md` – Mapping of implemented security measures to NIST 800-53 controls.

`/grc/soc1_control_matrix.xlsx` – Matrix documenting controls relevant to financial reporting objectives.

`/grc/policies/` – Directory containing sample policies (Acceptable Use, Incident Response, etc.).

#### SOC Artifacts
`/soc/incident_reports/` – Anonymized incident reports following a structured format.

`/soc/analysis_notes/` – Triage notes and investigation timelines from simulated alerts.

`/soc/playbooks/` – Basic procedural playbooks for common alert types.

`/soc/ioc_analysis.md` – Example analysis of a malware sample's network and host indicators.

`/soc/hunting_queries/` – KQL/SQL queries used for proactive threat hunting in log data.

### How Artifacts Were Created
**Lab Environment**: Utilized virtual machines, deliberately vulnerable applications, and open-source security tools (Wazuh, Security Onion, etc.).

**Data Generation**: Used simulated log generators (like LogGen) and scripted scenarios to create realistic but artificial security events.

**Framework Application**: Controls and procedures were designed for the lab environment, not taken from production systems.

**Analysis Work**: All investigations are based on deliberately planted security events within the lab. No real breaches or incidents are documented.

### Tools & Technologies

GRC: LibreOffice/Excel, draw.io for diagrams, VS Code for documentation.

SOC Analysis: Wazuh SIEM, Elastic Stack, Security Onion, REMnux for malware analysis.

Infrastructure: VirtualBox/VMware, isolated network segments.


> **Important Disclaimer**
> This portfolio represents work performed in a personal, controlled lab environment. All data, systems, and scenarios are simulated. No real organizational data, proprietary information, or actual security incidents are contained within this repository.
