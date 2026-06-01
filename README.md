# Analyze a Phishing Email Sample  Task 2
ElevateLabs Cybersecurity Internship

## Overview
This repository contains the deliverables for Task 2 of the ElevateLabs Cybersecurity Internship. The task involved analyzing a simulated phishing email to identify and document indicators of fraud.

## Objective
Identify phishing characteristics in a suspicious email sample and produce a report listing all indicators found.

## Tools Used
- MXToolbox Header Analyzer - SPF/DKIM/DMARC analysis
- Text Editor - examining raw email source
- URLVoid - safe URL reputation check
- Google Admin Messageheader - secondary header validation

## Key Findings
- **Typosquatted Domain:** paypa1-verify.com (digit 1 used in place of the letter l)
- **Authentication Failures:** SPF, DKIM, and DMARC verification mechanisms all failed
- **Mismatched URL:** The user-facing visible link text differed entirely from the hidden HTML href destination
- **Social Engineering Tactics:** Deceptive use of artificial urgency, fear responses, and brand authority impersonation
- **Linguistic Anomalies:** Multiple prominent grammatical and structural errors inconsistent with official enterprise communications

## Files Included
- `Phishing_Email_Analysis_Report.pdf` - The comprehensive technical forensic analysis report
- `sample_phishing_email.txt` - The raw simulated email file (headers and body) used for the investigation
- `screenshots/` - Directory containing evidentiary tool analysis outputs from MXToolbox and URLVoid
- `finding_notes.txt`

## Disclaimer
All email samples, domains, IPs, and scenarios analyzed within this project are entirely simulated, fictional, and created exclusively for educational and training purposes.
