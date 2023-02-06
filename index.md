---
layout: col-sidebar
title: OWASP Testability Patterns for Web Applications
tags: home
level: 2
type: 
pitch: TestabiliTy Pattern-driven Web Application Security and Privacy Testing

---

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white)![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)


# OWASP  Testability Patterns for Web Applications
OWASP TESTABLE redefines the classical secure development life-cycle around the concept of testability, providing new tools for:
- Web and AI/ML Developers
- Managers
- Security Teams

## Objective
The OWASP project aims to deliver tools and methodologies for:
- Managers: New metric quantifying the security and privacy risks of a program.
- Developers: Better and flexible tools to improve testability, reducing security and privacy risk exposure.
- Security teams: Better and more flexible security, privacy testing, and AI/ML tools.

## Roadmap

- June 2022: OWASP Project created
- February 2023:
  - OWASP Project kickstart @ OWASP AppSec EU
  - Open Source release of the main project repositories
- September 2023: 
- September 2024: Release of the TESTABLE Standard Document
- Later 2024: Active and self sustained community

### More secure web applications with privacy incorporated
The application of standard business practices to building software applications is advancing rapidly to meet the evolving needs of web-based application software powered by artificial intelligence (AI). The EU-funded TESTABLE project proposes a software development lifecycle (SDLC) that combines two metrics to quantify the security and privacy risks of a program: the code testability and vulnerable behaviour indicators. TESTABLE will empower software/AI developers, managers, testers, and auditors to reduce the risk by building better security and privacy testing techniques for web applications and removing or mitigating the impact of the patterns causing the high-risk levels. It will develop algorithms, techniques, and tools to analyse, test, and study web applications.

## Project Components

### Testability Pattern Catalogs for SAST
This repository includes the catalogs of SAST testability patterns. **Testability Patterns** (TPs) are problematic code instructions that affect the capability of code analysis tools for security testing. Due to TPs, SAST tools may not detect an existing vulnerability, or conversely, report a false alarm. 

### TP-Framework: Testability Pattern Framework for SAST
TP-Framework relies on [testability patterns](https://github.com/testable-eu/sast-testability-patterns) to reduce false positive/negative rate in SAST analysis over supported programming languages.

TP-Framework enables operations such as:
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


## Next Talk: OWASP AppSec Dublin 16th February
[Luca Compagna](https://owasp2023globalappsecdublin.sched.com/speaker/luca.compagna?iframe=yes&w=100%&sidebar=yes&bg=no) will talk about the project at the next [OWASP AppSec Dublin](https://dublin.globalappsec.org) <br>
When: Thursday February 16, 2023 10:30am - 11:30am GMT <br>
Where: Liffey Meeting Room 2 <br>
<p align="center">
  <img src="https://www.theccd.ie/media/event_listing/owasp_global_appsec.png"><br>
</p>

## Publications
To see the complete list publications, please visit [https://testable.eu/publications/](https://testable.eu/publications/).

## Acknowledgements

This project received funding from the European Union's Horizon 2020 research and innovation programme under grant agreement No. 101019206.

<p align="center">
  <img src="https://testable.eu/img/eu_flag.png"><br>
  Funded by the European Union
</p>




