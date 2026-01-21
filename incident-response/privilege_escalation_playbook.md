# Privilege Escalation Incident Response Playbook

## Incident Type
Abnormal Privilege Escalation (sudo abuse)

## Detection Method
Behavior-based detection using time-window and threshold logic in Splunk.

## Severity Levels
- Medium: Single burst of abnormal sudo activity
- High: Repeated bursts across multiple time windows

## Investigation Steps
1. Validate detection results in Splunk
2. Review sudo command frequency
3. Inspect executed commands
4. Identify affected host and user context
5. Check for repeated suspicious behavior

## Response Actions
- Recommend credential review or password reset
- Monitor host for continued activity
- Escalate to higher tier if behavior persists

## MITRE ATT&CK Mapping
- T1548 – Abuse Elevation Control Mechanism
- T1110 – Brute Force

