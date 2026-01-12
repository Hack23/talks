<h1 align="center">
  <img src="https://hack23.com/icon-192.png" width="192" height="192" alt="Hack23 AB">
</h1>

<h1 align="center">🔐 Hack23 AB — ISMS Reference Guide for Talks & Presentations</h1>

<p align="center">
  <strong>📚 Mapping Presentation Topics to ISMS-PUBLIC Security Policies</strong><br>
  <em>Demonstrating Security Through Transparency</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Owner-James_Pether_Sörling-0A66C2?style=flat-square&logo=linkedin" alt="Owner"/>
  <img src="https://img.shields.io/badge/Version-1.0-4CAF50?style=flat-square" alt="Version"/>
  <img src="https://img.shields.io/badge/Effective-2025--01--10-FF9800?style=flat-square&logo=calendar" alt="Effective Date"/>
  <img src="https://img.shields.io/badge/Review_Cycle-Annual-2196F3?style=flat-square&logo=renewal" alt="Review Cycle"/>
</p>

<p align="center">
  📄 <strong>Document Type:</strong> Reference Guide | 
  🏢 <strong>Scope:</strong> Presentations & Technical Talks | 
  👥 <strong>Audience:</strong> Public
</p>

---

## 📋 Purpose

This reference guide provides a comprehensive mapping between the security and compliance topics discussed in Hack23's presentations and the corresponding policies in our [ISMS-PUBLIC repository](https://github.com/Hack23/ISMS-PUBLIC). This demonstrates our commitment to transparency by providing verifiable documentation for all security claims and practices discussed in public forums.

> *"At Hack23, we believe that security through transparency builds trust. Every security practice we discuss in presentations is backed by documented policies that anyone can review and verify."*
>
> — **James Pether Sörling**, CEO & Founder, Hack23 AB

---

## 🎯 How to Use This Guide

1. **For Presentation Attendees**: Find the talk you attended and explore the referenced ISMS policies to verify claims and learn more about our security practices
2. **For Security Professionals**: Use this as a template for mapping your own presentations to documented policies
3. **For Compliance Teams**: Reference this guide to understand how presentation materials align with formal security documentation

---

## 🎤 Secure Development Pipeline Talk

**Presentation:** SecureDevelopmentPipeline20190919 (PowerPoint/OpenDocument)  
**Event:** Javaforum Göteborg  
**Video:** [YouTube](https://www.youtube.com/watch?v=A_hq2Y03d6I)  
**Podcast:** [Shift Left Like A Boss](https://www.youtube.com/watch?v=aYwSd1Wu28Q&ab_channel=Soluble/)

### Topic-to-Policy Mapping

<table>
  <tr>
    <th>Presentation Topic</th>
    <th>ISMS-PUBLIC Policy</th>
    <th>Key Sections</th>
  </tr>
  <tr>
    <td>🔐 <strong>DevSecOps Integration</strong><br>Shifting security left in the development pipeline</td>
    <td><a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Secure_Development_Policy.md">Secure Development Policy</a></td>
    <td>
      • DevSecOps Principles<br>
      • Security in CI/CD Pipelines<br>
      • Automated Security Testing
    </td>
  </tr>
  <tr>
    <td>🔍 <strong>Static Application Security Testing (SAST)</strong><br>SonarQube integration and code quality gates</td>
    <td><a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Secure_Development_Policy.md">Secure Development Policy</a></td>
    <td>
      • SAST Requirements<br>
      • Code Quality Standards<br>
      • Security Metrics
    </td>
  </tr>
  <tr>
    <td>⚡ <strong>Dynamic Application Security Testing (DAST)</strong><br>OWASP ZAP and runtime vulnerability scanning</td>
    <td><a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Secure_Development_Policy.md">Secure Development Policy</a></td>
    <td>
      • DAST Requirements<br>
      • Penetration Testing<br>
      • Runtime Security Validation
    </td>
  </tr>
  <tr>
    <td>📦 <strong>Software Composition Analysis (SCA)</strong><br>Dependency vulnerability scanning and license compliance</td>
    <td>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Secure_Development_Policy.md">Secure Development Policy</a><br>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Open_Source_Policy.md">Open Source Policy</a>
    </td>
    <td>
      • SCA Requirements<br>
      • Dependency Management<br>
      • SBOM Generation<br>
      • License Compliance
    </td>
  </tr>
  <tr>
    <td>🔄 <strong>CI/CD Security Pipeline</strong><br>Automated security testing in Jenkins/GitHub Actions</td>
    <td>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Secure_Development_Policy.md">Secure Development Policy</a><br>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Change_Management_Procedure.md">Change Management Procedure</a>
    </td>
    <td>
      • Pipeline Security Controls<br>
      • Automated Testing Requirements<br>
      • Deployment Security
    </td>
  </tr>
  <tr>
    <td>🛡️ <strong>Compliance Automation</strong><br>Automated compliance validation and reporting</td>
    <td>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Information_Security_Policy.md">Information Security Policy</a><br>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Secure_Development_Policy.md">Secure Development Policy</a>
    </td>
    <td>
      • Compliance Frameworks<br>
      • Automated Evidence Collection<br>
      • Continuous Compliance
    </td>
  </tr>
  <tr>
    <td>🚨 <strong>Vulnerability Management</strong><br>CVE tracking, patching, and remediation</td>
    <td><a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Vulnerability_Management_Procedure.md">Vulnerability Management Procedure</a></td>
    <td>
      • Vulnerability Identification<br>
      • Risk Assessment<br>
      • Remediation Timelines
    </td>
  </tr>
  <tr>
    <td>☁️ <strong>CloudFormation Security</strong><br>Infrastructure as Code security scanning (cfn_nag)</td>
    <td>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Secure_Development_Policy.md">Secure Development Policy</a><br>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Cloud_Security_Policy.md">Cloud Security Policy</a>
    </td>
    <td>
      • IaC Security Requirements<br>
      • Cloud Resource Security<br>
      • Configuration Management
    </td>
  </tr>
</table>

### Reference Implementations

All practices discussed in this presentation are implemented in Hack23's open source projects:

- **🏛️ Citizen Intelligence Agency** - [CIA Jenkinsfile](https://github.com/Hack23/cia/blob/master/Jenkinsfile)
- **🔐 CIA Compliance Manager** - [GitHub Actions Workflows](https://github.com/Hack23/cia-compliance-manager/tree/main/.github/workflows)
- **🎮 Black Trigram** - [Security Architecture](https://github.com/Hack23/blacktrigram/blob/master/SECURITY_ARCHITECTURE.md)

---

## 📜 License Compliance Alternatives Documentation

**Document:** [LicenseComplianceAlternatives.md](LicenseComplianceAlternatives.md)  
**Focus:** Open source license compliance tools for Java Maven projects

### Topic-to-Policy Mapping

<table>
  <tr>
    <th>Documentation Topic</th>
    <th>ISMS-PUBLIC Policy</th>
    <th>Key Sections</th>
  </tr>
  <tr>
    <td>📋 <strong>Software Component Verification (SCVS)</strong><br>OWASP standards for component verification</td>
    <td><a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Open_Source_Policy.md">Open Source Policy</a></td>
    <td>
      • Component Inventory<br>
      • SBOM Requirements<br>
      • Supply Chain Security
    </td>
  </tr>
  <tr>
    <td>🔍 <strong>License Compliance Tools</strong><br>Maven plugins, SonarQube, FOSSA, BlackDuck</td>
    <td>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Open_Source_Policy.md">Open Source Policy</a><br>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Secure_Development_Policy.md">Secure Development Policy</a>
    </td>
    <td>
      • License Scanning Requirements<br>
      • Approved License List<br>
      • Tool Requirements
    </td>
  </tr>
  <tr>
    <td>📦 <strong>SBOM Generation</strong><br>CycloneDX and SPDX formats</td>
    <td><a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Open_Source_Policy.md">Open Source Policy</a></td>
    <td>
      • SBOM Standards<br>
      • Distribution Requirements<br>
      • Update Frequency
    </td>
  </tr>
  <tr>
    <td>🤝 <strong>OpenChain Compliance</strong><br>Industry standard for open source compliance</td>
    <td>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Open_Source_Policy.md">Open Source Policy</a><br>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Third_Party_Management.md">Third Party Management</a>
    </td>
    <td>
      • Compliance Framework<br>
      • Process Requirements<br>
      • Training & Awareness
    </td>
  </tr>
  <tr>
    <td>⚖️ <strong>License Compatibility</strong><br>Managing conflicting licenses and dependencies</td>
    <td><a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Open_Source_Policy.md">Open Source Policy</a></td>
    <td>
      • License Compatibility Matrix<br>
      • Conflict Resolution<br>
      • Approval Workflow
    </td>
  </tr>
</table>

---

## 🛡️ Security Resources Documentation

**Document:** [Security.md](Security.md)  
**Focus:** Threat modeling, vulnerability management, and compliance frameworks

### Topic-to-Policy Mapping

<table>
  <tr>
    <th>Documentation Topic</th>
    <th>ISMS-PUBLIC Policy</th>
    <th>Key Sections</th>
  </tr>
  <tr>
    <td>🚨 <strong>Threat Intelligence</strong><br>ENISA threat landscape and MITRE ATT&CK</td>
    <td>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Information_Security_Policy.md">Information Security Policy</a><br>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Incident_Response_Plan.md">Incident Response Plan</a>
    </td>
    <td>
      • Threat Monitoring<br>
      • Threat Intelligence Sources<br>
      • Risk Assessment
    </td>
  </tr>
  <tr>
    <td>⚠️ <strong>Common Weaknesses (CWE)</strong><br>MITRE CWE and SANS Top 25 vulnerabilities</td>
    <td>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Secure_Development_Policy.md">Secure Development Policy</a><br>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Vulnerability_Management_Procedure.md">Vulnerability Management Procedure</a>
    </td>
    <td>
      • Secure Coding Standards<br>
      • Common Weakness Prevention<br>
      • Code Review Requirements
    </td>
  </tr>
  <tr>
    <td>🔍 <strong>CVE Management</strong><br>NVD vulnerability tracking and CVSS scoring</td>
    <td><a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Vulnerability_Management_Procedure.md">Vulnerability Management Procedure</a></td>
    <td>
      • CVE Tracking Process<br>
      • Risk Scoring (CVSS)<br>
      • Remediation Timelines
    </td>
  </tr>
  <tr>
    <td>📊 <strong>NIST 800-53 Controls</strong><br>Control families and implementation guidance</td>
    <td>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Information_Security_Policy.md">Information Security Policy</a><br>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Access_Control_Policy.md">Access Control Policy</a><br>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Network_Security_Policy.md">Network Security Policy</a>
    </td>
    <td>
      • Control Implementation<br>
      • Compliance Mapping<br>
      • Continuous Monitoring
    </td>
  </tr>
  <tr>
    <td>🔐 <strong>ISO 27001 Compliance</strong><br>Annex A controls and implementation</td>
    <td>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Information_Security_Policy.md">Information Security Policy</a><br>
      All ISMS-PUBLIC Policies
    </td>
    <td>
      • ISO 27001:2022 Alignment<br>
      • Annex A Control Mapping<br>
      • ISMS Documentation
    </td>
  </tr>
</table>

---

## 🔗 Related ISMS Documents

For comprehensive security documentation, explore the complete ISMS-PUBLIC repository:

<table>
  <tr>
    <th>Category</th>
    <th>Documents</th>
  </tr>
  <tr>
    <td>🔐 <strong>Core Policies</strong></td>
    <td>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Information_Security_Policy.md">Information Security Policy</a><br>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Acceptable_Use_Policy.md">Acceptable Use Policy</a><br>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Data_Classification_Framework.md">Data Classification Framework</a>
    </td>
  </tr>
  <tr>
    <td>🛠️ <strong>Development & Operations</strong></td>
    <td>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Secure_Development_Policy.md">Secure Development Policy</a><br>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Open_Source_Policy.md">Open Source Policy</a><br>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Change_Management_Procedure.md">Change Management Procedure</a><br>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Vulnerability_Management_Procedure.md">Vulnerability Management Procedure</a>
    </td>
  </tr>
  <tr>
    <td>🔑 <strong>Access & Identity</strong></td>
    <td>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Access_Control_Policy.md">Access Control Policy</a><br>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Password_Policy.md">Password Policy</a><br>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/MFA_Policy.md">Multi-Factor Authentication Policy</a>
    </td>
  </tr>
  <tr>
    <td>☁️ <strong>Cloud & Infrastructure</strong></td>
    <td>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Cloud_Security_Policy.md">Cloud Security Policy</a><br>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Network_Security_Policy.md">Network Security Policy</a><br>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Backup_and_Recovery_Policy.md">Backup and Recovery Policy</a>
    </td>
  </tr>
  <tr>
    <td>🚨 <strong>Incident & Business Continuity</strong></td>
    <td>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Incident_Response_Plan.md">Incident Response Plan</a><br>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Business_Continuity_Plan.md">Business Continuity Plan</a><br>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Disaster_Recovery_Plan.md">Disaster Recovery Plan</a>
    </td>
  </tr>
  <tr>
    <td>🤝 <strong>Third-Party & Compliance</strong></td>
    <td>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Third_Party_Management.md">Third Party Management</a><br>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Data_Protection_Policy.md">Data Protection Policy (GDPR)</a><br>
      <a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Privacy_Policy.md">Privacy Policy</a>
    </td>
  </tr>
</table>

---

## 🎯 Transparency Benefits

By mapping presentation topics to documented ISMS policies, Hack23 demonstrates:

<table>
  <tr>
    <th>Benefit</th>
    <th>Description</th>
    <th>Stakeholder Value</th>
  </tr>
  <tr>
    <td>✅ <strong>Verifiable Claims</strong></td>
    <td>All security practices discussed are backed by documented policies</td>
    <td>Attendees can independently verify our security approach</td>
  </tr>
  <tr>
    <td>🏆 <strong>Competitive Advantage</strong></td>
    <td>Public ISMS demonstrates security maturity</td>
    <td>Differentiation in client proposals and procurement</td>
  </tr>
  <tr>
    <td>🤝 <strong>Trust Building</strong></td>
    <td>Transparency reduces information asymmetry</td>
    <td>Enhanced credibility with clients and partners</td>
  </tr>
  <tr>
    <td>📚 <strong>Educational Value</strong></td>
    <td>Others can learn from our documented approach</td>
    <td>Community contribution and thought leadership</td>
  </tr>
  <tr>
    <td>⚡ <strong>Audit Readiness</strong></td>
    <td>Pre-documented policies accelerate audits</td>
    <td>Reduced audit preparation time and cost</td>
  </tr>
  <tr>
    <td>🔄 <strong>Continuous Improvement</strong></td>
    <td>Public accountability drives policy refinement</td>
    <td>Higher quality security program</td>
  </tr>
</table>

---

## 📞 Questions About Our ISMS?

If you have questions about our security policies or ISMS implementation:

- **Repository:** [github.com/Hack23/ISMS-PUBLIC](https://github.com/Hack23/ISMS-PUBLIC)
- **Issues/Discussions:** Use GitHub Issues for questions or clarifications
- **LinkedIn:** Connect with [James Pether Sörling](https://www.linkedin.com/in/jamessorling/)
- **Website:** [hack23.com](https://hack23.com)

---

## 📝 Document Control

<table>
  <tr>
    <td><strong>Approved By</strong></td>
    <td>James Pether Sörling, CEO, Hack23 AB</td>
  </tr>
  <tr>
    <td><strong>Distribution</strong></td>
    <td>Public - Conference Attendees, Clients, Partners, Security Community</td>
  </tr>
  <tr>
    <td><strong>Classification</strong></td>
    <td><a href="https://github.com/Hack23/ISMS-PUBLIC/blob/main/Data_Classification_Framework.md"><img src="https://img.shields.io/badge/Classification-PUBLIC-9E9E9E?style=flat-square" alt="Public"></a></td>
  </tr>
  <tr>
    <td><strong>Effective Date</strong></td>
    <td>2025-01-10 (UTC)</td>
  </tr>
  <tr>
    <td><strong>Next Review</strong></td>
    <td>2026-01-10 (Annual Review)</td>
  </tr>
</table>

### Framework Compliance

<div align="center">
  <img src="https://img.shields.io/badge/ISO_27001:2022-Compliant-4CAF50?style=flat-square" alt="ISO 27001:2022"/>
  <img src="https://img.shields.io/badge/NIST_CSF_2.0-Aligned-2196F3?style=flat-square" alt="NIST CSF 2.0"/>
  <img src="https://img.shields.io/badge/CIS_Controls_v8.1-Implemented-FF9800?style=flat-square" alt="CIS Controls v8.1"/>
  <img src="https://img.shields.io/badge/OpenChain_2.1-Compliant-00BCD4?style=flat-square" alt="OpenChain 2.1"/>
</div>

---

<div align="center">
  <p><strong>Security Through Transparency</strong></p>
  <p>Hack23 AB | Org.nr 559534-7807 | Sweden</p>
  <p><a href="https://github.com/Hack23/ISMS-PUBLIC">View Complete ISMS-PUBLIC Repository</a></p>
</div>
