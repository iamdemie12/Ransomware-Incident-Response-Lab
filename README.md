# Ransomware Incident Response Lab

## Project Overview
This project presents a scenario-based ransomware incident response case study involving HarborPoint Health, a fictional healthcare organisation. It examines how a security operations and incident response team could investigate, contain, eradicate, and recover from a ransomware attack affecting critical healthcare systems.

**Project type:** Cybersecurity case study and incident response planning

## Incident Scenario
HarborPoint Health experiences a ransomware incident involving encrypted electronic health record (EHR) and medical imaging systems, with suspected data exfiltration. The scenario highlights gaps in early detection, network segmentation, backup resilience, and incident communication.

## Project Objectives
- Develop a structured ransomware incident response approach.
- Identify opportunities for earlier threat detection and containment.
- Outline forensic investigation and evidence preservation procedures.
- Recommend strategies for secure recovery and backup validation.
- Improve incident communication, security monitoring, and organisational resilience.

## Tools and Technologies Discussed
- **Splunk Enterprise Security:** SIEM monitoring and proposed correlation searches.
- **Wireshark and Zeek:** Network traffic analysis.
- **YARA:** Proposed malware detection rules.
- **MISP:** Threat intelligence sharing and indicator enrichment.
- **Volatility:** Memory forensic analysis.
- **Autopsy / Sleuth Kit:** Disk forensic investigation.
- **EDR:** Endpoint detection and response capabilities.

These technologies are discussed as part of the proposed response approach; their inclusion does not imply that each tool was deployed or tested.

## Incident Response Methodology
1. **Preparation:** Identify critical assets, define responsibilities, review logging coverage, and establish backup and communication procedures.
2. **Detection and Analysis:** Review suspicious endpoint activity, authentication events, network connections, and potential indicators of compromise.
3. **Containment:** Isolate affected systems, restrict lateral movement, and preserve forensic evidence.
4. **Eradication:** Remove malicious persistence mechanisms and address exploited weaknesses.
5. **Recovery:** Restore validated backups, monitor restored systems, and verify the integrity of critical services.
6. **Lessons Learned:** Review detection gaps, response effectiveness, and long-term security improvements.

## Security Recommendations
- Improve SIEM and endpoint telemetry coverage.
- Introduce stronger network segmentation for critical healthcare services.
- Maintain immutable or offline backups and test restoration procedures.
- Integrate threat intelligence into detection workflows.
- Establish clear incident escalation and communication processes.
- Conduct regular tabletop exercises and ransomware response reviews.

## Project Deliverables
- HarborPoint Health ransomware incident response report.
- Proposed detection, investigation, containment, and recovery procedures.
- Security improvement recommendations and response performance objectives.

## Scope and Disclaimer
This is an educational, fictional healthcare ransomware scenario. The README describes an incident response design and case study, not a verified live incident or a fully implemented detection environment.

## Author
Peace Akinwale

Cybersecurity | SOC Analysis | Network Security | Incident Response | GRC
