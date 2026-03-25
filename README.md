<h1 align="center">Hi, I'm Baljindra Singh 👋</h1>

<p align="center">
  <b>IT System Administrator · Zero Trust · Identity & Security Observability</b><br/>
  Gurugram, India · <a href="https://linkedin.com/in/baljindrasingh">LinkedIn</a>
</p>

---

## 🔐 About Me

IT System Administrator with **7+ years** of experience designing, securing, and operating hybrid IT infrastructure for organisations of up to **250 users across 3 sites**.

I specialise in **zero-trust networking**, **identity-first access**, **endpoint security**, and **security observability** — building infrastructure that is secure by design, observable by default, and scalable without complexity.

> 🏆 Secured and managed hybrid infrastructure for 250+ users across 3 sites — implementing zero-trust architecture, centralised security observability, and automated endpoint management that reduced manual effort and eliminated standing access privileges.

---

## 🛠️ Tech Stack

| Area | Tools |
|------|-------|
| **Zero Trust / VPN** | NetBird, WireGuard, IPsec, SSL VPN, OpenVPN |
| **Identity & Access** | Microsoft Entra ID, Hybrid AD, FreeRADIUS + OAuth2, SAML SSO, MFA, Conditional Access |
| **Endpoint Security** | CrowdStrike Falcon, Microsoft Intune (Windows, macOS, RHEL), Code42 DLP, SOAR |
| **Cloud & Infra** | AWS EC2, AWS Lambda, Azure AD, M365, Proxmox, VMware ESXi, Docker, Traefik |
| **Automation** | Ansible, Python, PowerShell, Bash, WinRM, AWS Lambda, Jira API |
| **Monitoring & SIEM** | Prometheus, Grafana, Alertmanager, CrowdStrike Falcon LogScale, rsyslog |
| **Networking** | FortiGate 101F/81F/40F, Aruba AP505/515, Unifi UAP, DHCP, DNS |
| **Compliance** | SOC 2, ISO 27001 / ISMS, TLS Hardening, HTTP Security Headers, CAA DNS |

---

## 🚀 Projects

### 🔐 Zero Trust & NetBird

| # | Repository | Description |
|---|-----------|-------------|
| 1 | [netbird-enterprise-deployment](https://github.com/baljindrasingh/netbird-enterprise-deployment) | Self-hosted NetBird on AWS EC2 — Docker Compose, Traefik, TLS hardening (SSL Labs A+), HTTP security headers (F→A), CAA DNS, Intune deployment scripts (Windows + macOS) |
| 2 | [netbird-crowdstrike-logscale-pipeline](https://github.com/baljindrasingh/netbird-crowdstrike-logscale-pipeline) | rsyslog → CrowdStrike Falcon LogScale pipeline for Docker container + host OS log visibility — custom parser templates and alert rules |
| 3 | [jit-access-jira-netbird-lambda](https://github.com/baljindrasingh/jit-access-jira-netbird-lambda) | Just-In-Time VPN access — Jira webhook → AWS Lambda (Python) → NetBird API peer lifecycle (create, assign, revoke) + Jira notifications + compliance access reports |

### ⚙️ Automation & Infrastructure

| # | Repository | Description |
|---|-----------|-------------|
| 4 | [ansible-rhel-enterprise-automation](https://github.com/baljindrasingh/ansible-rhel-enterprise-automation) | End-to-end RHEL 9 provisioning — AD join, Intune enrolment, patching, developer tooling, Flatpak/Snap, DNF auto-updates. Windows + Linux hybrid inventory |
| 5 | [ansible-windows-linux-netbird](https://github.com/baljindrasingh/ansible-windows-linux-netbird) | Unified Windows + Linux automation — WinRM-based Ansible with dynamic inventory and NetBird P2P connectivity for secure remote execution across 3 sites |
| 6 | [rhel-intune-integration](https://github.com/baljindrasingh/rhel-intune-integration) | RHEL 9 + Microsoft Intune enrolment — centralised Linux device management, compliance enforcement, and security policy application |

### 🛡️ Identity & Access

| # | Repository | Description |
|---|-----------|-------------|
| 7 | [freeradius-entra-id-oauth2](https://github.com/baljindrasingh/freeradius-entra-id-oauth2) | FreeRADIUS + Microsoft Entra ID OAuth2 for WPA2-Enterprise — EAP-TTLS, Azure AD app, Graph API, token caching, TLS hardening |
| 8 | [hybrid-azure-ad-join](https://github.com/baljindrasingh/hybrid-azure-ad-join) | Hybrid Azure AD Join — Proxmox, MS Server 2022, Entra Connect Sync with hard matching for 250 unified user identities |
| 9 | [azure-ad-sso-fortigate-saml](https://github.com/baljindrasingh/azure-ad-sso-fortigate-saml) | Azure AD SAML SSO for FortiGate SSL VPN — Azure AD as IdP, MFA + Conditional Access, group-based RBAC mapping |
| 10 | [crowdstrike-sso-azure-ad](https://github.com/baljindrasingh/crowdstrike-sso-azure-ad) | CrowdStrike Falcon + Azure AD SSO — SAML authentication, MFA, Conditional Access, role-based access via Azure AD groups |

### 📡 Security & Monitoring

| # | Repository | Description |
|---|-----------|-------------|
| 11 | [prometheus-grafana-netbird-monitoring](https://github.com/baljindrasingh/prometheus-grafana-netbird-monitoring) | Prometheus + Grafana + Node Exporter — dashboards, Alertmanager (Slack/email/webhook), TLS, multi-server scrape configs |
| 12 | [fortigate-syslog-crowdstrike-siem](https://github.com/baljindrasingh/fortigate-syslog-crowdstrike-siem) | FortiGate syslog on RHEL — Rsyslog config, daily log rotation (7-day retention), Humio Log Collector → CrowdStrike SIEM |
| 13 | [fortinet-crowdstrike-soar](https://github.com/baljindrasingh/fortinet-crowdstrike-soar) | FortiGate Cloud + CrowdStrike Falcon SOAR — automated threat detection, dynamic firewall policy updates, device isolation playbooks |

### 🖥️ Endpoint Management

| # | Repository | Description |
|---|-----------|-------------|
| 14 | [firefox-url-filtering-intune](https://github.com/baljindrasingh/firefox-url-filtering-intune) | Firefox URL filtering via Intune — ADMX templates, OMA-URI policies, enterprise policy registry key, deployed across 200+ Windows endpoints |

---

## 📈 Current Focus

- 🔐 Zero-trust mesh networking with NetBird at enterprise scale
- 🤖 Just-In-Time access automation — Jira + NetBird API + AWS Lambda
- 📡 Security observability — CrowdStrike Falcon LogScale pipelines
- 🧪 Infrastructure automation with Ansible across hybrid Windows + Linux environments

---

## 📬 Connect

- 💼 [LinkedIn](https://linkedin.com/in/baljindrasingh) — feel free to connect or DM

---

<p align="center">
  <img src="https://img.shields.io/badge/NetBird-Zero%20Trust-1F4E79?style=flat-square" />
  <img src="https://img.shields.io/badge/AWS-Lambda%20%7C%20EC2-FF9900?style=flat-square&logo=amazonaws" />
  <img src="https://img.shields.io/badge/CrowdStrike-Falcon%20LogScale-E01B22?style=flat-square" />
  <img src="https://img.shields.io/badge/Ansible-Automation-EE0000?style=flat-square&logo=ansible" />
  <img src="https://img.shields.io/badge/Microsoft-Entra%20ID-0078D4?style=flat-square&logo=microsoftazure" />
  <img src="https://img.shields.io/badge/Docker-Compose-2496ED?style=flat-square&logo=docker" />
  <img src="https://img.shields.io/badge/FortiGate-Security-EE3124?style=flat-square" />
  <img src="https://img.shields.io/badge/RHEL-9-EE0000?style=flat-square&logo=redhat" />
</p>
