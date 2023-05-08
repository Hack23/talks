# Talks by Hack23

This repository contains resources and talks by James Pether Sörling, an experienced technology professional, open source contributor, and founder of [Hack23](https://www.hack23.com/). The talks focus on securing your development pipeline with static application security testing (SAST), dynamic application security testing (DAST), and software composition analysis (SCA) using SonarQube.

## Contents

- [Secure Development Pipeline Talk](#secure-development-pipeline-talk)
- [License Tools for Java Projects](#license-tools-for-java-projects)
- [Security Testing Tools](#security-testing-tools)
- [Examples](#examples)

## Secure Development Pipeline Talk

James Pether Sörling presented this talk at Javaforum Göteborg, where he discussed how to secure your development pipeline with static and dynamic application security tests, as well as software composition analysis using SonarQube. You can watch the video [here](https://www.youtube.com/watch?v=A_hq2Y03d6I).

James was also a guest on the "Shift Left Like A Boss" security podcast, which is available [here](https://www.youtube.com/watch?v=aYwSd1Wu28Q&ab_channel=Soluble/).

Presentation slides are available in [PowerPoint](https://github.com/Hack23/talks/raw/master/SecureDevelopmentPipeline20190919.pptx) and [OpenDocument](https://github.com/Hack23/talks/raw/master/SecureDevelopmentPipeline20190919.odp) formats.

## License Tools for Java Projects

A list of license tools for Java projects can be found [here](https://github.com/Hack23/talks/blob/master/LicenseComplianceAlternatives.md).

## Security Testing Tools

- For security testing of AWS CloudFormation templates, you can use [cfn_nag](https://github.com/stelligent/cfn_nag) and the [SonarQube CloudFormation plugin](https://github.com/Hack23/sonar-cloudformation-plugin).
- For security testing of Docker containers, you can use [Trivy](https://github.com/aquasecurity/trivy) and the [Container Check Sonar plugin](https://github.com/ministryofjustice/container-check-sonar-plugin).

## Examples

The latest Jenkinsfile example can be found in the [Hack23 CIA repository](https://github.com/Hack23/cia/blob/master/Jenkinsfile).

## About James Pether Sörling

James Pether Sörling is an experienced technology professional with expertise in information security and delivery of secure cloud systems. He is a strong advocate for transparency in organizations and is committed to ensuring the security and reliability of his open source projects through the use of industry best practices such as OpenSSF and CII Best Practices.

You can learn more about James Pether Sörling and his work through the following resources:

- [Hack23](https://www.hack23.com/)
- [OpenHub profile](https://www.openhub.net/accounts/pethers)
- [Talks on GitHub](https://github.com/Hack23/talks)
- [LinkedIn profile](https://www.linkedin.com/in/james-pether-s%C3%B6rling-1425a01a1/)

James has also been featured in various press coverage:

- [Computer Sweden](https://computersweden.idg.se/2.2683/1.689115/teknik-avslojar-politiker)
- [Riksdag och Departement](https://www.rid.se/nyheter/2018/06/cia-granskar-riksdagen/)
- [Expressen](https://www.expressen.se/debatt/sa-kan-vi-stoppa-politikernas-utanforskap/)
- [National Democratic Institute: Strengthening Parliamentary Accountability, Citizen Engagement and Access to Information](https://www.ndi.org/sites/default/files/Strengthening-Parliamentary-Accountability-Citizen-Engagement-and-Access-to-Information-A-Global-Survey-of-the-Performance-of-Parliamentary-Monitoring-Organizations-English.pdf)

Some of his past and current projects include:

- [Citizen Intelligence Agency](https://www.hack23.com/citizen-intelligence-agency/) - A volunteer-driven, open-source intelligence (OSINT) project that provides a neutral and comprehensive dashboard focusing on political activity in Sweden. By monitoring key political figures and institutions, the platform offers valuable insights into financial performance, risk metrics, and political trends. Additionally, the dashboard features a ranking system, enabling users to objectively compare politicians based on performance.
- [Sonar-CloudFormation-Plugin](https://github.com/Hack23/sonar-cloudformation-plugin) - A plugin for SonarQube that allows users to analyze CloudFormation templates written in YAML or JSON, developed in Java. The plugin uses the SonarQube API to perform code analysis on the templates and generate detailed reports on best practices, potential security issues, and other code quality metrics. The plugin integrates with cfn-nag and Checkov to provide additional security checks based on the CWE, NIST 800-53, and ISO 27001 standards.
- [Lambda in Private VPC](https://github.com/Hack23/lambda-private-vpc) - A proof-of-concept (POC) showcasing a multi-region active/active site leveraging Resilience Hub policy compliance and runbooks to facilitate rapid recovery from failures.
