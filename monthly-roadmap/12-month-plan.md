# 12-Month DFIR Learning Plan

**Starting level:** Beginner  
**Study pace:** 3 hours per day, 6 days per week  
**Goal:** Build practical digital-forensics and incident-response skills through progressive labs and documented investigations.

## Month 1 — Computer and operating-system fundamentals
**Learn:** Hardware, CPU, RAM, storage, partitions, file systems, processes, services, users, permissions, Windows architecture, and command-line basics.

**Practise:** Inspect Windows processes and services; explore users and startup applications; create a Linux VM; learn shell navigation; document normal system activity.

**Deliverable:** Windows and Linux fundamentals notebook with commands and screenshots.

## Month 2 — Networking and Linux
**Learn:** TCP/IP, OSI model, IPv4 and subnetting basics, DNS, DHCP, ARP, HTTP/S, SSH, SMTP, ports, routing, NAT, firewalls, Linux permissions and logs.

**Practise:** Use ipconfig, ping, tracert, nslookup, and netstat; inspect Linux logs; capture traffic in Wireshark; identify DNS queries and TCP handshakes.

**Deliverable:** Network fundamentals notes and an annotated PCAP of normal traffic.

## Month 3 — Windows forensic artefacts
**Learn:** Windows Registry, EVTX logs, Prefetch, LNK files, Jump Lists, Recycle Bin, UserAssist, ShellBags, scheduled tasks, services, and browser history.

**Practise:** Inspect logs with Event Viewer and PowerShell; examine training artefacts with Eric Zimmerman's tools; identify evidence of logons and program execution; create a basic timeline.

**Deliverable:** Windows artefact reference sheet explaining investigative value and limitations.

## Month 4 — Event logs and endpoint investigation
**Learn:** Security, System, and Application logs; logon events; account changes; process creation; Sysmon events; event correlation and timestamps.

**Practise:** Install Sysmon in a disposable VM; generate benign test activity; investigate failed logons and suspicious PowerShell activity in training data; correlate events into a timeline.

**Deliverable:** Simulated endpoint investigation report.

## Month 5 — Evidence handling and disk acquisition
**Learn:** Forensic principles, chain of custody, evidence integrity, acquisition versus analysis, SHA-256 hashing, write-blocking concepts, disk images, MBR and GPT.

**Practise:** Hash and verify test files; acquire a test image with FTK Imager or an equivalent tool; document source, acquisition details, evidence identifiers, and hashes; analyse a verified copy.

**Deliverable:** Evidence inventory and acquisition record.

## Month 6 — File-system and disk forensics
**Learn:** NTFS, MFT, timestamps, alternate data streams, USN Journal, deleted files, unallocated space, file carving, file signatures, and metadata.

**Practise:** Examine a training image in Autopsy; recover selected deleted files; search for suspicious files and user activity; build a timeline and validate findings using another artefact where possible.

**Deliverable:** Disk-forensics report with evidence references and hashes.

## Month 7 — Memory forensics
**Learn:** RAM acquisition concepts; processes, threads, DLLs, handles, network connections, process-injection indicators, and Volatility 3 fundamentals.

**Practise:** Use a legitimate training memory image; identify processes and command lines; inspect network artefacts and loaded modules; investigate suspicious parent-child relationships; correlate with endpoint logs.

**Deliverable:** Memory-forensics report explaining findings and limitations.

## Month 8 — Network forensics
**Learn:** PCAP structure, TCP handshakes, DNS, HTTP, TLS metadata, scanning, beaconing, data-transfer indicators, and Zeek logs.

**Practise:** Analyse training PCAPs in Wireshark; inspect protocol details; run Zeek against a PCAP; interpret generated logs; create a network timeline.

**Deliverable:** Network investigation report with PCAP evidence references.

## Month 9 — SIEM and incident response
**Learn:** SIEM ingestion, parsing, correlation, alerts, dashboards; Splunk or Elastic searches; incident-response lifecycle; severity, escalation, incident notes, and communications.

**Practise:** Ingest sample endpoint and network logs; search for failed logons and unusual process activity; correlate alerts; draft an incident timeline and response actions.

**Deliverable:** Simulated incident ticket with queries, findings, and recommendations.

## Month 10 — Threat hunting and detection
**Learn:** Hypothesis-driven hunting, MITRE ATT&CK, YARA fundamentals, Velociraptor collections, indicators of compromise versus behavioural indicators.

**Practise:** Create a hunt hypothesis; search lab telemetry; write and test a basic YARA rule against benign test files; run an authorised Velociraptor collection in a lab.

**Deliverable:** Threat-hunting report with hypothesis, data sources, findings, and gaps.

## Month 11 — Malware and ransomware investigation
**Learn:** Safe malware-analysis workflow, isolation, static triage, hashes, strings, file metadata, imports, persistence, ransomware evidence, containment, backups, and recovery.

**Practise:** Use benign samples, purpose-built simulations, or vetted training datasets; perform static triage without executing unknown files; investigate simulated ransomware artefacts; map behaviours to ATT&CK.

**Deliverable:** Ransomware incident report based on a safe simulation or training dataset.

## Month 12 — End-to-end DFIR capstone
Conduct one integrated investigation using available endpoint, disk, memory, and/or network evidence.

**Tasks:** Define scope; document evidence sources; preserve and hash evidence; analyse artefacts; construct a timeline; identify indicators; map observed behaviours to ATT&CK; separate facts from inferences; recommend containment, eradication, and recovery actions.

**Final portfolio deliverables:** Executive summary, scope and methodology, evidence inventory and hashes, timeline, findings with evidence references, indicators, response recommendations, limitations, and lessons learned.

## Monthly review
- [ ] Explain the month's concepts without relying on notes.
- [ ] Complete at least one practical lab.
- [ ] Record tool versions, commands, and evidence.
- [ ] Write a short report another learner could follow.
- [ ] List gaps and priorities for the next month.

## Safety and integrity
Use only authorised systems and datasets. Keep original evidence separate from working copies. Do not execute unknown malware on your everyday computer. Never publish private or confidential evidence.
