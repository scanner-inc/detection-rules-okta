# Scanner Detection Rules - Okta System Logs

This repository contains Scanner detection rules for Okta System logs.

### Examples

Here are a few examples of the detections that are included in this repository:
- Okta MFA Reset or Deactivated
- Okta Security Threat Detected
- Okta FastPass Phishing Detection
- Okta Unauthorized Access to App

### Event Sinks

When these detection rules are triggered, alerts are sent to the [event sinks](https://docs.scanner.dev/scanner/using-scanner/detection-rules/event-sinks)
in Scanner that are associated with these keys:
- `informational_severity_alerts`
- `low_severity_alerts`
- `medium_severity_alerts`
- `high_severity_alerts`
- `critical_severity_alerts`
- `fatal_severity_alerts`

### Deployment

To deploy these rules into your Scanner instance, you can follow the
instructions in the [Scanner documentation](https://docs.scanner.dev) under
**Detection Rules as Code**. Your Scanner instance will sync with the `main`
branch of this repository, keeping your detections up-to-date.
