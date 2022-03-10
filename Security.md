


## Threats

https://www.enisa.europa.eu/publications/enisa-threat-landscape-2021

Attacks https://mitre-attack.github.io/attack-navigator/


## SDLC Assets and Threat Taxonomy and good practices https://www.enisa.europa.eu/publications/good-practices-for-security-of-iot-1/at_download/fullReport


## Reduce vulnerabilities 


Common Weakness Enumeration (CWE) is a category system for software weaknesses and vulnerabilities.

https://cwe.mitre.org/


The SANS Top 25 Most Dangerous Software Errors

https://www.sans.org/top25-software-errors/


## Common Vulnerabilities and Exposures (CVE) 

cve-NUMBER reference for publicly known security vulnerabilities classified by risk score 0-10. with 10 being the most severe.

https://nvd.nist.gov/
https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator


Vulnerabilities without cve:s

Not all known software security issues covered, mainly companies and large organizations that request a cve:s.









# Group the rules to CWE


CWE-311 - Missing Encryption of Sensitive Data https://cwe.mitre.org/data/definitions/311

CWE-326 - Inadequate Encryption Strength https://cwe.mitre.org/data/definitions/326

CWE-732 - Incorrect Permission Assignment for Critical Resource https://cwe.mitre.org/data/definitions/732

CWE-257 - Storing Passwords in a Recoverable Format https://cwe.mitre.org/data/definitions/257

CWE-778 - Insufficient Logging https://cwe.mitre.org/data/definitions/778

CWE-272 - Least Privilege Violation https://cwe.mitre.org/data/definitions/272

CWE-286 - Incorrect User Management https://cwe.mitre.org/data/definitions/286

CWE-770 - Allocation of Resources Without Limits or Throttling https://cwe.mitre.org/data/definitions/770

CWE-779 - Logging of Excessive Data https://cwe.mitre.org/data/definitions/779.html

CWE-200 - Exposure of Sensitive Information to an Unauthorized Actor https://cwe.mitre.org/data/definitions/200.htm 


Tracking bugs: Vulnerabilities without cve:s

Not all security issues covered, mainly companies and large organizations

So important to patch often.





# Group the rules to NIST 800-53

https://csrc.nist.gov/Projects/risk-management/sp800-53-controls/release-search#/controls?version=5.1


800-53-AC-4 AC-4 INFORMATION FLOW ENFORCEMENT https://csrc.nist.gov/Projects/risk-management/sp800-53-controls/release-search#/control?version=5.1&number=AC-4

800-53-AC-6 AC-6 LEAST PRIVILEGE https://csrc.nist.gov/Projects/risk-management/sp800-53-controls/release-search#/control?version=5.1&number=AC-6

800-53-AU-12 AU-12 AUDIT GENERATION https://csrc.nist.gov/Projects/risk-management/sp800-53-controls/release-search#/control?version=5.1&number=AU-12

800-53-IA-5 IA-5 AUTHENTICATOR MANAGEMENT https://csrc.nist.gov/Projects/risk-management/sp800-53-controls/release-search#/control?version=5.1&number=IA-5

800-53-SC-5 SC-5 DENIAL OF SERVICE PROTECTION https://csrc.nist.gov/Projects/risk-management/sp800-53-controls/release-search#/control?version=5.1&number=SC-5

800-53-SC-7 SC-7 BOUNDARY PROTECTION https://csrc.nist.gov/Projects/risk-management/sp800-53-controls/release-search#/control?version=5.1&number=SC-7

800-53-SC-8 SC-8 TRANSMISSION CONFIDENTIALITY AND INTEGRITY https://csrc.nist.gov/Projects/risk-management/sp800-53-controls/release-search#/control?version=5.1&number=SC-8

800-53-SC-12 SC-12 CRYPTOGRAPHIC KEY ESTABLISHMENT AND MANAGEMENT https://csrc.nist.gov/Projects/risk-management/sp800-53-controls/release-search#/control?version=5.1&number=SC-12

800-53-SC-13 SC-13 CRYPTOGRAPHIC PROTECTION https://csrc.nist.gov/Projects/risk-management/sp800-53-controls/release-search#/control?version=5.1&number=SC-13

800-53-CP-9 CP-9 INFORMATION SYSTEM BACKUP https://csrc.nist.gov/Projects/risk-management/sp800-53-controls/release-search#/control?version=5.1&number=CP-9

800-53-RA-5 RA-5 VULNERABILITY SCANNING https://csrc.nist.gov/Projects/risk-management/sp800-53-controls/release-search#/control?version=5.1&number=RA-5

800-53-AU-11 AU-11 AUDIT RECORD RETENTION https://csrc.nist.gov/Projects/risk-management/sp800-53-controls/release-search#/control?version=5.1&number=AU-11


# Group the rules to ISO 270001

https://www.isms.online/iso-27001/annex-a-9-access-control/

A.9 Access Control A.9.2 User Access Management

A.9 Access Control A.9.3 User Responsibilities

A.9 Access Control A.9.4 System and Application

https://www.isms.online/iso-27001/annex-a-10-cryptography/

A.10 Cryptography A.10.1 Cryptographic Controls

https://www.isms.online/iso-27001/annex-a-12-operations-security/

A.12 Operations Security A.12.3 Information Backup

A.12 Operations Security A.12.4 Logging and Monitoring

A.12 Operations Security A.12.6 Technical Vulnerability Management

https://www.isms.online/iso-27001/annex-a-13-communications-security/

A.13 Communications Security A.13.1 Network Security Management

https://www.isms.online/iso-27001/annex-a-14-system-acquisition-development-and-maintenance/

A.14 System acquisition, dev & maintenance A.14.2 Security in Dev & Support

https://www.isms.online/iso-27001/annex-a-18-compliance/

A.18 Compliance A.18.1 Compliance with Legal and Regulatory Reqs




# Open source license compliance checks

## Problem

Software Component Verification Standard (SCVS) <https://owasp.org/scvs>
<https://github.com/OWASP/Software-Component-Verification-Standard/releases/download/1.0/OWASP_SCVS-1.0-en.pdf>
  * V1: Inventory
  * V2: Software Bill of Materials (SBOM)
  * V3: Build Environment
  * V4: Package Management
  * V5: Component Analysis
  * V6: Pedigree and Provenance


## Standards
The Industry Standard for Open Source Compliance
<https://www.openchainproject.org/> <https://wiki.linuxfoundation.org/_media/openchain/openchainspec-2.0.pdf>
<https://github.com/OpenChain-Project/curriculum/raw/master/slides/openchain-curriculum-for-2-0.pdf>


## Dataformat
CycloneDX is a lightweight software bill-of-material (SBOM) specification designed for use in application security contexts and supply chain component analysis.
<https://cyclonedx.org/>

The Software Package Data Exchange (SPDX)
<https://spdx.dev/specifications/>

