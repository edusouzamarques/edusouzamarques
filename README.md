# Eduardo de Souza Marques
### AI Safety / Agent-Governance & Cybersecurity Professional

I build control planes for autonomous agents and defend enterprise digital infrastructure. My work bridges **AI safety guardrails, verifiable audit ledgers, and applied cybersecurity operations (GRC, SOC & Network Hardening)**.

---

## 🎯 Hands-on Cybersecurity Portfolio (Simulated Scenarios & Audit Labs)

A dedicated operational showcase of hands-on incident investigations, compliance audits, and security simulations derived from the **Google Cybersecurity Professional Certificate** and industry frameworks (NIST CSF / NIST SP 800-53 / NIST SP 800-63B / CIS Controls / GDPR):

```mermaid
flowchart TD
    subgraph GRC["1. Governance, Risk & Access Control (GRC & AAA)"]
        L1["<b>GRC & Compliance Audit</b><br/>Botium Toys Security Audit<br/><i>NIST CSF / Scope / Controls</i>"]
        L2["<b>Data Leak Prevention & Least Privilege</b><br/>Data Leak Prevention (NIST AC-6)<br/><i>DLP / Auto-Revocation / RBAC</i>"]
        L3["<b>Access Control & AAA Audit</b><br/>Payroll Incident Audit (Event 1227)<br/><i>AAA / Non-Repudiation / Dual-Auth</i>"]
    end

    subgraph Defense["2. Network & System Hardening"]
        L4["<b>Perimeter & Access Hardening</b><br/>Network Hardening & Risk Assessment<br/><i>MFA / Port Filtering / SIEM</i>"]
        L5["<b>Incident Response & DoS Defense</b><br/>DoS ICMP Flood Incident Report<br/><i>NIST CSF / Rate Limiting / uRPF</i>"]
        L6["<b>Linux Authorization & Least Privilege</b><br/>Linux File Permissions Audit<br/><i>chmod / ls -la / Access Control</i>"]
    end

    subgraph Forensics["3. Forensics & SOC Data Analysis"]
        L7["<b>Network Forensics & Packet Analysis</b><br/>tcpdump Incident Investigation<br/><i>DNS & HTTP Malware Triage</i>"]
        L8["<b>SQL SOC Triage & Log Filtering</b><br/>SQL Security Incident Investigation<br/><i>AND / OR / NOT / LIKE Telemetry</i>"]
    end

    subgraph Hub["🌐 Live Portfolio Hub"]
        Web["GitHub Pages Showcase<br/><b>edusouzamarques.github.io/cybersec</b>"]
    end

    GRC --> Hub
    Defense --> Hub
    Forensics --> Hub
```

### 📋 Practical Lab Repositories

#### 1. [🛡️ Botium Toys Security Audit (GRC & Compliance)](https://github.com/edusouzamarques/botium-toys-security-audit)
- **Focus:** Governance, Risk, and Compliance (GRC), Internal Audit, and Risk Assessment.
- **Scenario:** Comprehensive security audit of an international toy company preparing for modern digital expansion.
- **Deliverables:** Complete stakeholder-ready audit report, NIST CSF alignment matrix, scope boundaries, risk register, and [executive PDF report](https://edusouzamarques.github.io/cybersec/Botium_Toys_Security_Audit_Report.pdf).

#### 2. [📋 Data Leak Prevention & Least Privilege Lab (NIST SP 800-53: AC-6)](https://github.com/edusouzamarques/data-leak-prevention-nist-ac6)
- **Focus:** Data Loss Prevention (DLP), Access Control Lists, and NIST SP 800-53 Control AC-6.
- **Scenario:** Triage and remediation of an internal data leak at an EdTech firm where confidential product roadmaps were shared externally due to lack of link expiration and over-provisioned access.
- **Deliverables:** Formal Data Leak Worksheet, NIST CSF mapping (PR.DS-5), and an executable Python simulation validating expiring TTL links and role-based sharing blocks.

#### 3. [🔑 Access Control & AAA Framework Audit Lab (NIST SP 800-53 / CIS Controls)](https://github.com/edusouzamarques/access-control-aaa-audit-lab)
- **Focus:** Authentication, Authorization, Accounting (AAA), Non-Repudiation, and Dual-Authorization.
- **Scenario:** Forensic triage of unauthorized payroll routing changes (Event ID 1227) executed via a shared `Legal\Administrator` account from a rogue external machine (`Up2-NoGud`).
- **Deliverables:** Formal Access Controls Worksheet report, target-state Zero Trust architecture, and executable Python simulation enforcing RBAC and Maker-Checker dual authorization.

#### 4. [🔒 Network Hardening & Security Risk Assessment Lab](https://github.com/edusouzamarques/network-hardening-security-risk-assessment)
- **Focus:** Network Defense, Perimeter Port Filtering, Password Policies, and Multi-Factor Authentication.
- **Scenario:** Remediation of a social media platform breach caused by exposed database ports, vendor-default passwords, and lack of MFA.
- **Deliverables:** Formal risk assessment report, defense-in-depth architecture, and executable Python simulation engine reproducing the breach and validating hardened controls.

#### 5. [⚡ DoS (ICMP Flood) Incident Report Analysis (NIST CSF)](https://github.com/edusouzamarques/dos-icmp-flood-incident-report-nist-csf)
- **Focus:** Incident Response (IR), Denial of Service (DoS) Containment, and NIST CSF 5-Function Lifecycle.
- **Scenario:** Triage, containment, and recovery of a 2-hour network blackout caused by an ICMP ping flood exploiting an unconfigured firewall.
- **Deliverables:** Full NIST CSF incident report (Identify, Protect, Detect, Respond, Recover) and Python simulation demonstrating interface queue overflow vs. rate-limiting and anti-spoofing (uRPF).

#### 6. [🔑 Linux File Permissions & Least Privilege Audit Lab](https://github.com/edusouzamarques/linux-file-permissions-least-privilege-audit)
- **Focus:** Operating System Hardening, Access Control Lists (ACLs), and Principle of Least Privilege (PoLP).
- **Scenario:** Security audit of research team files (`/home/researcher2/projects`), revoking unauthorized world-write permissions, locking down archived files, and isolating sensitive subdirectories.
- **Deliverables:** Comprehensive audit report with terminal telemetry and reproducible Bash automation script.

#### 7. [🔍 SQL Security Incident Investigation & Telemetry Filtering Lab](https://github.com/edusouzamarques/sql-security-incident-investigation-lab)
- **Focus:** Database Security, SOC Incident Triage, and Authentication Log Analysis via SQL.
- **Scenario:** Investigating after-hours failed login spikes, isolating multi-day breach timelines, detecting foreign IP anomalies, and segmenting employee workstations for vulnerability patching.
- **Deliverables:** Formal triage report, standalone SQLite database instance, and automated query execution engine.

#### 8. [📡 tcpdump Incident Investigation & Packet Analysis Lab](https://github.com/edusouzamarques/tcpdump-incident-investigation-lab)
- **Focus:** Network Protocol Analysis, Threat Hunting, and Packet Sniffing (`tcpdump`).
- **Scenario:** Triage of a compromised web server executing unauthorized JavaScript browser redirection to a malicious domain.
- **Deliverables:** Real packet trace analysis, TCP 3-way handshake dissection, DNS/HTTP correlation, and packet analysis cheat sheet.

👉 **Explore the interactive portfolio showcase:** [edusouzamarques.github.io/cybersec](https://edusouzamarques.github.io/cybersec/)

---

## 🤖 AI Safety, Agent-Governance & Control Planes

Every library in this section exists because an autonomous agent failed in a way that generic tooling could not catch. The shared thesis: AI systems need the same properties as high-risk operational software — pre-execution gates, adversarial review, structured recovery, cost containment, and tamper-evident provenance.

### 🛡️ Safety & Governance of Autonomous Agents
- [`agent-gates`](https://github.com/edusouzamarques/agent-gates) — Pre-execution gates that intercept tool calls and return `allow` / `ask` / `deny` with a structured reason, so the host — not the model — has final authority.
- [`polycourt`](https://github.com/edusouzamarques/polycourt) — Cross-vendor LLM jury with quorum, circuit-breaker, fallback, and persisted deliberation for auditable decisions.
- [`devil-advocate`](https://github.com/edusouzamarques/devil-advocate) — Adversarial panel that attacks plans, designs, and diffs with severity-based dedup, a completeness-guard that refuses fragments, and default-REFUTED adjudication.
- [`deputy`](https://github.com/edusouzamarques/deputy) — Bounded delegation for autonomous agents: reserved zones no quorum can unlock, a cap on consecutive self-authorizations, and a journal that makes a dead mechanism visible.

### 🔁 Reliability & Recovery
- [`error-registry`](https://github.com/edusouzamarques/error-registry) — Structured error taxonomy for triage, routing, and automatic recovery without halting operations.
- [`durable-context`](https://github.com/edusouzamarques/durable-context) — Long-term memory with atomic persistence of agent session and execution state.
- [`steady-driver`](https://github.com/edusouzamarques/steady-driver) — Headless browser driver tolerant to crashes, blocks, and disconnections.

### 💰 Cost Governance (FinOps for AI)
- [`spend-guard`](https://github.com/edusouzamarques/spend-guard) — Budget kill-switch and token limiter per agent, project, and hour.
- [`gpu-spot-guard`](https://github.com/edusouzamarques/gpu-spot-guard) — Monitors spot-GPU lifecycle and checkpoints state before preemption.
- [`lane-router`](https://github.com/edusouzamarques/lane-router) — Routes simple prompts to cheap models and reserves expensive ones for reasoning — up to 85% cost reduction.

### 🧭 Tooling & Orchestration
- [`mcp-navigator`](https://github.com/edusouzamarques/mcp-navigator) — Dynamic tool index and resolver via Model Context Protocol.
- [`comfy-ui2api`](https://github.com/edusouzamarques/comfy-ui2api) — Converts ComfyUI visual workflows into production headless API endpoints.
- [`video-assembly-kit`](https://github.com/edusouzamarques/video-assembly-kit) — Programmatic video editing, cutting, concatenation, and captioning via pure ffmpeg.

### 🔗 Provenance & Audit
- [`asset-ledger`](https://github.com/edusouzamarques/asset-ledger) — Immutable ledger with cryptographic hashes for AI-generated media — provenance, anti-deepfake, chain of custody.

---

## Why a former police officer builds AI guardrails & Cybersecurity defenses

Thirteen years in the military police teaches you that systems fail at the worst possible moment, that people will exploit any ambiguity, and that a decision only matters if you can reconstruct how it was made. Chain-of-custody is not a buzzword when it has to hold up in court. I bring that same rigor to agent governance and cybersecurity: assume adversarial conditions, enforce boundaries before execution, and keep records that survive scrutiny.

---

## 📬 Stack & Contact

- **Cybersecurity Standards:** NIST CSF · NIST SP 800-53 (AC-6 / PR.DS-5) · CIS Controls v8 · GDPR / LGPD · SQL / MariaDB · Wireshark / tcpdump · SIEM
- **AI Stack:** Python 3.9+ · zero-dependency · ~3,400 tests · CI on Linux/macOS/Windows · MIT licensed
- **Contact:** [LinkedIn — /in/edusouzamarques](https://www.linkedin.com/in/edusouzamarques) · eduardo@zemark.dev
