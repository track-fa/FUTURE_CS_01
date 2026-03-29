# FUTURE_CS_01 — Vulnerability Assessment Report

![Track](https://img.shields.io/badge/Track-Cyber%20Security-blue)
![Task](https://img.shields.io/badge/Task-01-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)

## Overview
Passive vulnerability assessment conducted on the Altoro Mutual 
demo banking application (demo.testfire.net) using non-intrusive 
read-only techniques.

## Analyst
- **Name:** Wafa Chaibai
- **Track:** Cyber Security (CS)
- **Task:** 01 — Vulnerability Assessment

## Target
| Field | Value |
|-------|-------|
| Application | Altoro Mutual Demo Bank |
| URL | http://demo.testfire.net |
| IP | 65.61.137.117 |
| Assessment Type | Passive / Read-Only |

## Findings Summary
| ID | Finding | Severity |
|----|---------|----------|
| F-01 | Missing HTTP Security Headers | Medium |
| F-02 | Server Information Disclosure | Low |
| F-03 | Missing Anti-CSRF Protections | Medium |
| F-04 | Cookie Missing SameSite Attribute | Medium |
| F-05 | Additional Service Exposure (Port 8080) | Medium |
| F-06 | HTTP Access Without Enforcement | Low |

## Tools Used
- Nmap — port and service scanning
- OWASP ZAP — passive scan mode
- Browser DevTools — header inspection

## Methodology
OWASP Testing Guide — 4-phase passive approach

## Report
📄 [View Full PDF Report](./Altoro_Vulnerability_Assessment_Task1_2026.pdf)

> No exploitation or harmful testing was performed.
