| [Home](https://github.com/fortinet-fortisoar/solution-pack-fortisiem-essentials/blob/develop/README.md) | 
|--------------------------------------------|

# Usage

FortiSIEM (v6.4.0 onwards) helps execute FortiSOAR playbooks and connectors from the **Incidents** page for individual incidents or the **Analytics** page for individual events.

FortiSIEM executes a playbook that provides the entire set of incident or raw event data as an argument to the playbook in JSON format. The playbook operates on that data, executes some actions, and returns the result to FortiSIEM.

FortiSIEM provides several sample FortiSOAR playbooks that are compatible with FortiSIEM and serving following functions:

- Getting IP address reputation via VirusTotal
- Getting Domain reputation via VirusTotal, Anomali, FortiGuard, MX Toolbox, URLVoid, and Alienvault OTX
- Getting URL reputation via VirusTotal, Anomali, FortiGuard, MX Toolbox, and URLVoid
- Getting file hash reputation via VirusTotal
