# aws-soc-lab
Cloud-based SOC lab with ELK Stack SIEM, Windows log forwarding, and attack simulation using Atomic Red Team and Metasploit on AWS EC2
# 🛡️ Home SOC Lab on AWS

A fully functional Security Operations Center built on AWS using 
the ELK Stack for SIEM, Sysmon for Windows telemetry, and Atomic 
Red Team for attack simulation.

## Architecture
- **SOC-SIEM** (Ubuntu) — Elasticsearch, Logstash, Kibana
- **SOC-Windows-Victim** (Windows Server 2019) — Sysmon + Winlogbeat
- **SOC-Kali-Attacker** (Kali Linux) — Metasploit + Atomic Red Team

## Key Skills Demonstrated
- AWS VPC, EC2, Security Groups
- ELK Stack deployment and configuration
- Windows event log forwarding (Winlogbeat)
- Detection rule creation (MITRE ATT&CK aligned)
- Attack simulation and log analysis

## Results
Captured 5,000+ security events including:
- T1059.001 PowerShell abuse
- T1053.005 Scheduled task persistence  
- T1003.001 Credential dumping (LSASS)
- T1136.001 Local account creation

## Documentation
- [Full Setup Guide](docs/setup-guide.md)
- [Troubleshooting Log](docs/troubleshooting.md)
- [Error Prevention Guide](docs/error-prevention.md)
