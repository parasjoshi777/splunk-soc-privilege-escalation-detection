# Splunk SIEM – Privilege Escalation Detection (SOC Project)

## Overview
This project demonstrates an enterprise-style SOC detection built using Splunk SIEM.
The focus is on detecting abnormal privilege escalation behavior on macOS systems
using behavior-based analysis of sudo activity.

## Key Features
- Log ingestion and normalization in Splunk
- Behavior-based detection (no keyword dependency)
- Time-window and threshold-based correlation
- False-positive reduction using baselining
- Severity classification and risk scoring
- SOC dashboard visualization
- Incident response playbook
- MITRE ATT&CK mapping

## Detection Logic
The primary detection identifies rapid sudo attempts within a short time window,
which may indicate password guessing or unauthorized privilege escalation.

## Tools & Technologies
- Splunk Enterprise (Free)
- macOS system logs
- SPL (Search Processing Language)
- MITRE ATT&CK Framework

## MITRE ATT&CK Coverage
- T1548 – Abuse Elevation Control Mechanism
- T1110 – Brute Force

## Author
Paras Joshi
