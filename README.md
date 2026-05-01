# Week 1: OWASP Juice Shop Assessment
**DevelopersHub Cyber Security Internship - May 2026**

## Solved: 2/173 Challenges 

### SQL Injection - CRITICAL
Payload: `' OR 1=1--` | Result: Admin login bypass

### XSS - HIGH
Payload: `<svg onload=alert('XSS')>` | Result: Code injection confirmed

## Proof of Concept 
Check screenshots folder for evidence.

## Remediation
- Parameterized queries
- Output encoding + CSP
