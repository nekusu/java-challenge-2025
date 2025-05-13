# Code analysis
## java-challenge-2025-users-service 
#### Branch main
#### Version 0.0.1-SNAPSHOT 

**By: default**

*Date: 2025-05-13*

*Analyzed the: 2025-05-13*

## Introduction
This document contains results of the code analysis of java-challenge-2025-users-service

Demo project for Spring Boot

## Configuration

- Quality Profiles
    - Names: Sonar way [Java]; Sonar way [XML]; 
    - Files: a1522d43-0afa-47bd-a6eb-feb7686389c0.json; 813475bc-f60b-46be-9cc9-0d264e1c6d79.json; 


 - Quality Gate
    - Name: Sonar way
    - File: Sonar way.xml

## Synthesis

### Analysis Status

Reliability | Security | Security Review | Maintainability |
:---:|:---:|:---:|:---:
A | A | E | A |

### Quality gate status

| Quality Gate Status | OK |
|-|-|

Metric|Value
---|---
Duplicated Lines (%) on New Code|OK
New Issues|OK


### Metrics

Coverage | Duplications | Comment density | Median number of lines of code per file | Adherence to coding standard |
:---:|:---:|:---:|:---:|:---:
92.7 % | 0.0 % | 0.1 % | 34.5 | 100.0 %

### Tests

Total | Success Rate | Skipped | Errors | Failures |
:---:|:---:|:---:|:---:|:---:
13 | 100.0 % | 0 | 0 | 0

### Detailed technical debt

Reliability|Security|Maintainability|Total
---|---|---|---
-|-|-|-


### Metrics Range

\ | Cyclomatic Complexity | Cognitive Complexity | Lines of code per file | Coverage | Comment density (%) | Duplication (%)
:---|:---:|:---:|:---:|:---:|:---:|:---:
Min | 0.0 | 0.0 | 5.0 | 87.5 | 0.0 | 0.0
Max | 66.0 | 10.0 | 600.0 | 100.0 | 0.6 | 0.0

### Volume

Language|Number
---|---
Java|600
XML|175
Total|775


## Issues

### Issues count by severity and types

Type / Severity|INFO|MINOR|MAJOR|CRITICAL|BLOCKER
---|---|---|---|---|---
BUG|0|0|0|0|0
VULNERABILITY|0|0|0|0|0
CODE_SMELL|0|0|0|0|0


### Issues List



## Security Hotspots

### Security hotspots count by category and priority

Category / Priority|LOW|MEDIUM|HIGH
---|---|---|---
LDAP Injection|0|0|0
Object Injection|0|0|0
Server-Side Request Forgery (SSRF)|0|0|0
XML External Entity (XXE)|0|0|0
Insecure Configuration|0|0|0
XPath Injection|0|0|0
Authentication|0|0|0
Weak Cryptography|0|0|0
Denial of Service (DoS)|0|0|0
Log Injection|0|0|0
Cross-Site Request Forgery (CSRF)|0|0|1
Open Redirect|0|0|0
Permission|0|0|0
SQL Injection|0|0|0
Encryption of Sensitive Data|0|0|0
Traceability|0|0|0
Buffer Overflow|0|0|0
File Manipulation|0|0|0
Code Injection (RCE)|0|0|0
Cross-Site Scripting (XSS)|0|0|0
Command Injection|0|0|0
Path Traversal Injection|0|0|0
HTTP Response Splitting|0|0|0
Others|0|0|0


### Security hotspots

Category|Name|Priority|Severity|Count
---|---|---|---|---
Cross-Site Request Forgery (CSRF)|Disabling CSRF protections is security-sensitive|HIGH|CRITICAL|1

