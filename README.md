# Blue Team · Detection & Automation · Systems Programming

I build SOC labs, write up investigations, and work at the level of the systems underneath them. Open to SOC analyst and blue-team roles, and to security-flavoured software roles.

**Stack:** Splunk · Wazuh · Elastic · Sysmon · Shuffle · MITRE ATT&CK · Wireshark · C and C++

[Security labs](#security-labs) · [Write-ups](#write-ups) · [Software projects](#software-projects) · [Toolbox](#toolbox)

## Security labs

| Lab | What it does |
|---|---|
| [SOC Automation Lab](https://github.com/Nikat0r/SOC-Automation-Lab) | SOC pipeline built on Wazuh, Shuffle (SOAR), TheHive and VirusTotal, detecting Mimikatz |
| [AD Security Automation Lab](https://github.com/Nikat0r/AD-Security-Automation-Lab) | Splunk, Active Directory and Shuffle: detects suspicious RDP activity and disables the account only after analyst approval |
| [Atomic Detonation Lab](https://github.com/Nikat0r/Atomic-Detonation-Lab) | Atomic Red Team tests run on a Sysmon-instrumented host, with logs in Splunk Cloud and detections mapped to MITRE ATT&CK |

## Write-ups

Investigation write-ups from hands-on rooms: the scenario, the tools, the approach, the detection takeaways and the mistakes I made. All in [Write-ups](https://github.com/Nikat0r/Write-ups).

- [Tempest](https://github.com/Nikat0r/Write-ups/tree/main/tryhackme/tempest): a full intrusion reconstructed from Sysmon, Windows logs and a packet capture
- [Boogeyman 1-3](https://github.com/Nikat0r/Write-ups/tree/main/tryhackme/boogeyman): email analysis, PowerShell logs, DNS exfiltration, memory forensics and ELK
- [Fixit](https://github.com/Nikat0r/Write-ups/tree/main/tryhackme/fixit): repairing Splunk ingestion and field extraction
- [ShadowTrace](https://github.com/Nikat0r/Write-ups/tree/main/tryhackme/shadowtrace): static triage of a suspicious binary

## Software projects

Low-level C and C++ from the 42 Network curriculum. The full list is in [42-projects](https://github.com/Nikat0r/42-projects).

| Project | What it is |
|---|---|
| [megashell](https://github.com/Nikat0r/megashell) | A bash-like shell in C: lexer, parser and AST, expansion, pipes, redirections, heredocs, subshells |
| [ft_containers](https://github.com/Nikat0r/ft_containers) | The C++ vector, map, stack and set rebuilt in C++98, with a red-black tree map |
| [webserv](https://github.com/Nikat0r/webserv) | An NGINX-like HTTP server in C++ with I/O multiplexing and CGI |

## Toolbox

**Hands-on** (used in my labs and write-ups)

| Area | Tools |
|---|---|
| SIEM and logging | Splunk, Wazuh, Elastic (Kibana), Sysmon, Windows Event Logs |
| SOAR and case management | Shuffle, TheHive, VirusTotal |
| Detection and adversary emulation | MITRE ATT&CK, Atomic Red Team |
| Investigation and forensics | Wireshark, tshark, Volatility |
| Scripting | Bash, PowerShell |
| Vulnerability management | Qualys VMDR |
| Environments | Active Directory, Windows, Linux, Docker |
| Languages | C, C++ |

**Training coverage**

| Area | Covered |
|---|---|
| SOC operations | Alert triage, classification and escalation, incident reporting and documentation |
| SOC solutions | SIEM (Splunk and Elastic), EDR and SOAR concepts |
| Phishing analysis | Email header analysis, malicious attachments, phishing prevention |
| Network analysis and monitoring | Wireshark, tshark, Snort, Zeek, NetworkMiner |
| Endpoint monitoring | Windows event logs, Sysmon, Sysinternals, Osquery, Windows registry forensics |
| Threat intelligence | MISP, OpenCTI, YARA |
| Offensive basics | Nmap, Metasploit, Burp Suite, SQL injection basics, Hydra, Gobuster |

[**TryHackMe**](https://tryhackme.com/p/Nikator): top 1% globally

**Currently learning:** detection engineering with Sigma, threat hunting, Microsoft Sentinel and KQL, Python.
