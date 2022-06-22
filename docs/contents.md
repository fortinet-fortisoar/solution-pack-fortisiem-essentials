| [Home](https://github.com/fortinet-fortisoar/solution-pack-fortisiem-essentials/blob/develop/README.md) | 
|--------------------------------------------|

# Contents

## Connectors

| Connector Name             | Description                                                                                                                                                                                                                      |
|:---------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Anomali ThreatStream       | This connector facilitates automated operations to to pull threat intelligence from the ThreatStream platform, import observables into ThreatStream from any source, manage threat model entities and investigations, and so on. |
| Fortinet Web Filter Lookup | Fortinet Web Filter Lookup allows users to check category and classification for any Domain.                                                                                                                                     |
| MxToolbox                  | MxToolbox offers monitoring solutions and lookup tools. Connector supports automated operations for Lookup, Monitor and Usage.                                                                                                   |
| URLVoid                    | URLVoid provides a service to analyze websites through multiple blacklist engines and online reputation tools to facilitate the detection of fraudulent and malicious websites.                                                  |
| VirusTotal                 | Scans and analyzes suspicious files, URLs, IP addresses and retrieves reports from VirusTotal about them.                                                                                                                        |

>**Warning:** After deployment, this Solution Pack installs or upgrades the stated list of connectors.

## Playbook Collection

|03 - Enrich (FortiSIEM)|
|:----------------------|

| Playbook Name                             | Description                                                           |
|:------------------------------------------|:----------------------------------------------------------------------|
| fortisiem-get-domain-reputation           | FortiSIEM get domain reputation on attributes in an event or incident |
| fortisiem-get-hash-reputation             | FortiSIEM get hash reputation on attributes in an event or incident   |
| fortisiem-get-ip-reputation               | FortiSIEM get IP reputation on attributes in an event or incident     |
| fortisiem-get-url-reputation              | FortiSIEM get URL reputation on attributes in an event or incident    |
| fortisiem-reference-get-domain-reputation | Get Reputation of Domain Nested Playbook                              |
| fortisiem-reference-get-hash-reputation   | Get Hash Reputation Nested Playbook                                   |
| fortisiem-reference-get-url-rep           | Get Reputation of URL nested playbook                                 |
| fortisiem-reference-validate-ip           | FortiSIEM Validate IP address is valid nested playbook                |
| fortisiem-reference-virustotal-reputation | Get virus total reputation nested playbook                            |

>**Warning:** It is recommended to clone these Playbooks before any customizations to avoid loss of information while upgrading the Solution Pack.
