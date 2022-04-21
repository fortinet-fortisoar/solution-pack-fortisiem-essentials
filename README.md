# FortiSIEM Essentials Solution Pack

## Release Information

- Solution Pack Version: 1.0.0
- FortiSOAR™ Version Tested on: 7.2.0
- Authored By: Fortinet
- Certified: Yes

## Overview

### Introduction

*FortiSIEM Essentials Solution Pack* is designed to provide a set of enrichment playbooks. These playbooks contains the essential contents to make the FortiSIEM integration in FortiSOAR more seamless and comprehensive. Through enhancements in the FortiSOAR modules to suit the FortiSIEM ingestion better and by providing you with helpful use case playbooks, the solution pack aims to enhance the utility and experience of the integration. Once installed, you will also start seeing the installed playbooks in FortiSIEM's native UI (v6.4.0+).

### Usage

FortiSIEM (v6.4.0 onwards) provides the capability to adhoc execute FortiSOAR Playbooks and Connectors from the "INCIDENTS" page for individual incidents, or from the "ANALYTICS" page for individual events.

FortiSIEM executes a Playbook, it provides the entire set of incident or raw event data , depending on execution from the "INCIDENTS" or "ANALYTICS" page respectively, as an argument to the Playbook in JSON format. The Playbook operates on that data, execute some actions, and returns the result to FortiSIEM.

FortiSIEM provides a number of sample FortiSOAR playbooks that are compatible with FortiSIEM.

- Playbook for getting IP address reputation via VirusTotal
- Playbook for getting Domain reputation via VirusTotal, Anomali, FortiGuard, MX Toolbox, URLVoid, Alienvault OTX
- Playbook for getting URL reputation via VirusTotal, Anomali, FortiGuard, MX Toolbox, URLVoid
- Playbook for getting file hash reputation via VirusTotal

## Prerequisites

|**Solution Pack Name**|**Purpose**|**Doc Link**|
| :- | :- | :- |
|SOAR Framework 1.0.0|Require for Incident Response modules|[Click here](https://github.com/fortinet-fortisoar/solution-pack-soar-framework/blob/develop/README.md)|

## Contents

1. Connector(s)
    |**SN**|**Connector Name**|
    | :- | :- |
    |1|Anomali ThreatStream|
    |2|Fortinet Web Filter Lookup|
    |3|MxToolbox|
    |4|URLVoid|
    |5|VirusTotal|

     **Warning:** After deployment, this Solution Pack installs or upgrades the stated list of connectors.

2. Playbook Collection(s)
    - 02 - Use Case - Phishing Email Response (5):

    |**SN**|**Playbook Name**|**Description**|
    | :- | :- | :- |
    |1|fortisiem-get-domain-reputation|FortiSIEM get domain reputation on attributes in an event or incident|
    |2|fortisiem-get-hash-reputation|FortiSIEM get hash reputation on attributes in an event or incident|
    |3|fortisiem-get-ip-reputation|FortiSIEM get IP reputation on attributes in an event or incident|
    |4|fortisiem-get-url-reputation|FortiSIEM get URL reputation on attributes in an event or incident|
    |5|fortisiem-reference-get-domain-reputation|Get Reputation of Domain Nested Playbook|
    |6|fortisiem-reference-get-hash-reputation|Get Hash Reputation Nested Playbook|
    |7|fortisiem-reference-get-url-rep|Get Reputation of URL nested playbook|
    |8|fortisiem-reference-validate-ip|FortiSIEM Validate IP address is valid nested playbook|
    |9|fortisiem-reference-virustotal-reputation|Get virus total reputation nested playbook|

     **Warning:** It is recommended to clone these Playbooks before any customizations to avoid loss of information while upgrading the Solution Pack.
