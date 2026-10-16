# MITRE ATT&CK Sigma Rules

## About

This repository contains Sigma detection rules mapped to MITRE ATT&CK techniques. The goal is to develop, document, and validate behavior-based detections for security monitoring and threat hunting.

## Objectives

- Develop Sigma rules mapped to MITRE ATT&CK techniques.
- Document detection logic, relevant log sources, and potential false positives.
- Validate rules against representative log events.
- Support SIEM-independent detection engineering.

## Repository Structure

Rules are organized by MITRE ATT&CK tactic and technique ID.

Each rule includes its detection logic, log source, severity, false-positive considerations, and relevant ATT&CK mapping.

## Scope

The Resource Development tactic is excluded from this project.

## Rule Validation

Rules are tested for Sigma syntax and evaluated against representative log data where available. Detection results may vary depending on log collection, field mapping, and SIEM configuration.

## Disclaimer

These rules are intended for defensive security monitoring, detection engineering, and educational research. A rule match is not, by itself, proof of malicious activity.
