# Threat Hunting Training Platform
### Wazuh SIEM · KQL Query Practice · MITRE ATT&CK

An interactive, self-paced threat hunting training platform built around real-world attack scenarios. Students write actual Wazuh KQL queries in a simulated SIEM interface, learn real UI navigation steps, and map every technique to MITRE ATT&CK — all in the browser with no setup required.

---

## What's Covered

| Scenario | Attack Type | MITRE Techniques |
|---|---|---|
| 1 | SSH Brute-Force Detection | T1110.001 |
| 2 | Named Pipe Privilege Escalation | T1134.001 |
| 3 | Malicious Macro and Dropper | T1059.005, T1204.002 |
| 4 | Apache Rootkit Detection | T1014, T1543.002 |
| 5 | Data Staging and Exfiltration | T1560.001, T1041 |

---

## Features

- **Simulated Wazuh Discover interface** — write real KQL queries and see realistic log results come back
- **Exact syntax validation** — the query engine enforces real Wazuh KQL syntax and returns helpful error messages
- **Wazuh UI navigation walkthroughs** — step-by-step instructions for finding each artifact in a live Wazuh deployment
- **MITRE ATT&CK integration** — every scenario includes technique mappings with descriptions, and dedicated ATT&CK questions
- **Split layout** — query terminal and question panel visible simultaneously on every question step
- **Full sidebar navigation** — jump between scenarios at any time, track progress per scenario
- **KQL + MITRE reference page** — complete field reference and technique ID table accessible from the sidebar
- **20+ KQL queries to write** across 5 scenarios covering SSH, Sysmon, FIM, and Linux audit log fields
- **15 questions** — mix of KQL field identification and MITRE ATT&CK technique mapping
- **Score tracking** — live score badge and progress bar throughout

---

## Log Data

All IoC values in the simulated log database (IP addresses, usernames, filenames, timestamps, hashes) are fictional and do not match any real environment. Attack patterns, Wazuh rule IDs, Sysmon event IDs, and KQL field names are accurate to a real Wazuh deployment.
