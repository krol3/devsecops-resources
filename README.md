# Devops - DevSecOps - Checklist [![Awesome](https://awesome.re/badge.svg)](https://github.com/krol3/devsecops-resources)

![DevSecOps](https://github.com/krol3/devsecops-resources/blob/main/devsecops.png)

## Good practices Securing the code

- Conformance to process:
  * Code reviews
  * Coding Standards
  * Verifiable builds
  * Test coverage
  * Static Analysis
  * Vulnerability Scanning
  * Verifiable deployments

- Audit Traceability

- Inmutable infrastructure
  * Docker
  * Image OS

- Standard Tooling ??? - Controversial

- Enforce compliance in the pipeline

## Pipeline must have 16 gates
* Source code version control
* Optimum branching strategy
* Static analysis
* > 80% Code coverage
* Vulnerability scan
* Open source scan
* Artifact version control
* Auto provision
* Inmutable servers
* Integration testing
* Performance testing
* Build, deploy, testing automated for every commit
* Automated Rollback
* Automated Change Order
* Zero downtime release
* Feature Toggle

## Security fundamentals
- Vulnerability management (Automating, dashboard)
- Continuous scanning - AppSec Pipeline
- Asset inventory

---
## Nice talks and blogs about Devops
- [os-primeiros-passos-para-uma-carreira-devops by Gomex](https://gomex.me/2018/01/05/os-primeiros-passos-para-uma-carreira-devops/)
- [Devops-exercises](https://github.com/bregman-arie/devops-exercises)
- [Delivery Pipelines as enabler for a DevOps culture](https://medium.com/hackernoon/delivery-pipelines-as-enabler-for-a-devops-culture-ebc45963f703)

## Nice talks and blogs about DevSecOps
* [Controlled Chaos: The Inevitable Marriage of DevOps & Security - Blackhat USA 2019](https://youtu.be/LGaD9p1rQ2s)
* [Designing a Secure Software Development Lifecycle with DevOps - Mike Long](https://youtu.be/yqqhrrZK62Q)
* [The Current State of DevSecOps Metrics by Bill Nichols - 2021](https://insights.sei.cmu.edu/blog/the-current-state-of-devsecops-metrics/) - [Slides](https://published-prd.lanyonevents.com/published/rsaus20/sessionsFiles/17446/2020_USA20_DSO-T11_01_DevSecOps%20State%20of%20the%20Union.pdf)
* [Gibler - How to 10X Your Security - 2020](https://docs.google.com/presentation/d/1lfEvXtw5RTj3JmXwSQDXy8or87_BHrFbo1ZtQQlHbq0/edit?usp=sharing)
* [appsec-cali-2019-lessons-learned-from-the-devsecops-trenches/](https://tldrsec.com/blog/appsec-cali-2019-lessons-learned-from-the-devsecops-trenches/)
* [why-am-i-rooting-for-a-new-category-in-owasp-top-10-2021-insecure-build-deployment-environment](https://infosecwriteups.com/why-am-i-rooting-for-a-new-category-in-owasp-top-10-2021-insecure-build-deployment-environment-e255242530e9)
* [devsecops blogs by Carnegie Mellon University](https://insights.sei.cmu.edu/blog/topics/devsecops/)

## Devops Course 

* [devops-culture-and-mindset - Coursera course](https://www.coursera.org/learn/devops-culture-and-mindset/home/welcome)
* [The Ops School](https://www.opsschool.org/introduction.html)
* [devsecops bootcamp](http://devsecops.github.io/)


## DevSecOps Tools
* [Sysadmin landscape](https://sysadmin.it-landscape.info/)
* [DevSecOps Ref Architecture](https://www.sonatype.com/hubfs/DevSecOps%20Reference%20Architecture.pdf)
* [Open source security tools](https://techblog.bozho.net/list-of-open-source-security-tools/)
* [Periodic Table of DevOps Tools](https://xebialabs.com/periodic-table-of-devops-tools/) - _XebiaLabs_ - A collection of DevSecOps tooling categorised by tool functionality.

## Secure Software Guidelines - SDLC

- [Cloud Security and DevSecOps Best Practices by Sans.org](https://www.sans.org/security-resources/posters/cloud-security-devsecops-practices/200/download).
- [pagerduty_security_training_for_engineers_public.pdf](https://sudo.pagerduty.com/assets/pdf/pagerduty_security_training_for_engineers_public.pdf)
- [secure-coding-practices-quick-reference-guide by OWASP](https://owasp.org/www-project-secure-coding-practices-quick-reference-guide/migrated_content)
- [Application Security Verification Standard](https://owasp.org/www-project-application-security-verification-standard/) - _OWASP_ - A framework of security requirements and controls to help developers design and develop secure web applications.
- [Coding Standards](https://wiki.sei.cmu.edu/confluence/display/seccode/SEI+CERT+Coding+Standards) - _CERT_ - A collection of secure development standards for C, C++, Java and Android development.
- [Proactive Controls](https://owasp.org/www-project-proactive-controls/) - _OWASP_ - OWASP's list of top ten controls that should be implemented in every software development project.
- [Secure Coding Guidelines](https://wiki.mozilla.org/WebAppSec/Secure_Coding_Guidelines) - _Mozilla_ - A guideline containing specific secure development standards for secure web application development.
- [Secure Coding Practices Quick Reference Guide](https://owasp.org/www-pdf-archive/OWASP_SCP_Quick_Reference_Guide_v2.pdf) - _OWASP_ - A checklist to verify that secure development standards have been followed.

### Frameworks
- [Secure Software Development Life Cycle Processes by Carnegie Mellon University](https://resources.sei.cmu.edu/asset_files/WhitePaper/2013_019_001_297287.pdf)
Frameworks and standards such as the Capability Maturity Model Integration2 (CMMI) framework, Team Software Process (TSP),3 the FAA-iCMM, the Trusted CMM/Trusted Software Methodology (T-CMM/TSM), and the Systems Security Engineering Capability Maturity Model (SSE-CMM). In addition, Two approaches, Software Assurance Maturity Model (SAMM) and Software Security Framework (SSF), which were just released, have been added to give the reader as much current information as possible.
- [Building Security In Maturity Model (BSIMM)](https://www.bsimm.com/framework.html) - _Synopsys) - A framework for software security created by observing and analysing data from leading software security initiatives.
- [Secure Development Lifecycle](https://www.microsoft.com/en-us/securityengineering/sdl/practices) - _Microsoft_ - A collection of tools and practices that serve as a framework for the secure development lifecycle.
- [Secure Software Development Framework](https://csrc.nist.gov/CSRC/media/Publications/white-paper/2019/06/07/mitigating-risk-of-software-vulnerabilities-with-ssdf/draft/documents/ssdf-for-mitigating-risk-of-software-vulns-draft.pdf) - _NIST_ - A framework consisting of practices, tasks and implementation examples for a secure development lifecycle.
- [Software Assurance Maturity Model](https://github.com/OWASP/samm) - _OWASP_ - A framework to measure and improve the maturity of the secure development lifecycle.

## Security by Design
[security-design-with-principles 2021](https://medium.com/ouspg/security-design-with-principles-a8c045765b93)
[bottom-up-security-testing-security-in-all-levels 2021](https://medium.com/ouspg/bottom-up-security-testing-security-in-all-levels-654e4f7e8ed7)
[8-security-design-principles-business-solutions](https://www.openbusinesscouncil.org/8-security-design-principles-business-solutions/)
[Security Design Principles](https://line.17qq.com/articles/klgpomlov.html)

## Open Source Static Analysis Tools
* C/C++ - Clang Static Analyzer, Phasar, Cppcheck
* C#/.NET - Puma Scan, Security Code Scan
* Golang - gosec, glasgo
* Java - SpotBugs, Frameworks: Soot, WALA
* JavaScript/Typescript - NodeJsScan, eslint, tslint, eslint-pluginno-unsanitized
* Python - bandit, dlint, pyre-check (data-flow analysis to find
* web app bugs)
* Ruby - Brakeman
* [Semgrep](https://github.com/returntocorp/semgrep#readme) - Python, JavaScript, Golang, Java, ...


Massive list: [mre/awesome-static-analysis](https://github.com/analysis-tools-dev/static-analysis)

## Intentionally Vulnerable Applications

let you practice your skills at exploiting them.

- [Bad SSL](https://github.com/chromium/badssl.com) - _The Chromium Project_ - A container running a number of webservers with poor SSL / TLS configuration. Useful for testing tooling.
- [Cfngoat](https://github.com/bridgecrewio/cfngoat) - _Bridgecrew_ - Cloud Formation templates for creating stacks of intentionally insecure services in AWS. Ideal for testing the Cloud Formation Infrastructure as Code Analysis tools above.
- [Damn Vulnerable Web App](http://www.dvwa.co.uk/) - _Ryan Dewhurst_ - A web application that provides a safe environment to understand and exploit common web vulnerabilities.
- [Juice Shop](https://github.com/bkimminich/juice-shop) - _OWASP_ - A web application containing the OWASP Top 10 security vulnerabilities and more.
- [NodeGoat](https://github.com/OWASP/NodeGoat) - _OWASP_ - A Node.js web application that demonstrates and provides ways to address common security vulnerabilities.
- [Terragoat](https://github.com/bridgecrewio/terragoat) - _Bridgecrew_ - Terraform templates for creating stacks of intentionally insecure services in AWS, Azure and GCP. Ideal for testing the Terraform Infrastructure as Code Analysis tools above.
- [Vulnerable Web Apps Directory](https://owasp.org/www-project-vulnerable-web-applications-directory) - _OWASP_ - A collection of vulnerable web applications for learning purposes.

## SRE
- [Squadcast](https://squadcast.com) - _Squadcast_ - Modern Incident Response with Intuitive Actionable Alerting and On-Call. Practice Site Reliability Engineering
(SRE) through better Incident Management to proactively respond, resolve, and learn from every incident.

## Devops Podcasts

* [DevSecOps Podcast by Cássio B. Pereira - Portugues](https://youtube.com/playlist?list=PLC2UsZBhySmJU0EYM6kzgchnXikYXZzmi)

## Samples applying DevSecOps

* Java: https://github.com/fvilarinho/demo
* IaaC: https://github.com/krol3/infra-code-tf

## Awesome DevSecOps Resources
- https://github.com/TaptuIT/awesome-devsecops/blob/main/readme.md
- https://github.com/hp271/awesome-dev-first-security
