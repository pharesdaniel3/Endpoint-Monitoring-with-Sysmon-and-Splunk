# SOC Endpoint Monitoring Lab (Sysmon + Splunk)

## Overview

This project demonstrates the implementation of an endpoint monitoring solution using Sysmon and Splunk SIEM for security event collection, analysis, and detection.

The lab was built to simulate the workflow of a Security Operations Center (SOC) by collecting endpoint telemetry, forwarding logs to Splunk, and performing threat detection based on observed activities.

## Objectives

* Configure Sysmon for endpoint telemetry collection.
* Forward logs using Splunk Universal Forwarder.
* Analyze events in Splunk SIEM.
* Detect suspicious behaviors through custom searches and alerts.
* Gain hands-on SOC investigation experience.

## Technologies Used

* Sysmon
* Splunk Enterprise
* Splunk Universal Forwarder
* Windows Server
* PowerShell

## Monitored Events

* Process Creation (Event ID 1)
* Registry Modification (Event ID 13)
* DNS Queries (Event ID 22)

## Detection Scenarios

### Encoded PowerShell Detection

Simulated suspicious PowerShell execution using encoded commands and detected the activity in Splunk.

### Process Monitoring

Analyzed process execution details including:

* Process name
* Command line
* Parent process
* User context

### DNS Monitoring

Monitored DNS query activities to improve endpoint visibility.

## Alerting

Created Splunk alerts to detect suspicious PowerShell behavior and demonstrate proactive threat detection.

## Skills Gained

* Sysmon configuration
* Splunk log analysis
* Process creation monitoring
* Detection development
* SOC investigation fundamentals

## Future Improvements

* MITRE ATT&CK mapping
* Additional detection rules
* Advanced dashboards
* Threat hunting scenarios

## Conclusion

This project demonstrates foundational SOC analyst skills in endpoint monitoring, SIEM integration, and security event analysis.
