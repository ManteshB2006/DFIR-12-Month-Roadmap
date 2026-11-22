# Practical DFIR Labs

Complete these labs in order as the relevant topics appear in the roadmap. Use only systems and datasets you own or are authorised to investigate.

## Foundation labs
- [ ] Explore Windows processes, services, users, and startup entries.
- [ ] Explore Linux processes, permissions, and system logs.
- [ ] Capture normal DNS and web traffic in Wireshark.
- [ ] Identify DNS queries, TCP handshakes, and common protocols in a PCAP.

## Windows forensics labs
- [ ] Export and inspect Windows Security and System event logs.
- [ ] Identify successful and failed logon activity in a training dataset.
- [ ] Configure Sysmon in a disposable VM and inspect generated events.
- [ ] Examine Prefetch, LNK, Jump Lists, and browser artefacts from a lab image.
- [ ] Build a timeline from at least two independent artefact sources.

## Disk-forensics labs
- [ ] Hash a test file with SHA-256 and verify it after copying.
- [ ] Acquire a test disk image and document the process.
- [ ] Open a training image in Autopsy and inspect its file system.
- [ ] Recover selected deleted files from a training image.
- [ ] Record relevant NTFS artefacts and explain their meaning.

## Memory-forensics labs
- [ ] Run basic Volatility 3 identification and process-listing plugins.
- [ ] Examine process command lines and parent-child relationships.
- [ ] Inspect network-related artefacts in a memory image.
- [ ] Correlate a memory finding with endpoint logs where possible.

## Network-forensics labs
- [ ] Analyse a training PCAP and identify key communicating hosts.
- [ ] Investigate suspicious DNS or HTTP activity in a supplied dataset.
- [ ] Generate Zeek logs from a PCAP.
- [ ] Create a timeline of relevant network events.

## SIEM and threat-hunting labs
- [ ] Ingest sample logs into Splunk or Elastic.
- [ ] Write a query for repeated failed logons.
- [ ] Correlate endpoint and network events.
- [ ] Write a hunt hypothesis and identify required telemetry.
- [ ] Create and test a basic YARA rule against benign test files.
- [ ] Run an authorised Velociraptor collection in a lab.

## Incident-response labs
- [ ] Triage a simulated endpoint compromise.
- [ ] Create an evidence inventory and incident timeline.
- [ ] Identify likely scope and affected assets from supplied evidence.
- [ ] Recommend containment steps while preserving evidence.
- [ ] Write an incident report with facts, hypotheses, and limitations.

## Lab report template
1. Objective and scope
2. Environment and tool versions
3. Dataset source and authorisation
4. Evidence identifiers and hashes, where applicable
5. Steps and commands
6. Observations and findings
7. Interpretation and confidence
8. Limitations
9. Lessons learned
