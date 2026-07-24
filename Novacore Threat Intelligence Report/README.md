# Threat Actor Profiling & Risk Assessment — Novacore Financial Services

A threat intelligence project profiling financially motivated cyber threat groups relevant to a fintech payment processor, and producing a full risk assessment and defensive recommendations.

## Overview

Novacore Financial Services (case study) is a fintech providing payment processing and digital wallet services to SMB clients, assumed to operate in Germany / the EU. 

This project:

- Profiles five financially motivated threat groups (FIN7, Lazarus Group, Scattered Spider, Evil Corp, TA505/Clop)
- Compares and ranks them by relevance to Novacore's business model and region
- Selects **Evil Corp (Indrik Spider / UNC2165)** for deep-dive analysis
- Examines a famous historical attack (Garmin / WastedLocker, 2020) and a recent campaign (2024-2026 enforcement action and continued activity)
- Produces a risk assessment and a set of preventive, detection, and response recommendations

## Methodology

Threat group profiles and TTP mappings are built from [MITRE ATT&CK](https://attack.mitre.org) group pages, combined with current vendor and government reporting (CrowdStrike, NCA, CISA, and others).

## Key Findings

| | |
|---|---|
| **Groups assessed** | 5 |
| **Selected threat group** | Evil Corp (Indrik Spider / UNC2165) |
| **Overall risk rating** | Medium-High |
| **Top recommendation** | Phishing-resistant MFA + email security controls |

## Files

- `Novacore_Threat_Intelligence_Capstone_Report.pdf` - full written report.

## Skills Demonstrated

- Threat actor profiling and comparative analysis
- MITRE ATT&CK tactic/technique mapping
- Risk assessment (likelihood/impact modeling)
- Regulatory context awareness (GDPR, PSD2, DORA)
- Threat intelligence report writing
