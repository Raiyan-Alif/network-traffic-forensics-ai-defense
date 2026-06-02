# Network Traffic Monitoring, Forensic Analysis, & AI-Driven Defence

## Project Overview
This project presents a comprehensive, two-phased approach to modern cybersecurity engineering, carefully balancing offensive forensic analysis with defensive artificial intelligence paradigms. 

## Phase 1: Offensive Operations & Data Forensics Pipeline
* **Reconnaissance & Vulnerability Assessment:** Executed an active network pipeline against a controlled target environment (Metasploitable 2) utilizing industry-standard network sensors and scanners including `tcpdump`, `nmap`, and `Nikto`.
* **Denial of Service (DoS) Testing:** Deployed a Slowloris Denial of Service attack to evaluate system resilience under resource depletion constraints.
* **Forensic Analysis:** Analyzed resulting packet capture (`.pcap`) files and Apache server logs (`final_access.log`) to validate automated attack signatures.
* **Key Findings:** Identifed distinctive traffic spikes, an anomalous ~3.5:1 HTTP 404 error ratio indicating directory enumeration, and high-density socket-exhaustion NetFlow patterns via the SiLK toolset.

## Phase 2: AI-Driven Defense Infrastructure
Shifting from reactive analysis to proactive mitigation, this phase explores the integration of Large Language Models (LLMs) into production security infrastructure. Three paradigms are evaluated:
1.  **LLM-Based Log & Alert Analysis:** Automating the parsing and summarization of raw security logs.
2.  **LLM-Assisted Cyber Threat Intelligence (CTI) Synthesis:** Mapping unstructured threat intelligence directly to the **MITRE ATT&CK framework**.
3.  **Agent-Based Incident Response Assistance:** Utilizing autonomous agents to assist in real-time incident triage and response workflows.

## Governance & Technology Adoption
The project establishes a formal strategic technology adoption roadmap, targeted training programs, and a risk governance framework to deploy defensive AI systems safely within enterprise environments.
