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
- [ ] Search Engine Discovery and Reconnaissance for Information Leakage
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

-------
###### References & Footnotes
[LinkOwaspWstg]: https://owasp.org/www-project-web-security-testing-guide/latest/
