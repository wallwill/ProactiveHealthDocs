Activity: E1 - Assess Strategic Architecture Gateway
Inputs
Outputs
Guidelines
Process
Task: 01 - Assess EA Inputs
Task: 02 - Understand Overall Value Streams
Task: 03 - Understand Business Context
Task: 04 - Understand Technical Landscape
Task: 05 - Assess Innovation and IP value
Activity: E2 - Design Overall Solution
Inputs
Outputs
Guidelines
Process
Task: 01 - Decompose Solution in Modules
Task: 02 - Detail Overall Value Streams
Task: 03 - Refine Overall Solution Design
Task: 04 - Design Application Architecture
Task: 05 - Design Data Architecture
Task: 06 - Review Adherence to Enterprise Standards
Task: 07 - Propose Spikes / Technical Enablers
Activity: E3 - Manage Stakeholders Communication
Inputs
Outputs
Process
Task: 01 - Gather Stakeholder List
Task: 02 - Establish Approval Chains
Task: 03 - Establish Communication  Channels
Activity: E4 - Manage Architecture Decisions
Inputs
Outputs
Guidelines
Process
Task: 01 - Propose, Detail or Approve ADR's
Activity: E5 - Manage Risks and NFR's
Inputs
Outputs
Process
Task: 01 - Manage Risks
Task: 02 - Assess NFRs
Task: 03 - Propose Spikes / Technical Enablers /ADR's 
Activity: E6 - Manage Product Platform
Inputs
Outputs
Task: 01 - Support CI / CD
Task: 02 - Support and Coordinate Observability
Task: 03 - Coordinate with Devops
Task: 04 - Support Test Automation
Task: 05 - Optimise Product Resources
Task: 06 - Support Performance Engineering
Task: 07 - Propose Spikes / Technical Enablers /ADR's 
Task: 08 - Tag and Register Application in Platform Management Repos
Task: 09 - Monitor and Manage Application Vulnerabilities
Activity: E7 - Manage Product Security and Compliance
Inputs
Outputs
Process
Task: 01 - Submit Security Architect Report
Task: 02 - Submit Data Governance Report
Task:  03 - Submit Data Encryption Report
Task:  04 - Submit Disaster Recovery Report
Task: 05 -  Submit User Lifecycle Management Report
Task:  06 - Submit AI Report
Task: 07 - Submit Application Security Report
Task:  08 - Submit Change Management Report
Task:  09 - Submit SDLC Report
Phase: Feature Solution Intent Process
Activity: F1 - Design Feature Solution Intent
Inputs
Outputs
Guidelines
Process
Task: 01 - Run Impact Analysis
Task: 02 - Collaborate with PO on  System Use Cases / A/C
Task: 03 - Collaborate with Application Architect / Tech Leaders
Task: 04 - Collaborate with UX Designers
Task: 05 - Address NFR's
Task: 06 - Verify Adherence to Enterprise Standards
Task: 07 - Review and Sign Off Application Architecture
Task: 08 - Propose Spikes / Technical Enablers /ADR's 
Activity: F2 - Manage Stakeholders
Activity: F3 - Manage Architecture Decisions
Activity: F4 - Risks and NFR's
Activity: F5 - Manage Product Platform
Activity: F6 - Submit Application for Security Review
References
Files
Overview


The purpose of this page is describe the Solution Architecture process as we practice in CGS Ireland. The intent of this page is not a hard prescriptive process but state the set of best Practices as we, Ireland Solution Architects, understand.

As an Elevance subsidiary we cannot stick to a single process once we provide services to different Business Units with different SLDC tailoring. 

Despite that we can follow to a set of Enterprise Architecture and Solution Architecture disciplines best practices adopted by the industry and a set of guidelines already supported by Elevance, including (Note: You can find comprehensive references list in the 'reference' section):


DOTS - Technical Architecture
Elevance - Software Development Life Cycle
Elevance - Agile Framework Community Library Home
Elevance - Domain Architecture
Elevance - Business Capability Model - BCM 2.0
Elevance - Enterprise Architecture and Governance
Elevance - Enterprise ECOSYSTEM
TOGAF 10 - (Requires Open Group registration)
Tailoring Guide
asdasd

Compliance
Architecture Solution Delivery Process - IT-CMF Compliance - Draft 1

Solution Architecture Process
Due to the different Solution Architecture effort profiles on a project lifecycle and the different SDLC maturity stages we introduced the concept of phase. A phase suggests the focus of SA activities in the context of a product lifecycle, wether he should be performing Overall Product Architecture solution or Feature / Module solution.

We have two great phases now:

Solution Intent Elaboration - The SA activities performed during the Discovery or Elaboration phase of a product 
Feature Solution Intent Process - The SA activities performed during the active construction of the product


Note: In future we may need to consider transition activities to hand off the product to a business unit 



Phase: Solution Intent Elaboration
In the Solution Intent Elaboration phase we have following goals:

Understand the scope of the incoming product / project
Gather Technical Risks and build a mitigation plan
Application Modularisation and Business Capability Mapping 
Application architecture
Data Architecture
Architecture aligns to Elevance standards (DOTS and ESG)
Leverage Enterprise Cloud Platform
Activity: E1 - Assess Strategic Architecture Gateway
Our goal is assess if the requirements for proceeding with the product development are fulfilled. Solution Architects provide a Strategic Architeture Acceptance document stating wether EA inputs qulality where met or not. Additionally, if SA recognise that the project has potential ti innovation and IP, the Statement over Innovation and IP is produced.

Inputs
Cloud Architecture
Technical Architecture
Business Architecture
Epics List
Enterprise Architecture Inputs:
SVRO (formerly OTIC)
Solution Intent Architecture Repository
01 - Solution Intent in Review
00 - Solution Intent Published 
Example: Advanced Home Delivery (OTIC 2024)
Example - Updated BCM / Value Stream: OTIC 2024 - Health Solutions
BCM
OTIC 2024 - BCM Mapping
Business Architecture (Ireland)
Domain Architecture
BCM Home (High Level Functions)
DOTS Patterns
Technical Architecture
RAPL Patterns
Reference Architecture Patterns Library
Outputs
Strategic Architecture Acceptance (see: Template - Strategic Architecture Acceptance)
Statement over innovation and IP
Guidelines
Architecture Solution Delivery Checklist - Draft 1
Process
Task: 01 - Assess EA Inputs
We check the main inputs from Enterprise Architecture: Cloud Architecture, Business architecture, Technical Architecture, and assess if we have all required information to proceed with the product development according the criteria stablished by Architecture Solution Delivery Checklist - Draft 1 .

Task: 02 - Understand Overall Value Streams
We understand the value streams defined by business and touched business capabilities, identifying possible gaps and opportunities for refinements to be carried during Overall Solution Intent activity.

Task: 03 - Understand Business Context
Based on the Business Architecture and Business Capability Model we understand the priorities in terms of Business Capabilities and Value Streams, identify the gaps the new application should solve and possible business risks like 3rd party contract sign offs, delivery of external capabilities.

Task: 04 - Understand Technical Landscape
We acknowledge the technical architecture and technical stack proposed by technical architecture and double check the technical stack suitability, our internal capacity to address technical architecture and eventual risks to be managed/mitigated on further activities.

Task: 05 - Assess Innovation and IP value
SA and Product Managers analyses the innovation and IP value. The assessment report is documented in the Statement over Innovation and IP report. 

Activity: E2 - Design Overall Solution
This is the core activity in the Solution Intent Elaboration. Here we develop the application architecture based on the inputs from Enterprise Architecture. The Goals:

Define High Level Design / Application Design / Dat Architecture to guide a application development
Guarantee the application compliance to the Enterprise Architecture / Strategic Architecture guidelines
Inputs
Cloud Architecture
Business Architecture
Technical Architecture
Epic List
Enterprise Architecture Inputs:
SVRO (formerly OTIC)
Solution Intent Architecture Repository
Example: Advanced Home Delivery (OTIC 2024)
GOOD EXAMPLE: Project Eagle - Carelon Behavioral Health Crisis Safety Platform CSP
BCM
OTIC 2024 - BCM Mapping
Business Architecture (Ireland)
Domain Architecture
BCM Home (High Level Functions)
DOTS Patterns
Technical Architecture
Elevance Standards Governance (ESG)
ESG Home
RAPL Patterns
Reference Architecture Patterns Library
Outputs
Module/Service canvas

Application Architecture
Overall Solution Architecture (Disaster Recovery, IAM User Lifecycle)
Data Architecture (Conceptual Models, Data Governance, Data Encryption)
Proposed Spikes / Technical Enabler
ADR's
Guidelines
Guideline - Modularization and Business Capability Allocation
External Guidelines
TOGAF 10 - (Requires Open Group registration)
Twelve Factor Application
AWS Well-Architected Framework
Pattern anguage for microservices
Azure - Cloud Design Patterns
EIP - Enterprise Integration Patterns
Kafka - Event Streaming Patterns
Process
Task: 01 - Decompose Solution in Modules
Come up with the detailed architecture of the application representing the concurrency view of the application. The various modules and the interactions (protocols, ports) shall also be detailed

Review the Business Capabilities (BCM) assigned to present application and determine the  application module or modules in which those capabilities will be implemented. This is a very dynamic task and may change during project development, technological constraints may affect the module structure.   

See:

Guideline - Modularization and Business Capability Allocation
SVRO (formerly OTIC)
Solution Intent Architecture Repository
Task: 02 - Detail Overall Value Streams
Depict the Value Streams as they were envisioned by Business Architecture and depict the module collaboration  in the realisation of those Value Streams.

See: Guideline - Modularization and Business Capability Allocation

Task: 03 - Refine Overall Solution Design
Refine Solution Design, taking in consideration Application Decomposition and BCM mapping.

See: TOGAF 10 - (Requires Open Group registration)

Task: 04 - Design Application Architecture
Come up with the high level architecture of the application that details the functional and non functional capabilities of the application. We should define  the modules and physical application services mappings to the modules.

See: TOGAF 10 - (Requires Open Group registration)

Task: 05 - Design Data Architecture
Come up with the Data Architecture Design of the application, covering  Data Model, Data Bases, Data Governance, Data Encryption, observing the Data Modules structure.

See: TOGAF 10 - (Requires Open Group registration)

Task: 06 - Review Adherence to Enterprise Standards
Review the DOTS Patterns published and ensure compliance with the standards. In Elevance, DOTS is an easy-to-use quarterly publication that brings all relevant corporate technology standards together into a simple timeline. It defines a straight-forward technology lifecycle framework to fit standards into (See: Technical Architecture).

Review the ESG published and ensure compliance with the architecture detailed.

See:

DOTS Patterns
Technical Architecture
Elevance Standards Governance (ESG)
ESG Home
Task: 07 - Propose Spikes / Technical Enablers
Identify and document the spikes / technical enablers that are required to finalise and meet the functional/non functional requirements of the application.

Activity: E3 - Manage Stakeholders Communication
Manage communication with stakeholders who are interested in, or are influenced by, enterprise architecture management, and manage their expectations of what it can deliver.

Inputs
Ireland - IT-CMF (EAM) - C2 Communication and Stakeholder Management
Enterprise Stakeholder Inventory
Outputs
Stakeholder Communication Plan
Process
Task: 01 - Gather Stakeholder List
Gather the list of stakeholders along with business units and roles.

Task: 02 - Establish Approval Chains
Document the stakeholders responsible for approval of significant decisions

Task: 03 - Establish Communication  Channels
Establish channels like proper e-mail lists, wiki pages, teams channels, sharepoint directories and other resources. 

Activity: E4 - Manage Architecture Decisions
An architectural decision record (ADR) is a document that describes a choice the team makes about a significant aspect of the software architecture we're planning to build. The ADR process outputs a collection of architectural decision records. This collection creates the decision log. The decision log provides the project context as well as detailed implementation and design information. 

Inputs
Cloud Architecture
Business Architecture
Technical Architecture
Epic List
Enterprise Architecture Inputs:
SVRO (formerly OTIC)
Solution Intent Architecture Repository
Example: Advanced Home Delivery (OTIC 2024)
GOOD EXAMPLE: Project Eagle - Carelon Behavioral Health Crisis Safety Platform CSP
BCM
OTIC 2024 - BCM Mapping
Business Architecture (Ireland)
Domain Architecture
BCM Home (High Level Functions)
DOTS Patterns
Technical Architecture
Elevance Standards Governance (ESG)
ESG Home
RAPL Patterns
Reference Architecture Patterns Library
Outputs
ADR's
Features, Technical Enablers proposals
Guidelines
AWS Prescriptive Guidance - ADR Process
Process
Task: 01 - Propose, Detail or Approve ADR's
All architecturally significant decisions that should be proposed, accepted, deprecated or superseded. One ADR is an architecturally significant decision that affects software including:

Structure (for example, patterns such as microservices)
Non-functional requirements (security, high availability, and fault tolerance)
Dependencies (coupling of components)
Interfaces (APIs and published contracts)
Construction techniques (libraries, frameworks, tools, and processes)
Task: 02 - Propose Spikes / Technical Enablers

Identify and document the spikes / technical enablers that are required to finalise and meet the functional/non functional requirements of the application.

Activity: E5 - Manage Risks and NFR's
Identify, measure and track Risks and NFR's.

Inputs
Cloud Architecture
Business Architecture
Technical Architecture
Epic List
Enterprise Architecture Inputs:
SVRO (formerly OTIC)
Solution Intent Architecture Repository
Example: Advanced Home Delivery (OTIC 2024)
GOOD EXAMPLE: Project Eagle - Carelon Behavioral Health Crisis Safety Platform CSP
BCM
OTIC 2024 - BCM Mapping
Business Architecture (Ireland)
Domain Architecture
BCM Home (High Level Functions)
DOTS Patterns
Technical Architecture
Elevance Standards Governance (ESG)
ESG Home
RAPL Patterns
Reference Architecture Patterns Library
Outputs
Risk Mitigation Plan
NFR's Management Plan
Process
Task: 01 - Manage Risks
Identify the risks in the current design, prioritise and identify actions to mitigate the risks. All the risk details are to be documented and revised at regular intervals. We can prioritise the risks by using risk magnitude indicator as criteria. The list of risks can base the proposal of new Spikes, Technical Enablers or ADR's.

Task: 02 - Assess NFRs
Understand and identify spikes/activities that are required to assess the Identified NFRs (E.g , Jmeter configuration for Performance testing).

Task: 03 - Propose Spikes / Technical Enablers /ADR's 
Identify and document the spikes / technical enablers that are required to finalise and meet the functional/non functional requirements of the application.

Activity: E6 - Manage Product Platform
Identify, measure and track Risks and NFR's.

Inputs
Cloud Architecture
Business Architecture
Technical Architecture
Epic List
Enterprise Architecture Inputs:
SVRO (formerly OTIC)
Solution Intent Architecture Repository
Example: Advanced Home Delivery (OTIC 2024)
GOOD EXAMPLE: Project Eagle - Carelon Behavioral Health Crisis Safety Platform CSP
BCM
OTIC 2024 - BCM Mapping
Business Architecture (Ireland)
Domain Architecture
BCM Home (High Level Functions)
DOTS Patterns
Technical Architecture
Elevance Standards Governance (ESG)
ESG Home
Outputs
CI/CD Pipeline 
Product Dashboards
Devops Playbooks
Test Automation Script
Devops' IAC artifacts
Task: 01 - Support CI / CD
Support engineering teams by assessing and proposing enhancements in CI / CD processes and pipelines.

Task: 02 - Support and Coordinate Observability
Plan and execute the observability enablement of the application by coordinating with Devops and proposing Technical Enablers and ADR's, playbooks and automation scripts. 

Task: 03 - Coordinate with Devops
Collaborate with Devops by planing and execute the application compliance to platform by proposing Technical Enablers, ADR's, playbooks and automation scripts.

Task: 04 - Support Test Automation
Collaborate with QA and Devops towards the establishment of Test Automation by proposing Technical Enablers, ADR's, playbooks and automation scripts.

Task: 05 - Optimise Product Resources
Monitor application, find bottlenecks, resource optimisation opportunities and propose enhancements in Cloud infrastructure configurations and application enhancements by proposing Technical Enablers and ADR's.

Task: 06 - Support Performance Engineering
Collaborate with Performance Engineering, by providing application advice, proposing enhancements in Cloud Infrastructure and Application through Technical Enablers and ADR's/

Task: 07 - Propose Spikes / Technical Enablers /ADR's 
Identify and document the spikes / technical enablers that are required to finalise and meet the functional/non functional requirements of the application.

Task: 08 - Tag and Register Application in Platform Management Repos
We define the tags and application codification in Enterprise platform repositories. Those codes will be used to identify the new application on Cloud Platforms and Observability Platforms / SaaS like DD and Splunk.

Task: 09 - Monitor and Manage Application Vulnerabilities
We guarantee that the application is submitted to Static Analysis tools for static code analysis and guarantee that all vulnerabilities are addressed.

Activity: E7 - Manage Product Security and Compliance
We submit the Application on several different Security and compliance departments within Elevance. We should produce and collect evidences that the Application is being developed according Enterprise Standards (DOTS, RAPL, ESG...) and submit the evidences to the specific compliance department or directly on ESG.

Original Process as defined in the PI Platform - Security Review Process (Miro board link here). Other platforms or products may not have the full process documented.

Inputs
Module (Service) Canvas
Application Architecture
Overall Solution  Architecture
Data Architecture
Outputs
Security Architecture Report
Data Governance Report
Data Encryption Report
Disaster Recovery Report
IAM Lifecycle Management Report
Change Management Report
SDLC Assessment Report
Process
Task: 01 - Submit Security Architect Report
Gather the following documents for review:

Overall System design and architecture
Network Diagram
Components diagram
Deployment diagram
Submit the report to service now: https://miro.com/app/board/uXjVKUH6vww=/?moveToWidget=3458764586484716857&cot=14

Task: 02 - Submit Data Governance Report
Gather the following documents for review:

Data model / Data Dictionary

Data Classification

Replication pattern

Data Access Patterns - Onshore / Offshore

Submit the report to Data Governance Security:  DL-Carelon_DataGovernance_Security@carelon.com

Task:  03 - Submit Data Encryption Report
Gather the following documents for review:

Data Flow diagram,
Data Encryption patterns - data in transit and rest
Submit the report to service now: https://miro.com/app/board/uXjVKUH6vww=/?moveToWidget=3458764586484716549&cot=14

Task:  04 - Submit Disaster Recovery Report
Gather the following documents for review:

Disaster Recovery Plan

Deployment diagram

DR Validation plan

Submit the report to service now: https://miro.com/app/board/uXjVKUH6vww=/?moveToWidget=3458764587432185048&cot=14

Task: 05 -  Submit User Lifecycle Management Report
Gather the following documents for review:

IDP Integration - SSO login

User management 

AD Groups - SailPoint Integration 

User Roles Management

Flow Diagrams

Submit the report to service now:

Task:  06 - Submit AI Report
Gather the following documents for review:

RAI Impact Assessment

Solution Overview

Submit the report to service now:

Task: 07 - Submit Application Security Report
Gather the following documents for review:

Onboard resources to static code scans
Integrate with CI-CD pipelines
MPT Testing
Submit the report to service now: https://miro.com/app/board/uXjVKUH6vww=/?moveToWidget=3458764586484988103&cot=14

Task:  08 - Submit Change Management Report
Gather the following documents for review:

Dependencies
AppSec Approval
Submit the report to service now: https://miro.com/app/board/uXjVKUH6vww=/?moveToWidget=3458764586484988103&cot=14

Task:  09 - Submit SDLC Report
Gather the following documents for review:

Submit the report to service now:

Phase: Feature Solution Intent Process
In the Feature Solution Intent Elaboration phase we have following goals:

Incrementally build the application driven by Features and providing Archicte
Focus on practices for analysing designing and implementing the application functional (features) and non-functional requirements
Manage Technical Risks and build a mitigation plan
Enforce Modularisation
Application architecture
Data Architecture
Activity: F1 - Design Feature Solution Intent
WIP...

Inputs
Feature / Issue
Application Architecture
Data Architecture
Overal Solution Architecture
Cloud Architecture
Epic List
Outputs
Feature Solution Design Document

Module/Service canvas

Application Architecture
Overall Solution Architecture
Data Architecture
Proposed Spikes / Technical Enabler / ADR's
Guidelines
TOGAF 10 - (Requires Open Group registration)
Guideline - Modularization and Business Capability Allocation
Process
Task: 01 - Run Impact Analysis
We analyse the possible effects of this feature on implemented features, up next features and overall architecture and take it into consideration when providing the new solution.

Task: 02 - Collaborate with PO on  System Use Cases / A/C
Collaborate with PO on the bridging of possible gaps in the System Use Cases and A/Cs as specified in features

Task: 03 - Collaborate with Application Architect / Tech Leaders
Provide the High Level Design of the current feature, if required in the case of a not covered Use Case. Collaborate with Application Architect or Tech Leaders in defining the Low Level Designs for the feature.

Task: 04 - Collaborate with UX Designers
Collaborate with UX Designers in addressing Application Flows. 

Task: 05 - Address NFR's
Guarantee that provided solution covers Non-functional Requirements like usability, reliability, performance and security.

Task: 06 - Verify Adherence to Enterprise Standards
Guarantee that provided solution is is provided in conformity with Elevance standards

Task: 07 - Review and Sign Off Application Architecture
Review the Application Architecture or Low Level Design authored by Application Architect or Technical Leaders.

Task: 08 - Propose Spikes / Technical Enablers /ADR's 
Identify and document the spikes / technical enablers that are required to finalise and meet the functional/non functional requirements of the application.

Activity: F2 - Manage Stakeholders
As defined in Solution Intent Elaboration process.

Activity: F3 - Manage Architecture Decisions
As defined in Solution Intent Elaboration process.

Activity: F4 - Risks and NFR's
As defined in Solution Intent Elaboration process.

Activity: F5 - Manage Product Platform
As defined in Solution Intent Elaboration process.

Activity: F6 - Submit Application for Security Review
As defined in Solution Intent Elaboration process.

References
EA @CGS Ireland

IT-CMF (EAM)
Elevance Process / Solution

Elevance SLDC
Software Development Life Cycle
Agile Framework Community Library Home
Elevance Large Programas, Soution ayer PODs
Enterprise Architecture and Governance
TOGAF 10 - (Requires Open Group registration)
Enterprise Architecture - Solution Intent Architecture Repository
SAFE - Solution Train

Solution Train: https://scaledagileframework.com/solution-train/
SAFE Essential: https://scaledagileframework.com/#essential
SAFE Large Solution: https://scaledagileframework.com/#largesolution
BCM

BCM Ireland
Business Architecture (Ireland)
BCM 2.0 EXCEL
Domain / BCM
Elevance Confluence - Domain Architecture
https://collaborate.wellpoint.com/sites/entarch/SitePages/BCMHome.aspx
DOTS

Technical Architecture
External References

The DDD Way Towards Screaming Design — Part I: Strategic Patterns
Business architecture description: capability map vs. process map
O'Reilly Learning - Strategic Monoliths and Microservices: Driving Innovation Using Purposeful Architecture
AWS Prescriptive Guidance - ADR Process
TOGAF 10 - (Requires Open Group registration)
Twelve Factor Application
AWS Well-Architected Framework
Pattern anguage for microservices
Azure - Cloud Design Patterns
EIP - Enterprise Integration Patterns
Kafka - Event Streaming Patterns
