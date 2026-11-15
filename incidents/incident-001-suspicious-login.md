# Incident Report #001

## Incident Overview

This incident involves suspicious login attempts detected on the administrator account, followed by a successful login.

## Alert Information

- **Type:** Multiple Failed Login Attempts
- **Host:** SRV-AD-01
- **User:** administrator
- **Source IP:** 192.168.1.105
- **Attempts:** 15
- **Interval:** 2 minutes
- **Severity:** High

## Evidence Collected

During the initial investigation, the following evidence was identified:

- 15 failed authentication attempts on the administrator account.
- Source IP address: 192.168.1.105.
- A successful login occurred 30 seconds after the last failed attempt.
- The account owner reported that they did not recognize the login activity.
- The source IP belongs to an internal computer.

## Initial Analysis

The activity is suspicious because multiple failed login attempts were followed by a successful login.

The account owner does not recognize the activity, indicating a possible unauthorized access.

Further investigation is required to determine whether the account was compromised.

## Risk Assessment

**Risk Level: High**

The administrator account may have been compromised, potentially exposing sensitive company information and systems.

## Recommended Actions

- Immediately escalate the incident to SOC Level 2.
- Preserve authentication logs and relevant evidence.
- Identify the source device.
- Follow the incident response playbook for containment actions.
- Investigate possible unauthorized account access.

## Escalation

**Escalation Level:** SOC Level 2.

The incident requires further investigation and potential containment actions.

## Incident Status

**Status:** Under investigation.

**Responsible Team:** SOC Level 2.