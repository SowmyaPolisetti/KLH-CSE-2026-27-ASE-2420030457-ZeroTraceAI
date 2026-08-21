# AI-Based DevSecOps Secret Exposure Detection and Intelligent Security Risk Prioritization System

## Project Title

**AI-Based DevSecOps Secret Exposure Detection and Intelligent Security Risk Prioritization System**

## Team Members

| S. No. | Name         | Roll Number |
| ------ | ------------ | ----------- |
| 1      | D. Likitha   | 2420030295  |
| 2      | K. Dhishitha | 2420030314  |
| 3      | P. Sowmya    | 2420030457  |
| 4      | A. Aasritha  | 2420090127  |

## Supervisor

**Guide:** Bhavya Varma K

## Abstract

The **AI-Based DevSecOps Secret Exposure Detection and Intelligent Security Risk Prioritization System** is designed to automatically detect sensitive information such as API keys, passwords, access tokens, database credentials, and cloud secrets exposed in source code and configuration files.

The system combines **pattern-based detection, entropy analysis, and AI/ML-based classification** to identify potential secrets while reducing false positives. Detected vulnerabilities are analyzed based on their type, exposure, severity, and potential impact.

An intelligent risk-prioritization module assigns risk scores and categorizes vulnerabilities based on urgency, helping developers address critical security issues first.

The system can be integrated with **Git/GitHub, CI/CD pipelines, and cloud development environments** to perform automated security checks during development. It also generates security reports containing detected secrets, risk levels, affected files, and remediation recommendations.

## Objectives

* Detect exposed secrets in source code and configuration files.
* Reduce false positives using AI/ML-based classification.
* Analyze the severity and potential impact of detected vulnerabilities.
* Assign risk scores and prioritize critical security issues.
* Integrate security checks into DevSecOps workflows.
* Generate security reports and remediation recommendations.

## Technologies and Methods

* Pattern-Based Detection
* Entropy Analysis
* AI/ML-Based Classification
* Git / GitHub
* CI/CD Pipelines
* Cloud Development Environments

## Project Architecture

```text
              Source Code
                   │
                   ▼
          ┌─────────────────┐
          │ Secret Detection│
          │ Pattern +       │
          │ Entropy Analysis│
          └────────┬────────┘
                   │
                   ▼
          ┌─────────────────┐
          │  AI/ML Analysis │
          │  Classification │
          └────────┬────────┘
                   │
                   ▼
          ┌─────────────────┐
          │ Risk Prioritizer│
          │   Risk Score    │
          └────────┬────────┘
                   │
                   ▼
          Security Report
```

## System Workflow

1. **Code Scanning:** Source code and configuration files are scanned.
2. **Secret Detection:** Potential secrets are identified using patterns and entropy analysis.
3. **AI/ML Analysis:** Detected candidates are classified to reduce false positives.
4. **Risk Assessment:** Vulnerabilities are analyzed and assigned risk scores.
5. **Prioritization:** Critical vulnerabilities are prioritized for remediation.
6. **Reporting:** Security findings and recommendations are generated.

## Key Features

* Automated secret detection
* AI/ML-based classification
* Risk scoring and prioritization
* False-positive reduction
* Git/GitHub and CI/CD integration
* Security reports
* Remediation recommendations

## Expected Outcome

The system aims to detect exposed secrets early in the software development lifecycle, reduce secret leakage, improve vulnerability remediation, and strengthen secure development practices.

## Current Phase Status

**Current Phase:** Project Abstract / Initial Project Development

**Status:** Project concept, security detection approach, risk prioritization, DevSecOps integration, and reporting workflow defined.

## Academic Information

**Course:** Adaptive Software Engineering (ASE)

**Course Code:** 24CI3201

**Academic Year:** 2026–2027

**Guide:** Bhavya Varma K
