# Incident Response Coursework Portfolio

A five-project incident-response portfolio built in an isolated virtual lab. It demonstrates response planning, Windows event-log analysis, evidence-preservation documentation, a discussion-only ransomware tabletop, and an integrated executive/technical case assessment.

> **Educational case study.** The SecureMart organization and incident are coursework scenario material. Observed activity is limited to the retained lab artifacts described in the reports. This portfolio does not claim a production breach, ransomware execution, data theft, or a completed enterprise recovery.

## Project reports

| Project | Focus | Report |
|---|---|---|
| 1 | Incident response plan, roles, severity, escalation, and reusable templates | [PDF](reports/Project-01_Report_FINAL.pdf) | [DOCX](reports/Project-01_Report_FINAL.docx) |
| 2 | Lab service discovery, Windows authentication telemetry, event correlation, and UTC timeline | [PDF](reports/Project-02_Report_FINAL.pdf) | [DOCX](reports/Project-02_Report_FINAL.docx) |
| 3 | Evidence inventory, integrity checks, response-phase status, and recovery gaps | [PDF](reports/Project-03_Report_FINAL.pdf) | [DOCX](reports/Project-03_Report_FINAL.docx) |
| 4 | Six-inject ransomware discussion tabletop and after-action review | [PDF](reports/Project-04_Report_FINAL.pdf) | [DOCX](reports/Project-04_Report_FINAL.docx) |
| 5 | Advanced integrated executive and technical engagement report | [PDF](reports/Project-05_Advanced-Full-IR-Engagement_Report_FINAL.pdf) | [DOCX](reports/Project-05_Advanced-Full-IR-Engagement_Report_FINAL.docx) |
| Portfolio | Consolidated review of all five projects and their evidence boundaries | [PDF](reports/Cyber_Project_Integrated_IR_Report_FINAL.pdf) | [DOCX](reports/Cyber_Project_Integrated_IR_Report_FINAL.docx) |

## Case summary

The reports analyze a controlled Windows SMB authentication sequence in a private virtual lab, correlate selected Windows Security and System events, and separately document a later one-shot administrative validation. The evidence supports the specific events described in each report; it does not establish unauthorized access to a real organization or data exfiltration. A separate ransomware scenario was conducted as a paper tabletop, without running ransomware or changing a VM.

## Method and tools

The documented workflow uses a segmented VMware lab, Nmap for authorized service discovery, Windows Event Viewer and exported EVTX records for event review, PowerShell and audit policy queries for host configuration context, and SHA-256 comparisons for selected evidence-integrity checks. Evidence sources, event IDs, UTC chronology, confidence, limitations, and follow-up recommendations are explained in the reports.

## Repository layout

```text
reports/      Six de-identified project and portfolio reports (PDF + editable DOCX)
README.md     Project overview and scope
SECURITY.md   Public-release and evidence-handling boundaries
```

## Public-release handling

This repository intentionally contains curated, de-identified reports only. Raw EVTX files, live-response archives, screenshots, candidate credentials, account identifiers, hostnames, and exact lab addresses are excluded. Names and lab identifiers appearing in the source reports were replaced in this public copy.

## Academic context

Prepared as coursework for Incident Response Handling. The original private submission folder remains the source of the complete evidence package. Please cite this repository as an educational case study if reusing its structure.



