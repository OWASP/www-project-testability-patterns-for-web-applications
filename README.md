# OWASP Testability Patterns for Web Applications
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white)![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)


This repository contains the markdown / container for the OWASP Testability Patterns for Web Applications. 

The OWASP Testability Patterns project intends to create a community to re-design the classical secure development life-cycle around the concept of **Testability Patterns**, providing new tools for Web and AI/ML developers, managers, and security teams. In summary, the project aims to:

- curate a catalog of testability patterns for code analysis tools (that can act as a benchmark for them).
- create a framework that can automatically identify testability patterns in real-world software, and can run the patterns' benchmark against code analyis tools. 


## What is a Testability Pattern?

**Testability Patterns** (TPs) are problematic code instructions that affect the capability of code analysis tools for security testing. Due to TPs, SAST tools may not detect an existing vulnerability, or conversely, report a false alarm. This project intends to create a catalog of testability patterns. 


## TP-Catalogs: Testability Pattern Catalogs for SAST

This repository includes the catalogs of SAST testability patterns. At the time being, it supports the following programming languages:

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

Found a code snippet affecting a SAST tool? Join and contribute to our catalog. 

Want to test your SAST tools against our catalog? Extend [TP-Framework](https://github.com/testable-eu/sast-tp-framework) to support your tool. 

Need some help? Please visit our contribution guidelines [here](https://github.com/testable-eu/sast-testability-patterns/blob/master/docs/contribution-guidelines.md).


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

## Acknowledgements

This project received funding from the European Union's Horizon 2020 research and innovation programme under grant agreement No. 101019206.

<br>
<p align="center">
<a href="https://testable.eu"><img src="/assets/images/eu_flag.png" alt="EU Flag"/></a>
</p>



