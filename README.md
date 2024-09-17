# Azure-Honeynet

## Introduction
To understand malicious attack patterns over the internet and the effectiveness of security measures, I created a honeynet and Security Operations Center (SOC) with Microsoft Azure.

The various log sources are ingested into a Log Analytics Workspace, which Microsoft Sentinel uses to build attack maps, trigger alerts, and create incidents.

I left the environment insecure for 24 hours and recorded the log data. Then I secured the environment and recorded log data for another 24 hours.

These are the metrics which were recorded:
- SecurityEvent (Windows Event Logs)
- Syslog (Linux Event Logs)
- SecurityAlert (Log Analytics Alerts Triggered)
- SecurityIncident (Incidents created by Sentinel)
- AzureNetworkAnalytics_CL (Malicious Flows allowed into our honeynet)

## Architecture Before Hardening

## Architecture After Hardening

## Attack Maps Before Hardening

## Metrics

## Conclusion
