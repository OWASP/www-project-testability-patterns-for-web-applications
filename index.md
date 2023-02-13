---
layout: col-sidebar
title: OWASP Testability Patterns for Web Applications
tags: home
level: 2
type: 
pitch: TestabiliTy Pattern-driven Web Application Security and Privacy Testing

---

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white)![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)


# OWASP Testability Patterns for Web Applications

The OWASP Testability Patterns project intends to create a community to re-design the classical secure development life-cycle around the concept of **Testability Patterns**, providing new tools for Web and AI/ML developers, managers, and security teams. In summary, the project aims to:

- Curate a ***catalog of testability patterns*** for security testing tools (i.e., a security testing tool benchmark).
- Create a framework that can automatically ***identify testability patterns in programs***, and can ***run the patterns' benchmark against testing tools***. 


## What is a Testability Pattern?

**Testability Patterns** (TPs) are problematic code instructions that affect the capability of security testing tools. Due to TPs, security testing tools may miss vulnerabilities, or conversely, report a false alarm. This project intends to create a catalog of testability patterns. 


## TP-Catalogs: Testability Patterns Catalog

This repository includes the catalogs of testability patterns. Currently, the project focuses on testability patterns affecting static analysis security testing tools (SAST) and it supports the following programming languages:

- Java
- PHP
- JavaScript

The repository is available at: [https://github.com/testable-eu/sast-testability-patterns](https://github.com/testable-eu/sast-testability-patterns).

## TP-Framework: Testability Pattern Framework for SAST

[TP-Framework](https://github.com/testable-eu/sast-tp-framework) relies on [testability patterns](https://github.com/testable-eu/sast-testability-patterns) to reduce false positive/negative rate in SAST analysis over supported programming languages. TP-Framework enables operations such as:
- Measurement of SAST tools against a catalog of testability patterns
- Discovery of testability patterns within application source code

These features can enable for example the following types of user experiences:
- **Developers**:
  - Measuring the occurrences of the TPs in codebases
  - Remediating the TPs in codebases
- **Managers**:
  - Measuring the most effective SAST tool to be used in the SDLC pipeline
- **SAST Tools Developers**: 
  - Measuring the effective coverage and performance of their tools
  - Discovering the problematic TPs and improve the tool engine to correctly handle the TPs

Future works include the possibility to enable patterns' transformations directly from the framework in ordet to improve the testability of the SAST scanned application.   

The repository is available at: [https://github.com/testable-eu/sast-tp-framework](https://github.com/testable-eu/sast-tp-framework)

## How you can contribute?

You can join our nascent community and help the project in different ways:

1. Found a code snippet affecting a SAST tool? Join and contribute to our catalog. 
2. Want to test your SAST tools against our catalog? Extend [TP-Framework](https://github.com/testable-eu/sast-tp-framework) to support your tool. 

Contribution guidelines are [here](https://github.com/testable-eu/sast-testability-patterns/blob/master/docs/contribution-guidelines.md).


## Vision
The OWASP project aims to deliver tools and methodologies for:
- Managers: New metric quantifying the security and privacy risks of a program.
- Developers: Better and flexible tools to improve testability, reducing security and privacy risk exposure.
- Security teams: Better and more flexible security, privacy testing, and AI/ML tools.

### More secure web applications with privacy incorporated
The application of standard business practices to building software applications is advancing rapidly to meet the evolving needs of web-based application software powered by artificial intelligence (AI). The EU-funded TESTABLE project proposes a software development lifecycle (SDLC) that combines two metrics to quantify the security and privacy risks of a program: the code testability and vulnerable behaviour indicators. TESTABLE will empower software/AI developers, managers, testers, and auditors to reduce the risk by building better security and privacy testing techniques for web applications and removing or mitigating the impact of the patterns causing the high-risk levels. It will develop algorithms, techniques, and tools to analyse, test, and study web applications.


## Roadmap
- June 2022: OWASP Project created
- February 2023:
  - OWASP Project kickstart @ OWASP AppSec EU
  - Open Source release of the main project repositories
- September 2023: 
- September 2024: Release of the TESTABLE Standard Document
- Later 2024: Active and self sustained community

## Next Talk: OWASP AppSec Dublin 16th February
[Luca Compagna](https://owasp2023globalappsecdublin.sched.com/speaker/luca.compagna?iframe=yes&w=100%&sidebar=yes&bg=no) will talk about the project at the next [OWASP AppSec Dublin](https://dublin.globalappsec.org) <br>
When: Thursday February 16, 2023 10:30am - 11:30am GMT <br>
Where: Liffey Meeting Room 2 <br>
<br>
<p align="center">
<a href="https://dublin.globalappsec.org"><img src="/assets/images/owasp_global_appsec.png" alt="AppSec Dublin"/></a>
</p>

## Publications
To see the complete list of publications, please visit [https://testable.eu/publications/](https://testable.eu/publications/).

## Project partners

- [CISPA](https://cispa.de/)
- [Eurecom](https://www.eurecom.fr/en/)
- [Technical University of Braunschweig](https://www.tu-braunschweig.de/)
- [UC3M](https://www.uc3m.es/)
- [SAP SE](https://www.sap.com/)
- [ShiftLeft](https://www.shiftleft.io/)
- [IMQ Minded Security](https://mindedsecurity.com/)
- [NortonLifeLock](https://www.nortonlifelock.com/)
- [Pluribus One](https://www.pluribus-one.it/)

## Acknowledgements

This project received funding from the European Union's Horizon 2020 research and innovation programme under grant agreement No. 101019206.

<br>
<p align="center">
<a href="https://testable.eu"><img src="/assets/images/eu_flag.png" alt="EU Flag"/></a>
</p>

