# Awesome-Decision-Automation-Platform

## Top Decision Automation Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Business Rule Engines, DMN Decision Models & Process Orchestration*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Decision Automation**. These tools help organizations model, execute, and govern business decisions—from simple rule evaluation to complex DMN decision services—decoupling decision logic from application code.



**Examples** include Pega, Decisions, Red Hat Decision Manager, FICO Blaze Advisor, Drools, IBM ODM, FlexRule, InRule, Camunda DMN, OpenRules, and DecisionRules.io (the category leaders).



**Open-source emphasis**: Decision automation has a **mature and standards-driven open-source ecosystem**. **Apache KIE (Drools)** achieves **99.91% DMN TCK conformance**, placing it among the top engines globally . **Flowable** provides native BPMN, CMMN, and DMN engines with strong low-code tooling . **Camunda** remains the most widely adopted BPMN/DMN platform, though its DMN TCK scores date from 2024 . **IBM Process Automation Manager Open Edition** (formerly Red Hat) delivers an enterprise-grade open-source foundation built on Kogito, Drools, and jBPM . This section documents these production-grade solutions.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents



- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Pega](https://www.pega.com/)**  

  Enterprise decision automation and BPM platform. Provides decision management, case management, and AI-powered automation with the Pega Platform.



- **[Decisions](https://decisions.com/)**  

  Low-code decision automation platform. Provides rule engines, workflow automation, and decision services with a visual designer.



- **[Red Hat Decision Manager](https://www.redhat.com/)**  

  Enterprise decision management platform built on Drools. Provides business rule management, DMN decision models, and real-time decision services.



- **[FICO Blaze Advisor](https://www.fico.com/)**  

  Enterprise business rules management system. Provides decision automation with strong governance and compliance capabilities.



- **[IBM ODM](https://www.ibm.com/)**  

  IBM Operational Decision Manager. Enterprise decision automation platform with rule engine, decision tables, and decision modeling.



- **[FlexRule](https://flexrule.com/)**  

  Decision automation and business rules platform. Provides rule engines, decision models, and workflow automation.



- **[InRule](https://inrule.com/)**  

  Decision automation platform with rule engine, decision modeling, and AI integration.



- **[Camunda SaaS](https://camunda.com/)**  

  Managed Camunda 8 platform with Zeebe engine. Provides BPMN process orchestration, DMN decision models, and external worker architecture.



- **[DecisionRules.io](https://decisionrules.io/)**  

  Cloud-based decision automation platform. Provides rule engine, decision tables, and API-first decision services.



## Open-Source GitHub Projects



### BPMN & DMN Engine Platforms



- **[Flowable](https://github.com/flowable/flowable-engine)**  

  **The most balanced open-source BPMN/DMN engine for Java.** **Apache 2.0 licensed**. Native BPMN, CMMN, and DMN engines built on a rewritten v6 execution model with predictable scoping and consistent execution trees . **Flowable 8.0.0** spans Spring 7, Boot 4, and Jackson 3 upgrades . **Key strengths**: Embedded transaction model integrates easily with Java business systems; multi-instance and dynamic state changes enable countersign, return, and jump customizations; Apache 2.0 and relational database model favor private deployment; rich experience in domestic OA and low-code secondary development . **Best for**: Chinese-style OA, low-code approval workflows, and order fulfillment .



- **[Camunda 7 / Camunda Platform](https://github.com/camunda/camunda-bpm-platform)**  

  **The most widely adopted open-source BPMN engine.** **Apache 2.0 licensed** (Community Edition). Provides BPMN process automation, DMN decision models, and a mature ecosystem with Modeler, Cockpit, and Tasklist . **Camunda 7** remains on the Activiti 5 Engine architecture, while **Camunda 8** uses the Zeebe distributed engine . **Note**: Camunda 7 is in maintenance mode; Camunda 8 requires production licensing for self-managed use since 8.6 . **DMN TCK**: 80.86% (Camunda Platform 7.21, July 2024) . **Best for**: Teams with BPMN/DMN expertise and existing Camunda investments.



- **[Operaton](https://github.com/operaton/operaton)**  

  **A community fork of Camunda 7.** Provides a drop-in replacement for Camunda 7 with the same BPMN/DMN capabilities . **Best for**: Organizations needing to continue Camunda 7-style workflows without vendor lock-in.



- **[CIB seven](https://github.com/cibseven/cibseven)**  

  **Another Camunda 7 lineage fork.** Includes basic web application for process management . **Best for**: Teams seeking Camunda 7 compatibility with a community-governed alternative.



- **[Bonita](https://github.com/bonitasoft/bonita-engine)**  

  **Complete open-source BPM/DPA platform.** **GPL 2.0 licensed** (Community Edition). Provides Studio, UI Designer, application building, connectors, and runtime portal . **Key strength**: Complete platform for organizations not wanting to build process designers, pages, and task centers from scratch . **Best for**: Enterprises wanting a full BPM platform with visual development.



### Rule Engines & Decision Services



- **[Apache KIE / Drools](https://github.com/apache/incubator-kie-drools)**  

  **The leading open-source Java rule engine with top-tier DMN conformance.** **Apache 2.0 licensed**. **DMN TCK score: 99.91%** (Apache KIE 10.2.0, April 2026) . Powers **IBM Process Automation Manager Open Edition** alongside jBPM . Provides rule engine, decision tables, DMN decision models, and complex event processing. **Best for**: Java applications needing enterprise-grade rule evaluation and decision services.



- **[jBPM](https://github.com/kiegroup/jbpm)**  

  **Open-source BPM suite for Java.** Provides business process management, case management, and decision automation. Part of the KIE ecosystem alongside Drools . **Best for**: Java teams wanting an integrated BPM + rules platform.



- **[Automation Decision Engine](https://github.com/daveedashar/automation-decision-engine)**  

  **AI-powered business rule engine with decision automation, workflow orchestration, and intelligent process optimization.** **Python-based**. **Key features**: Rule engine in YAML or code; visual decision trees with branching logic; event processing for real-time reactions; action execution (workflows, APIs, notifications); complete audit trail; **A/B testing** for different rule sets in production; fallback handling for unmatched rules . **Best for**: Python teams wanting a lightweight, extensible decision engine.



- **[OpenRules](https://github.com/openrules/openrules)**  

  **Open-source business rules and decision management system.** Provides rule engine, decision tables, and decision modeling with Java integration. **Best for**: Java applications needing a mature rule engine.



- **[JevPolicy](https://github.com/Sanoy24/jevpolicy)**  

  **TypeScript decision runtime that turns probabilistic judgments into versioned, deterministic, replayable application decisions.** **Key features**: Deterministic preconditions before any provider call; provider timeouts map only to explicit policy fallbacks; **shadow evaluation** for testing candidate policies against live traffic; **policy diff** for semantic comparison; OpenTelemetry observability . **Best for**: TypeScript applications needing auditable, replayable decision logic.



- **[SemanticPolicy](https://github.com/semanticpolicy/semantic-policy)**  

  **Adds testable semantic decisions to .NET applications.** Rules are measured on labelled examples for business logic and AI agents with no provider lock-in . **Best for**: .NET applications integrating AI-driven decisions.



### Additional Strong Open-Source Options



- **BPMN/DMN Engines**: **Flowable** (most balanced, Apache 2.0, strong low-code), **Camunda 7/8** (most adopted, mature ecosystem), **Operaton** (Camunda 7 fork), **CIB seven** (Camunda 7 fork), **Bonita** (complete platform, GPL 2.0) .

- **Rule Engines**: **Apache KIE/Drools** (99.91% DMN TCK, enterprise-grade), **jBPM** (BPM + rules), **OpenRules** (rule engine + decision tables) .

- **Modern Decision Runtimes**: **Automation Decision Engine** (Python, YAML rules), **JevPolicy** (TypeScript, deterministic decisions), **SemanticPolicy** (.NET, semantic decisions) .



**Frameworks for building custom systems**: Combine **Flowable** for BPMN/DMN workflows with strong low-code tooling , **Apache KIE/Drools** for enterprise-grade rule evaluation with top DMN conformance , **Camunda 7** or **Operaton** for existing BPMN investments , and **Automation Decision Engine** or **JevPolicy** for modern, lightweight decision runtimes . Add **PostgreSQL** for persistence and **Docker** for deployment.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Decision automation platforms handle sensitive business logic and decision data; ensure proper access controls and compliance with governance policies.

- **Open-source reality**: The open-source ecosystem for decision automation is **mature and standards-driven**. **Apache KIE/Drools** achieves **99.91% DMN TCK conformance**, placing it among the top engines globally . **Flowable** provides the most balanced BPMN/DMN engine for Java with strong low-code tooling . **Camunda** remains the most widely adopted platform, though its DMN TCK scores date from 2024 . **Bonita** offers a complete BPM platform with visual development . However, **commercial platforms** (Pega, IBM ODM, FICO Blaze Advisor) provide **enterprise-grade governance, business-user-friendly authoring, and dedicated support** that open-source alternatives require additional tooling to match. **Note**: Open source is "free" in license, but TCO includes developer time, infrastructure, security, and maintenance—many organizations find these costs exceed managed platforms after 12–24 months .



---



**Made for business analysts, decision architects, Java developers, and process automation teams.**  

Let's make decision automation more open, transparent, and standards-compliant.
