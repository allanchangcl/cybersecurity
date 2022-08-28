# Cybersecurity Framework
- Web Application Penetration Test

~~- Secure Coding Practises~~

~~- Incident Response~~

## Web Application Penetration Test

### Business Summary

To discover vulnerabilities that could result in a data breach, exploits and service interruption.

Assessment based on Open Web Application Security Project, Web Security Testing Guide - [OWASP-WTSG][LinkOwaspWstg]

The scope of the assessment covers site domain `/* put domain here */`

### Findings Overview

```
// review of findings after tests
```

###  Recommendations

```
// review of recommendations after tests
```

###  Priority Level & Severity Scale

```
// review of priorities after tests
```



### Methodology

* [Information Gathering](#Information)
* [Configuration and Deployment Management Testing](#Configuration)
* [Identity Management Testing](#Identity_Management)
* [Authentication Testing](#Authentication)
* [Authorization Testing](#Authorization)
* [Session Management Testing](#Session_Management)
* [Input Validation Testing](#Input_Validation)
* [Testing for Error Handling](#Testing_for_Error_Handling)
* [Testing for Weak Cryptography](#Testing_for_Weak_Cryptography)
* [Business Logic Testing](#Business_Logic)
* [Client-side Testing](#Client-side)
* [API Testing](#API_Testing)

-------
### <a name="Information">Information Gathering</a>
- [ ] Conduct Search Engine Discovery and Reconnaissance for Information Leakage
- [ ] Fingerprint Web Server
- [ ] Review Webserver Metafiles for Information Leakage
- [ ] Enumerate Applications on Webserver
- [ ] Review Webpage Content for Information Leakage
- [ ] Identify Application Entry Points
- [ ] Map Execution Paths Through Application
- [ ] Fingerprint Web Application Framework
- [ ] Fingerprint Web Application
- [ ] Map Application Architecture

-------
### <a name="Configuration">Configuration and Deployment Management Testing</a>
- [ ] Test Network Infrastructure Configuration
- [ ] Test Application Platform Configuration
- [ ] Test File Extensions Handling for Sensitive Information
- [ ] Review Old Backup and Unreferenced Files for Sensitive Information
- [ ] Enumerate Infrastructure and Application Admin Interfaces
- [ ] Test HTTP
- [ ] Test HTTP Strict Transport Security
- [ ] Test RIA Cross Domain Policy
- [ ] Test File Permission
- [ ] Test for Subdomain Takeover
- [ ] Test Cloud Storage
- [ ] Test for Content Security Policy

-------
### <a name="Identity_Management">Identity Management Testing</a>
- [ ] Test Role Definitions
- [ ] Test User Registration Process
- [ ] Test Account Provisioning Process
- [ ] Testing for Account Enumeration and Guessable User Account
- [ ] Testing for Weak or Unenforced Username Policy

-------
### <a name="Authentication">Authentication Testing</a>
- [ ] Testing for Credentials Transported over an Encrypted Channel
- [ ] Testing for Default Credentials
- [ ] Testing for Weak Lock Out Mechanism
- [ ] Testing for Bypassing Authentication Schema
- [ ] Testing for Vulnerable Remember Password
- [ ] Testing for Browser Cache Weaknesses
- [ ] Testing for Weak Password Policy
- [ ] Testing for Weak Security Question Answer
- [ ] Testing for Weak Password Change or Reset Functionalities
- [ ] Testing for Weaker Authentication in Alternative Channel

-------
### <a name="Authorization">Authorization Testing</a>
- [ ] Testing Directory Traversal File Include
- [ ] Testing for Bypassing Authorization Schema
- [ ] Testing for Privilege Escalation
- [ ] Testing for Insecure Direct Object References
- [ ] Testing for OAuth Weaknesses
- [ ] Testing for OAuth Authorization Server Weaknesses
- [ ] Testing for OAuth Client Weaknesses

-------
### <a name="Session_Management">Session Management Testing</a>
- [ ] Testing for Session Management Schema
- [ ] Testing for Cookies Attributes
- [ ] Testing for Session Fixation
- [ ] Testing for Exposed Session Variables
- [ ] Testing for Cross Site Request Forgery
- [ ] Testing for Logout Functionality
- [ ] Testing Session Timeout
- [ ] Testing for Session Puzzling
- [ ] Testing for Session Hijacking
- [ ] Testing JSON Web Tokens

-------
### <a name="Input_Validation">Input Validation Testing</a>
- [ ] Testing for Reflected Cross Site Scripting
- [ ] Testing for Stored Cross Site Scripting
- [ ] Testing for HTTP Verb Tampering
- [ ] Testing for HTTP Parameter Pollution
- [ ] Testing for SQL Injection
- [ ] Testing for Oracle
- [ ] Testing for MySQL
- [ ] Testing for SQL Server
- [ ] Testing PostgreSQL
- [ ] Testing for MS Access
- [ ] Testing for NoSQL Injection
- [ ] Testing for ORM Injection
- [ ] Testing for Client-side
- [ ] Testing for LDAP Injection
- [ ] Testing for XML Injection
- [ ] Testing for SSI Injection
- [ ] Testing for XPath Injection
- [ ] Testing for IMAP SMTP Injection
- [ ] Testing for Code Injection
- [ ] Testing for File Inclusion
- [ ] Testing for Command Injection
- [ ] Testing for Format String Injection
- [ ] Testing for Incubated Vulnerability
- [ ] Testing for HTTP Splitting Smuggling
- [ ] Testing for HTTP Incoming Requests
- [ ] Testing for Host Header Injection
- [ ] Testing for Server-side Template Injection
- [ ] Testing for Server-Side Request Forgery
- [ ] Testing for Mass Assignment

-------
### <a name="Testing_for_Error_Handling">Testing for Error Handling</a>
- [ ] Testing for Improper Error Handling
- [ ] Testing for Stack Traces

-------
### <a name="Testing_for_Weak_Cryptography">Testing for Weak Cryptography</a>
- [ ] Testing for Weak Transport Layer Security
- [ ] Testing for Padding Oracle
- [ ] Testing for Sensitive Information Sent via Unencrypted Channels
- [ ] Testing for Weak Encryption

-------
### <a name="Business_Logic">Business Logic Testing</a>
- [ ] Test Business Logic Data Validation
- [ ] Test Ability to Forge Requests
- [ ] Test Integrity Checks
- [ ] Test for Process Timing
- [ ] Test Number of Times a Function Can Be Used Limits
- [ ] Testing for the Circumvention of Work Flows
- [ ] Test Defenses Against Application Misuse
- [ ] Test Upload of Unexpected File Types
- [ ] Test Upload of Malicious Files
- [ ] Test Payment Functionality

-------
### <a name="Client-side">Client-side Testing</a>
- [ ] Testing for DOM-Based Cross Site Scripting
- [ ] Testing for Self DOM Based Cross Site Scripting
- [ ] Testing for JavaScript Execution
- [ ] Testing for HTML Injection
- [ ] Testing for Client-side URL Redirect
- [ ] Testing for CSS Injection
- [ ] Testing for Client-side Resource Manipulation
- [ ] Testing Cross Origin Resource Sharing
- [ ] Testing for Cross Site Flashing
- [ ] Testing for Clickjacking
- [ ] Testing WebSockets
- [ ] Testing Web Messaging
- [ ] Testing Browser Storage
- [ ] Testing for Cross Site Script Inclusion
- [ ] Testing for Reverse Tabnabbing

-------
### <a name="API_Testing">API Testing</a>
- [ ] Testing GraphQL

-------
###### References & Footnotes
[LinkOwaspWstg]: https://owasp.org/www-project-web-security-testing-guide/latest/
