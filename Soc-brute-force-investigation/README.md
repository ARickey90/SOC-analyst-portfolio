# SOC Brute Force - End-to-End Incident Investigation

4VM lab (Kali, Ubuntu, pfSense, Wazuh) simulating and investigating an SSH brute-force attack.

## Contents
- [Incident Report (PDF)](SOC-Incident-Report.pdf)
- Screenshots: recon, attack simulation, detection, response

## Evidence
1. [Reconnaissance](02-recon-nmap-scan.png)
2. [Attack Simulation](03-attack-hydra-brute-force.png)
3. [Traffic Capture](04-traffic-wireshark-capture.png)
4. [Detection — Dashboard](05a-detection-wazuh-dashboard.png)
5. [Detection — Event Detail](05b-detection-wazuh-event-detail-1.png) / [continued](05b-detection-wazuh-event-detail-2.png)
6. [MITRE ATT&CK Mapping](06-mitre-attck-mapping.png)
7. [Response — Containment](07-response-pfsense-rule.png)
