# Elijah Marcisz — Portfolio Site

## Owner
- Name: Elijah Marcisz
- Role: Cybersecurity Analyst (SOC & GRC track)
- Email: elijah.marcisz5@gmail.com
- GitHub: github.com/eli-the-marcsman
- LinkedIn: linkedin.com/in/elijah-marcisz
- Location: Chicago metro area (relocating from Fort Wayne, IN)
- Education: B.S. Cybersecurity & Global Policy, Indiana University Bloomington, June 2026
- Certifications: ISC2 Certified in Cybersecurity (CC) - In Progress
- Clearance: Eligible for U.S. Secret Security Clearance

## Site Goal
Single-page portfolio targeting SOC Analyst and GRC Analyst recruiters at
boutique cybersecurity firms (Apex, Echelon, SideChannel, Plante Moran)
and enterprise SOC roles (Cboe Global Markets). Must be deploy-ready as
a GitHub Pages site (index.html at repo root).

## Design Direction
- Dark background, cyan accent (#00D4FF), terminal/SOC aesthetic
- Fonts: Space Grotesk (display) + Inter (body) + JetBrains Mono (labels/tags)
- Clean, consulting-grade — not a student project page
- Mobile responsive
- No frameworks, no build tools — pure HTML/CSS/JS single file

## Sections
1. Hero — name, title, one-line thesis, links to GitHub/LinkedIn/email
2. About — IU grad, cybersecurity + global policy background, targeting Chicago market
3. Skills — grouped: SIEM & Detection | Threat Intelligence | GRC & Compliance |
   Incident Response | Networking & Systems | Development
4. Projects — cards with title, description, tags, highlight stats, GitHub link
5. Experience — Steel Dynamics internship (Summer 2022, Splunk monitoring,
   phishing simulations), Meijer part-time
6. Contact — email, GitHub, LinkedIn

## Projects (use exactly this content)

### Wazuh SIEM/XDR Detection Lab
Tags: Wazuh · MITRE ATT&CK · NIST CSF 2.0 · CIS Controls v8 · Docker · Atomic Red Team
Description: Deployed Wazuh SIEM/XDR on Docker/WSL2 and executed five simulated
adversary techniques using Atomic Red Team, mapped to MITRE ATT&CK tactics.
Produced a consulting-grade Security Assessment Report, IR Runbook, Findings Log,
Control Assessment Matrix, and Executive Briefing aligned to NIST CSF 2.0 and
CIS Controls v8.
Stats: 5 ATT&CK simulations | 4 confirmed detections | 50% MITRE coverage

### Ransomware Tabletop Exercise — Maplewood Regional Medical Center
Tags: NIST SP 800-61 · HIPAA · Incident Response · GRC
Description: Designed and facilitated a ransomware TTX for a fictional healthcare
organization simulating a full LockBit 3.0 incident lifecycle from initial compromise
to recovery. Mapped to NIST SP 800-61 IR phases and HIPAA Breach Notification Rule.
Stats: Healthcare sector focus | Full IR lifecycle | Regulatory mapping

### MITRE ATT&CK Threat Map
Tags: MITRE ATT&CK · Threat Intelligence · Wazuh · Detection Engineering
Description: Built a cross-referenced threat map correlating MITRE ATT&CK techniques
against confirmed Wazuh detections. Documents 7 tactics, 8 techniques, 4 confirmed
detections, and a clear visual of detection coverage gaps.
Stats: 7 tactics | 8 techniques | 50% detection coverage

### Flask Help Desk Ticketing System
Tags: Python · Flask · MariaDB · RBAC · bcrypt · Security Engineering
Description: Built a full-stack help desk ticketing system with role-based access
control (RBAC) and bcrypt password hashing demonstrating secure application
development, least privilege, and audit trail functionality.

### Python Network Security Audit Tool
Tags: Python · Networking · TCP/IP · Security Auditing
Description: Built a Python-based network security audit tool for scanning and
analyzing network configurations, demonstrating applied networking fundamentals
and security assessment skills.

## Claude Code Permissions
permissions.allow:
  - Bash(git *)
  - Bash(ls *)
  - Bash(cat *)
  - Bash(mkdir *)
  - Bash(touch *)
  - Bash(mv *)
  - Bash(cp *)

permissions.deny:
  - Bash(curl *)
  - Bash(wget *)
  - Bash(rm -rf *)

## Style Rules
- No em dashes anywhere
- Sentence case for all headings and labels
- Consulting-grade copy, not student project copy
- Keep it tight — recruiters spend 30 seconds on this page
