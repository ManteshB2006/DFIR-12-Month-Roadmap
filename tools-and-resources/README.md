# DFIR Tools & Learning Resources

Learn tools when they support a concept or investigation. Do not try to install everything at once.

## Core tools
| Area | Tools | Use |
|---|---|---|
| Packet analysis | Wireshark | Inspect and filter network packets |
| Network monitoring | Zeek | Convert network traffic into structured logs |
| Disk forensics | Autopsy | Examine disk images and file-system artefacts |
| Acquisition | FTK Imager | Acquire and inspect forensic images |
| Memory forensics | Volatility 3 | Analyse memory captures |
| Windows artefacts | Eric Zimmerman's tools | Parse and examine Windows artefacts |
| Endpoint telemetry | Sysmon | Generate detailed Windows event telemetry |
| Endpoint collection | KAPE | Collect and process selected Windows artefacts |
| SIEM | Splunk or Elastic | Search, correlate, and visualise logs |
| Endpoint visibility | Velociraptor | Collect endpoint evidence and conduct hunts |
| Detection | YARA | Identify files matching rule-based patterns |

Check official documentation for current installation steps, supported versions, and licensing.

## Learning resources
- **13Cubed:** Windows forensics and memory-forensics education
- **CyberDefenders:** Blue-team and DFIR investigation labs
- **Blue Team Labs Online:** Practical defensive-security challenges
- **LetsDefend:** SOC investigation and alert-handling practice
- **MITRE ATT&CK:** Knowledge base of adversary tactics and techniques
- **Wireshark documentation:** Display filters and packet-analysis reference
- **Volatility Foundation documentation:** Volatility 3 usage and plugin reference
- **Autopsy documentation:** Disk-forensics workflow reference
- **Sysinternals documentation:** Windows system utilities and investigation support

## Suggested learning order
1. Windows, Linux, and networking fundamentals
2. Wireshark and Windows Event Viewer
3. Sysmon and Windows artefact parsers
4. FTK Imager and Autopsy
5. Volatility 3
6. Zeek
7. Splunk or Elastic
8. YARA and Velociraptor

## Lab safety
- Use disposable virtual machines and snapshots.
- Keep malware-analysis environments isolated from personal and production networks.
- Prefer vetted training datasets and benign simulations.
- Do not run unknown samples on your host machine.
- Respect dataset licences and platform rules.
