# Security Alert to Remediation Workflow

This document describes a typical workflow followed when a security alert is detected.

## 1. Alert Detection
- Alert generated from SIEM (e.g., QRadar)
- User-reported incident (phishing, suspicious activity)
- Automated security monitoring tools

## 2. Initial Triage
- Review alert severity and category
- Validate if alert is a false positive
- Identify affected user, system, or asset

## 3. Investigation
- Analyze logs and related events
- Correlate data from multiple sources
- Determine scope and potential impact

## 4. Containment
- Isolate affected system or account if required
- Block malicious IPs, URLs, or email senders
- Reset compromised credentials

## 5. Remediation
- Remove malicious artifacts
- Apply patches or configuration changes
- Restore system functionality

## 6. Post-Incident Review
- Document findings and actions taken
- Identify control gaps
- Recommend improvements to prevent recurrence
