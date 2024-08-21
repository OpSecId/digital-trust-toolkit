---
layout: default
title: Equitable Origin Governance Framework
parent: Applications
---

## Equitable Origin Governance Framework

# 1. Primary Document

## 1.1. Introduction 

This document articulates the governance framework for Equitable Origin as an issuer of a verifiable credential [(layer four application of the Trust Over IP Foundation (ToIP) model)](https://www.trustoverip.org/wp-content/toip-model/).

The development of this documentation follows the governance framework created by the [Trust over IP Foundation (ToIP)](https://trustoverip.org/) [Governance Metamodel Specification](https://trustoverip.org/wp-content/uploads/ToIP-Governance-Metamodel-Specification-V1.0-2022-12-21.pdf) created by the [Governance Stack Working Group (GSWG)](https://wiki.trustoverip.org/display/HOME/Governance+Stack+Working+Group).

These materials are made available under and are subject to the [Creative Commons Attribution 4.0 International license](http://creativecommons.org/licenses/by/4.0/legalcode).

THESE MATERIALS ARE PROVIDED “AS IS.” The Trust Over IP Foundation, established as the Joint Development Foundation Projects, LLC, Trust Over IP Foundation Series ("ToIP"), and its members and contributors (each of ToIP, its members and contributors, a "ToIP Party") expressly disclaim any warranties (express, implied, or otherwise), including implied warranties of merchantability, non-infringement, fitness for a particular purpose, or title, related to the materials. The entire risk as to implementing or otherwise using the materials is assumed by the implementer and user. 

IN NO EVENT WILL ANY ToIP PARTY BE LIABLE TO ANY OTHER PARTY FOR LOST PROFITS OR ANY FORM OF INDIRECT, SPECIAL, INCIDENTAL, OR CONSEQUENTIAL DAMAGES OF ANY CHARACTER FROM ANY CAUSES OF ACTION OF ANY KIND WITH RESPECT TO THESE MATERIALS, ANY DELIVERABLE OR THE ToIP GOVERNING AGREEMENT, WHETHER BASED ON BREACH OF CONTRACT, TORT (INCLUDING NEGLIGENCE), OR OTHERWISE, AND WHETHER OR NOT THE OTHER PARTY HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

***Acknowledgements***

This governance framework includes structural elements from the Trust over IP Metamodel that were developed by Governance Stack Working Group of the Trust over IP Foundation, the eSSIF Lab Glossary and Mental Models, were contributed to the Trust Over IP Foundation under the CC BY-SA 4.0 license.  There have also been contributions from the Concepts & Terminology Working Group at ToIP, the Human Experience Working Group at ToIP and the Ecosystem Foundry Working Group at ToIP, the work of the Governance Framework Working Group at Sovrin Foundation is also acknowledged in providing support.

## 1.2. Terminology and Notation 

[Glossary - General Trust Over IP Terms](https://trustoverip.github.io/toip/glossary)

**Requirements** include any combination of Machine-Testable Requirements and Human-Auditable Requirements. Unless otherwise stated, all Requirements MUST be expressed as defined in [RFC 2119](https://www.rfc-editor.org/rfc/rfc2119).

- Mandates are Requirements that use a MUST, MUST NOT, SHALL, SHALL NOT or REQUIRED keyword.
- Recommendations are Requirements that use a SHOULD, SHOULD NOT, or RECOMMENDED keyword.
- Options are Requirements that use a MAY or OPTIONAL keyword.

**Machine-Testable Requirements** are those with which compliance can be verified using an automated test suite and appropriate scripting or testing software.

**Rules** are Machine-Testable Requirements that are written in a Machine-Readable language and can be processed by a Rules Engine. They are expressed in a structured rules language as specified by the Governance Framework.

**Human-Auditable Requirements** are those with which compliance can only be verified by an audit of people, processes, and procedures.

**Policies** are Human-Auditable Requirements written using standard conformance terminology. The Policies used in the Governance Framework will use the standard terminology detailed in RFC 2119 keywords. Note that all RFC 2119 keywords have weight from an auditing perspective. An implementer MUST explain why a SHOULD or RECOMMENDED requirement was not implemented and SHOULD explain why a MAY requirement was implemented.

**Specifications** are documents containing any combination of Machine-Testable Requirements and Human-Auditable Requirements needed to produce technical interoperability.

## 1.3. Localization
The standard language for this Governance Framework (GF) is American English.

## 1.4. Governing Authority 

[Equitable Origin](https://www.equitableorigin.org/) is the Governing Authority responsible for this Governance Framework (GF). The contact information for Equitable Origin during the pilot phase of development is:

* 	**Name:** Soledad Mills
* 	**Title:** Chief Executive Officer
* 	**Organization:** Equitable Origin
* 	**Email:** [smills@equitableorigin.org](mailto:smills@equitableorigin.org)

## 1.5. Administering Authority

[Energy and Mines Digital Trust (EMDT)](https://digital.gov.bc.ca/case-studies/emdt) is the Administering Authority on behalf of PricewaterhouseCoopers (PwC) during the pilot phase of development.

The contact information for EMDT is:
* 	**Name:** Kyle Robinson 
* 	**Title:** Senior Strategic Advisor, Digital Trust Ecosystems
* 	**Organization:** Briartech Consulting Inc.
* 	**Email:** [kyle.robinson@briartech.ca](mailto:kyle.robinson@briartech.ca)

## 1.6. Purpose

The purpose of this governance framework is to describe the rules/policies/procedures for verifiable credential exchanges involving Equitable Origin Services Inc. with the open global community. The purpose of the rules is to enable all actors to understand agreed upon standards, terminology and processes that allow the community to interact with Equitable Origin in a trusted manner. This will help determine a governing framework and operating model for a global ecosystem that identifies how credentials can be issued, held, and verified. 

## 1.7. Scope 

Equitable Origin is a participant in an open ecosystem and the focus of this framework is to describe the process Equitable Origin uses for digital exchanges on Indy networks.

## 1.8. Objectives

_This section states the high-level outcomes desired by the trust community through its adoption of the GF._

1. SHOULD specify tangible, achievable results (e.g. SMART criteria and Fit-for-Purpose criteria).
2. MUST only contain outcomes over which the GF has the authority and mechanisms to achieve within its
scope.
3. MUST be consistent with the principles of the GF (below).


## 1.9. Principles 

_TBD - These are standard principals from ToIP, to be edited by Equitable Origin_

1)	Sustainability
2)	Stewardship 
3)	Public good
4)	Transparency
5)	Citizen Engagement
6)	Digital Sovereignty
7)	Security
8)	Confidence
9)	Synchronization

## 1.10. General Requirements
TBD

## 1.11. Revisions

Version 1.0

_TBD - How and when Equitable Origin would change governance framework_

## 1.12. Extensions

There are no extensions to this Governance Framework.

## 1.13. Schedule of Controlled Documents

TBD

# 2. Controlled Documents

## 2.1. Glossary


## 2.2. Risk Assessment

TBD

## 2.3. Trust Assurance and Certification

TBD

## 2.4. Governance Requirements

[Equitable Origin Governance](https://www.equitableorigin.org/about-us/overview/governance/)

## 2.5. Business Requirements

## 2.5.1. Establishment of Connection

1. Equitable Origin MUST send an invitation to the other business entity via email to initiate the exchange of information. 
2. The receiving party MUST accept invitation in order to establish a secure connection.

## 2.5.2. Issuance of EO100 Credential

1. Using the established connection, Equitable Origin MUST receive a credential request from the business entity. 
2. Continuing from step 1, the business entity MUST provide all of the following attributes in the credential request as outlined in the [EO100 Credential Governance](https://github.com/bcgov/bc-vcpedia/blob/main/credentials/credential-EO100.md#261-schema-definition):

certificate_issuer,  certificate_number, operator, ucp_name, ucp_location_city, ucp_location_province, ucp_location_country, certification_date, expiration_date, certification_standard, assessor_name 

3. Equitable Origin MUST receive and review the request
4. Any clarification questions MAY be asked via the secure messaging function 
5. Once all data is entered and correct, Equitable Origin SHALL offer the credential to the business entity
6. Business entity MAY choose to accept or negotiate the credential to request changes

## 2.6. Technical Requirements

*MUST have an Aries compatible business wallet.*

## 2.7. Information Trust Requirements

Equitable Origin's [Privacy Policy](https://www.equitableorigin.org/privacy-policy/)

## 2.8. Inclusion, Equitability and Accessibility Requirement

TBD

## 2.9. Legal Agreements

TBD

# End of Document












 
