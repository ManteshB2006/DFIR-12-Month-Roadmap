# Month 12 Capstone — Simulated Endpoint Intrusion

## Scenario
A fictional organisation reports unusual endpoint activity. You receive a synthetic Windows event-log bundle, a benign training PCAP and a lawful training memory image. This is a simulated exercise.

## Objectives
- Define scope and investigation questions.
- Inventory evidence and verify provided hashes.
- Identify relevant endpoint and network events.
- Build a UTC-normalised timeline.
- Correlate independent evidence sources for major findings.
- Identify potential indicators and map supported behaviour to MITRE ATT&CK.
- State uncertainty, alternative explanations and missing evidence.
- Recommend containment, recovery and detection improvements.

## Required artefacts
Use the [investigation report template](../templates/INVESTIGATION-REPORT.md).
- Executive summary
- Evidence inventory and hash log
- Methodology and tool versions
- Timeline
- Evidence-backed findings
- IOC table and ATT&CK mapping
- Limitations and recommendations
- Sanitised screenshots and reproducibility instructions

## Assessment rubric (100 points)
| Area | Points |
|---|---:|
| Scope, authorisation and evidence integrity | 15 |
| Correct tool use and reproducibility | 15 |
| Quality of artefact analysis | 20 |
| Timeline and cross-source correlation | 15 |
| Evidence-backed findings and uncertainty | 15 |
| Recommendations and communication | 10 |
| Safe portfolio publication | 10 |

Do not use real ransomware, execute malware or test against a live organisation. Use inert synthetic artefacts only.
