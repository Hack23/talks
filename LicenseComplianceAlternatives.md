# Open source license compliance check alternatives for Java Maven projects

## General problem with open source
  * Decide the project license
  * Decide which open source projects to include/allow in project.
  * Governance/Compliance to review only allowed/expected licenses are used.
  * Resolve projects with missing license information
  * Resolve non standard naming variants of known licenses.
  * Comply with Obligations Found, examples give credit, include copyright/license/notice.


## Tools and procedures
Have a few examples of tools that have/are being used at <https://github.com/Hack23/cia>.
* Maven plugins
* Sonarqube plugin
* FOSSA
* Copilot Blackduck
___


# Maven plugins

## Governance/Compliance Reports
<https://hack23.github.io/cia/third-party-report.html>
Dependencies
<https://hack23.github.io/cia/dependencies.html>

## Generate bill-of-material document from the project
Good to publish bom:s to maven repository using <https://github.com/CycloneDX/cyclonedx-maven-plugin>

## Configuration

Resolve projects with missing license information : <https://github.com/Hack23/cia/blob/master/citizen-intelligence-agency/src/license/THIRD-PARTY.properties>



```      <plugin>
        <groupId>org.codehaus.mojo</groupId>
        <artifactId>license-maven-plugin</artifactId>
        <version>2.0.0</version>
        <configuration>
          <excludedScopes>test</excludedScopes>
          <useMissingFile>true</useMissingFile>
          <includedLicenses>
            <includedLicense>Public Domain</includedLicense>
            <includedLicense>GNU Lesser General Public Licence (LGPL)</includedLicense>
            <includedLicense>GNU General Lesser Public License (LGPL) version 2.0</includedLicense>
            <includedLicense>GNU General Lesser Public License (LGPL) version 2.1</includedLicense>
            <includedLicense>GNU General Lesser Public License (LGPL) version 3.0</includedLicense>
            <includedLicense>The Apache Software License, Version 2.0</includedLicense>
            <includedLicense>The Apache Software License</includedLicense>
            <includedLicense>Eclipse Public License - Version 1.0</includedLicense>
            <includedLicense>CDDL+GPL License</includedLicense>
            <includedLicense>Common Development and Distribution License (CDDL) version 1.0</includedLicense>
            <includedLicense>Common Development and Distribution License (CDDL) version 1.1</includedLicense>
            <includedLicense>GNU General Public License, version 2,with the Classpath Exception</includedLicense>
            <includedLicense>CDDL + GPLv2 with classpath exception</includedLicense>
            <includedLicense>Bouncy Castle Licence</includedLicense>
            <includedLicense>New BSD License</includedLicense>
            <includedLicense>The BSD License</includedLicense>
            <includedLicense>BSD-like</includedLicense>
            <includedLicense>Common Public License</includedLicense>
            <includedLicense>Do What the Fuck You Want to Public License</includedLicense>
            <includedLicense>The JSON License</includedLicense>
            <includedLicense>The MIT License</includedLicense>
            <includedLicense>Mozilla Public License Version 1.1</includedLicense>
            <includedLicense>Mozilla Public License Version 2.0</includedLicense>
            <includedLicense>Indiana University Extreme! Lab Software License, vesion 1.1.1</includedLicense>
            <includedLicense>BSD style</includedLicense>
            <includedLicense>Eclipse Distribution License (EDL), Version 1.0</includedLicense>
            <includedLicense>Similar to Apache License but with the acknowledgment clause removed</includedLicense>
            <includedLicense>The W3C Software License</includedLicense>
            <includedLicense>W3C Software Copyright Notice and License</includedLicense>
          </includedLicenses>
          <licenseMerges>
            <licenseMerge>GNU General Public License, version 2,with the Classpath Exception|GPLv2+CE|GPL2 w/ CPE|GNU General Public License, Version 2 with the Classpath Exception</licenseMerge>
            <licenseMerge>Common Public License|CPL</licenseMerge>
            <licenseMerge>Do What the Fuck You Want to Public License|WTFPL</licenseMerge>
            <licenseMerge>GNU Lesser General Public Licence (LGPL)|GNU Lesser General Public Licence|Lesser General Public License (LGPL)|GNU LESSER GENERAL PUBLIC LICENSE|GNU Lesser General Public License|LGPL</licenseMerge>
            <licenseMerge>GNU General Lesser Public License (LGPL) version 2.1|LGPL 2.1|GNU Lesser General Public License, Version 2.1</licenseMerge>
            <licenseMerge>The Apache Software License, Version 2.0|Apache License 2.0|Apache 2|Apache License, Version 2.0|Apache 2.0|Apache Software License - Version 2.0|Apache License, version 2.0|Apache License Version 2.0|ASF 2.0|AL 2.0</licenseMerge>
            <licenseMerge>The Apache Software License|Apache Software Licenses|ASL</licenseMerge>
            <licenseMerge>Eclipse Public License - Version 1.0|Eclipse Public License - v 1.0|Eclipse Public License (EPL), Version 1.0|Eclipse Public License 1.0</licenseMerge>
            <licenseMerge>Common Development and Distribution License (CDDL) version 1.0|Common Development and Distribution License (CDDL) v1.0|COMMON DEVELOPMENT AND DISTRIBUTION LICENSE (CDDL) Version 1.0|CDDL|Common Development and Distribution License</licenseMerge>
            <licenseMerge>Common Development and Distribution License (CDDL) version 1.1|CDDL 1.1</licenseMerge>
            <licenseMerge>The BSD License|BSD|BSD licence|BSD License</licenseMerge>
            <licenseMerge>Mozilla Public License Version 1.1|MPL 1.1</licenseMerge>
            <licenseMerge>The MIT License|MIT License|MIT license</licenseMerge>
            <licenseMerge>BSD style|dom4j|BSD-Style|BSD-Style License</licenseMerge>
          </licenseMerges>
          <failIfWarning>true</failIfWarning>
        </configuration>
      </plugin>
```
___


# Sonarqube

## Report
<https://www.hack23.com/sonar/project/extension/licensecheck/dashboard?id=com.hack23.cia%3Acia-all&qualifier=TRK>

### Config
<https://github.com/porscheinformatik/sonarqube-licensecheck>
___



# FOSSA

## Report
<https://app.fossa.io/projects/git%2Bgithub.com%2FHack23%2Fcia?ref=badge_large>

## Export
<https://app.fossa.com/projects/git%2Bgithub.com%2FHack23%2Fcia/refs/branch/master/10b06718e7ffc355fa299f916b73032e2095799c/export>
___



# Copilot Blackduck

##Report
<https://copilot.blackducksoftware.com/github/repos/Hack23/cia/branches/master>


___
