# IT-Cloud-Portfolio

Welcome to my primary technology portfolio. This repository acts as a centralized index mapping my chronological journey from core networking up to fully-orchestrated hybrid cloud environment management. 

Each project listed below represents standalone repositories documenting live architecture, configuration parameters, validation evidence, and explicit engineering challenges encountered during execution.

## 🗺 Chronological Project & Lab Portfolio

### 🌐 Phase 1: Core Networking & Server Infrastructures
*Foundational systems layout focusing on fundamental protocol structures, addressing schemas, and local enterprise core roles.*

* **[🌐 networking-lab-packet-tracer](https://github.com/mflint-cloud/networking-lab-packet-tracer)**
  * **Description:** A 3-subnet routed enterprise topology implementing inter-VLAN routing, dynamic DHCP configurations, and local DNS mapping.
  * **Signals:** Cisco IOS, LAN Routing, Protocol Design.
* **[📐 subnetting-vlsm-design](https://github.com/mflint-cloud/subnetting-vlsm-design)**
  * **Description:** Mathematical structuring and realization of a 5-department Variable Length Subnet Mask (VLSM) topology mapping explicit IP block requirements.
  * **Signals:** IP Addressing, Network Optimization, VLSM.
* **[🖥️ windows-server-dns-dhcp](https://github.com/mflint-cloud/windows-server-dns-dhcp)**
  * **Description:** Implementation of Windows Server 2022 DNS and DHCP administrative server roles, defining robust scopes, active exclusions, and client validations.
  * **Signals:** Windows Server Administration, Infrastructure Roles.

### 🏢 Phase 2: Hybrid Directory Infrastructures & Core SIEM Monitoring
*Establishing centralized account identity, scripting structural administration, and implementing live pipeline monitoring.*

* **[🏢 active-directory-lab](https://github.com/mflint-cloud/active-directory-lab)** **[PINNED]**
  * **Description:** Creation of a full on-premise `corp.lab` environment containing domain controllers, Group Policy Objects (GPOs), drive mapping schemes, and rigid password criteria.
  * **Signals:** Windows Server Active Directory, GPO Administration.
* **[⚙️ powershell-ad-automation](https://github.com/mflint-cloud/powershell-ad-automation)**
  * **Description:** Standalone script library automating bulk user provisioning via CSV inputs, custom OU organizational builders, and active security grouping report exports.
  * **Signals:** PowerShell Automation, DevOps, System Operations.
* **[🟡 splunk-ad-monitoring](https://github.com/mflint-cloud/splunk-ad-monitoring)** **[PINNED]**
  * **Description:** Deployment of a Splunk Universal Forwarder onto an Active Directory Domain Controller to ingest Windows Event log structures into a custom 4-panel dashboard.
  * **Signals:** Splunk (SPL), Log Forwarding, Operational Monitoring.
* **[🔵 hybrid-ad-azure-lab](https://github.com/mflint-cloud/hybrid-ad-azure-lab)** **[PINNED]**
  * **Description:** Flagstone enterprise hybrid integration configuration, executing continuous secure directory sync from local Active Directory into Azure Entra ID via AD Connect.
  * **Signals:** Hybrid Identity, Azure Entra ID, Microsoft 365 Architecture.

### 🔍 Phase 3: Vulnerability Defenses & Threat Analytics (SIEM Engineering)
*Proactive evaluation of assets, vulnerability remediation workflows, and advanced correlation search engineering.*

* **[🔍 vulnerability-scanning-lab](https://github.com/mflint-cloud/vulnerability-scanning-lab)**
  * **Description:** Executing thorough Nessus Essentials credentialed asset scans, generating technical mitigation plans backed by CVE IDs, CVSS weightings, and re-scan delta proofing.
  * **Signals:** Vulnerability Management, CVSS, Defensive Infrastructure.
* **[🟢 secure-smb-infrastructure](https://github.com/mflint-cloud/secure-smb-infrastructure)**
  * **Description:** Multi-tier architectural design integrating a pfSense edge routing firewall with co-existing Splunk and ELK SIEM analytical stacks mapping SMB operations.
  * **Signals:** Firewalls, Network Isolation, Elastic Stack.
* **[⚙️ elk-siem-lab](https://github.com/mflint-cloud/elk-siem-lab)**
  * **Description:** Ingesting event pipelines into Elasticsearch, organizing visualization interfaces inside Kibana, and drafting automated log-checking alert definitions.
  * **Signals:** ELK Stack, Pipeline Configuration, Alerts.
* **[🟡 splunk-threat-detection](https://github.com/mflint-cloud/splunk-threat-detection)** **[PINNED]**
  * **Description:** 4 core correlation searches mapping Active Directory attack signatures (brute-force, account enumeration, privilege hikes, and lateral migration) translated side-by-side between SPL and KQL.
  * **Signals:** SIEM Engineering, SPL, KQL, Threat Detection.
* **[📋 incident-response-playbooks](https://github.com/mflint-cloud/incident-response-playbooks)**
  * **Description:** Detailed incident remediation maps formatted against the NIST SP 800-61 6-phase framework, defining mitigation workflows for active SIEM triggers.
  * **Signals:** Incident Response, Technical Writing, Policy Compliance.

### ☁️ Phase 4: Public Cloud Architecture & Governance (Azure Admin)
*Transitioning operations into software-defined environments, adopting infrastructure-as-code paradigms, and enterprise auditing.*

* **[☁️ azure-foundations-az900](https://github.com/mflint-cloud/azure-foundations-az900)**
  * **Description:** Structured platform management containing cost containment analyses, active budget notifications, and automated structural resource group tags.
  * **Signals:** Cloud Cost Optimization, Azure Basics.
* **[🌐 azure-vnet-peering-lab](https://github.com/mflint-cloud/azure-vnet-peering-lab)**
  * **Description:** Setup and validation of explicit hub-and-spoke VNet models leveraging Network Security Groups (NSGs) to control communication matrices between isolated segments.
  * **Signals:** Cloud Networking, Tenant Security.
* **[🔒 azure-rbac-policy-lab](https://github.com/mflint-cloud/azure-rbac-policy-lab)**
  * **Description:** Building granular Custom Azure RBAC roles via explicit JSON syntax, assigning resource locks, and defining geography-specific Azure Policies.
  * **Signals:** Cloud Governance, Security Principles, Identity Management.
* **[💾 azure-backup-recovery-lab](https://github.com/mflint-cloud/azure-backup-recovery-lab)**
  * **Description:** Configuration of Recovery Services Vault policies to ensure business continuity targets (RPO/RTO) are met through validated file-level restoration checks.
  * **Signals:** Business Continuity, Backup Systems.
* **[📊 azure-monitor-kql-lab](https://github.com/mflint-cloud/azure-monitor-kql-lab)**
  * **Description:** Logging configuration using Log Analytics Workspaces, tracking virtual infrastructure performance counters, and organizing alerting frameworks via KQL syntax.
  * **Signals:** Cloud Monitoring, KQL Analytic Queries.
* **[🔴 azure-admin-environment](https://github.com/mflint-cloud/azure-admin-environment)** **[PINNED]**
  * **Description:** Production-grade Azure framework featuring multi-tier spokes, centralized hub routing, monitoring rulesets, and RBAC schemes deployed completely through reusable Azure Bicep IaC files.
  * **Signals:** Infrastructure as Code (IaC), Azure Bicep, Enterprise Cloud Administration.
* **[🟣 soc-sentinel-lab](https://github.com/mflint-cloud/soc-sentinel-lab)**
  * **Description:** Cloud SOC SIEM blueprint compiling Microsoft Sentinel log collectors, active cloud cyberattack runbooks, and 5 distinct custom analytical alert models.
  * **Signals:** Cloud Security SIEM, Microsoft Sentinel, Advanced Threat Hunting.

### 📞 Phase 5: Ongoing Operational Communications
*Continuous validation repository modeling everyday multi-disciplinary systems tasks.*

* **[🟠 helpdesk-ticket-simulation](https://github.com/mflint-cloud/helpdesk-ticket-simulation)**
  * **Description:** Real-world troubleshooting index logging 20 realistic scenarios (10 Active Directory, 5 Azure Cloud, 5 Network Topology). Structured strictly as professional tickets: Symptoms → Root Cause Analysis → Resolution Steps.
  * **Signals:** Technical Communications, Diagnostic Reasoning, Customer Support Operations.

---
