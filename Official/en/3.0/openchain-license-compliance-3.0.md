## OpenChain Specification - DRAFT

## Version 3.0

This Specification is designed to provide an interation to ISO/IEC 5230:2020. It is currently a draft and is not ready for deployment.

## Contents

### Introduction

### 1 - Scope

### 2 - Terms and definitions

### 3 - Requirements

- 3.1 - Program foundation
- - 3.1.1 - Policy
- - 3.1.2 - Competence
- - 3.1.3 - Awareness
- - 3.1.4 - Program scope
- - 3.1.5 - License obligations

- 3.2 - Relevant tasks defined and supported
- - 3.2.1 - Access
- - 3.2.2 - Effectively 

- 3.3 - Open source content review and approval
- - 3.3.1 - Bill of materials
- - 3.3.2 - License compliance

- 3.4 - Compliance artifact creation and delivery
- - 3.4.1 - Compliance artifacts

- 3.5 - Understanding open source community engagements
- - 3.5.1 - Contributions

- 3.6 - Adherence to the specification requirements
- - 3.6.1 - Conformance
- - 3.6.2 - Duration

# Introduction

This document defines the key requirements of a quality open source license compliance program. The objective is to provide a benchmark that builds trust between organizations exchanging software solutions comprised of open source software. Specification conformance provides assurance that a program has been designed to produce the required compliance artifacts (i.e., legal notices, source code and so forth) for each software solution. This document focuses on the "what" and "why" aspects of a program rather than the "how" and "when". This ensures flexibility for different organizations of different sizes in different markets to choose specific policy and process content that fits their size, goals and scope. For instance, an OpenChain conformant program may address a single product line or the entire organization.

This introduction provides the context for all potential users. Clause 2 defines key terms used throughout this document. Clause 3 defines the requirements that a program must satisfy to achieve conformance. A requirement consists of one or more verification materials (i.e., records) that must be produced to satisfy the requirement. Verification materials are not required to be made public, though an organization may choose to provide them to others, potentially under a Non-Disclosure Agreement (NDA).

This document was developed as an open initiative with feedback received from more than 200 contributors. Insight into its historical development can be obtained by reviewing the Specification [mailing list](https://lists.openchainproject.org/g/specification) and [Frequently Asked Questions (FAQs)](https://www.openchainproject.org/resources/faq).

This specification is licensed under [Creative Commons Attribution License 4.0](https://creativecommons.org/licenses/by/4.0/) (CC-BY-4.0).

## Information technology — OpenChain Specification

## 1 - Scope

This document specifies the key requirements of a quality open source license compliance program in order to provide a benchmark that builds trust between organizations exchanging software solutions comprised of open source software.

## 2 - Terms and definitions

For the purposes of this document, the following terms and definitions apply.

### 2.1 - compliance artifacts

a collection of artifacts that represent the output of a compliance program and accompany the supplied software

Note: The collection may include (but is not limited to) one or more of the following: attribution notices, source code, build and install scripts, copy of licenses, copyright notices, modification notifications, written offers, open source component bill of materials, and SPDX documents.

### 2.2 - identified licenses

a set of open source software licenses identified as a result of following an appropriate method of identifying open source components from which the supplied software is comprised

### 2.3 - OpenChain conformant

a program that satisfies all the requirements of this document

## 2.4 - open source

software subject to one or more licenses that meet the Open Source Definition published by the Open Source Initiative (see [opensource.org/osd](https://opensource.org/osd)) or the Free Software Definition published by the Free Software Foundation (see [gnu.org/philosophy/free-sw.html](https://www.gnu.org/philosophy/free-sw.html)) or similar license

## 2.5 - program

the set of policies, processes and personnel that comprise an organization's open source license compliance activities

## 2.6 - program participants

any organization employee or contractor that defines, contributes to or has responsibility for preparing supplied software

Note: Depending on the organization, that may include (but is not limited to) software developers, release engineers, quality engineers, product marketing and product management.

## 2.7 - SPDX

the format standard created by the Linux Foundation's SPDX (Software Package Data Exchange) Working Group for exchanging bill of materials for a given software package, including associated license and copyright information (see [spdx.org](https://spdx.org/))

## 2.8 - supplied software

software that an organization distributes to third parties (e.g., other organizations or individuals)

## 2.9 - verification materials

materials that demonstrate that a given requirement of the specification is satisfied

ISO and IEC maintain terminological databases for use in standardization at the following addresses:

— ISO Online browsing platform: available at [https://www.iso.org/obp](https://www.iso.org/obp)

— IEC Electropedia: available at [http://www.electropedia.org/](http://www.electropedia.org/)

# 3 - Requirements

## 3.1 - Program foundation

### 3.1.1 - Policy

A written open source policy shall exist that governs open source license compliance of the supplied software. The policy shall be internally communicated.

#### Verification material(s):

- 3.1.1.1 - A documented open source policy.
- 3.1.1.2 - A documented procedure that makes program participants aware of the existence of the open source policy (e.g., via training, internal wiki, or other practical communication method).

#### Rationale:

To ensure steps are taken to create, record and make program participants aware of the existence of an open source policy. Although no requirements are provided here on what should be included in the policy, other sections may impose requirements on the policy.

### 3.1.2 - Competence

The organization shall

- Identify the roles and the corresponding responsibilities of those roles that affects the performance and effectiveness of the program;
- Determine the necessary competence of program participants fulfilling each role
- Ensure that program participants are competent on the basis of appropriate education, training, and/or experience;
- Where applicable, take actions to acquire the necessary competence; and
- Retain appropriate documented information as evidence of competence.

#### Verification material(s):

- 3.1.2.1 - A documented list of roles with corresponding responsibilities for the different participants in the program.
- 3.1.2.2 - A document that identifies the competencies for each role.
- 3.1.2.3 - Documented evidence of assessed competence for each program participant.

#### Rationale:

Ensure that the program participants have obtained a sufficient level of competence for their respective roles and responsibilities.

### 3.1.3 - Awareness

The organization shall ensure that the program participants are aware of:

- The open source policy;
- Relevant open source objectives;
- Their contribution to the effectiveness of the program; and
- The implications of not following the Program's requirements.

#### Verification material(s):

- 3.1.3.1 - Documented evidence of assessed awareness for the program participants - which should include the program's objectives, one's contribution within the program, and implications of program non-conformance.

#### Rationale:

To ensure the program participants have obtained a sufficient level of awareness for their respective roles and responsibilities within the program.

### 3.1.4 - Program scope

Different programs may be governed by different levels of scope. For example, a program could govern a single product line, an entire department or an entire organization. The scope designation needs to be declared for each program.

#### Verification material(s):

- 3.1.4.1 - A written statement that clearly defines the scope and limits of the program.

#### Rationale:

To provide the flexibility to construct a program that best fits the scope of an organization's needs. Some organizations could choose to maintain a program for a specific product line while others could implement a program to govern the supplied software of the entire organization.

### 3.1.5 - License obligations

A process shall exist for reviewing the identified licenses to determine the obligations, restrictions and rights granted by each license.

#### Verification material(s):

- 3.1.5.1 - A documented procedure to review and document the obligations, restrictions and rights granted by each identified license.

#### Rationale:

To ensure a process exists for reviewing and identifying the license obligations for each identified license for the various use cases an organization may encounter (as defined in §3.3.2).

## 3.2 - Relevant tasks defined and supported

### 3.2.1 - Access

Maintain a process to effectively respond to external open source inquiries. Publicly identify a means by which a third party can make an open source compliance inquiry.

#### Verification material(s):

- 3.2.1.1 - Publicly visible method that allows any third party to make an open source license compliance inquiry (e.g., via a published contact email address, or the Linux Foundation's Open Compliance Directory).
- 3.2.1.2 - An internal documented procedure for responding to third party open source license compliance inquiries.

#### Rationale:

To ensure there is a reasonable way for third parties to contact the organization with regard to open source compliance inquiries and that the organization is prepared to effectively respond.

### 3.2.2 - Effectively resourced

Identify and Resource Program Task(s):

- Assign accountability to ensure the successful execution of program tasks.
- Program tasks are sufficiently resourced:
  - Time to perform the tasks have been allocated; and
  - Adequate funding has been allocated.
- A process exists for reviewing and updating the policy and supporting tasks;
- Legal expertise pertaining to open source license compliance is accessible to those who may need such guidance; and
- A process exists for the resolution of open source license compliance issues.

#### Verification material(s):

- 3.2.2.1 - Document with name of persons, group or function in program role(s) identified.
- 3.2.2.2 - The identified program roles have been properly staffed and adequate funding provided.
- 3.2.2.3 - Identification of legal expertise available to address open source license compliance matters which could be internal or external.
- 3.2.2.4 - A documented procedure that assigns internal responsibilities for open source compliance.
- 3.2.2.5 - A documented procedure for handling the review and remediation of non-compliant cases.

#### Rationale:

To ensure: i) program responsibilities are effectively supported and resourced and ii) policies and supporting processes are regularly updated to accommodate changes in open source compliance best practices.

## 3.3 - Open source content review and approval

### 3.3.1 - Bill of materials

A process shall exist for creating and managing a bill of materials that includes each open source component (and its identified licenses) from which the supplied software is comprised.

#### Verification material(s):

- 3.3.1.1 - A documented procedure for identifying, tracking, reviewing, approving, and archiving information about the collection of open source components from which the supplied software is comprised.
- 3.3.1.2 - Open source component records for the supplied software that demonstrates the documented procedure was properly followed.

#### Rationale:

To ensure a process exists for creating and managing an open source component bill of materials used to construct the supplied software. A bill of materials is needed to support the systematic review and approval of each component's license terms to understand the obligations and restrictions as it applies to the distribution of the supplied software.

### 3.3.2 - License compliance

The program shall be capable of managing common open source license use cases encountered by program participants for supplied software, which may include the following use cases (note that the list is neither exhaustive, nor might all of the use cases apply):

- Distributed in binary form;
- Distributed in source form;
- Integrated with other open source such that it triggers additional licensing obligations;
- Contains modified open source;
- Contains open source or other software under an incompatible license interacting with other components within the Supplied Software; and/or
- Contains open source with attribution requirements.

#### Verification material(s):

- 3.3.2.1 - A documented procedure for handling the common open source license use cases for the open source components of the supplied software.

#### Rationale:

To ensure the program is sufficiently robust to handle an organization's common open source license use cases. That a procedure exists to support this activity and that the procedure is followed.

## 3.4 - Compliance artifact creation and delivery

### 3.4.1 - Compliance artifacts

A process shall exist for creating the set of compliance artifacts for the supplied software.

#### Verification material(s):

- 3.4.1.1 - A documented procedure that describes the process under which the compliance artifacts are prepared and distributed with the supplied software as required by the identified licenses.
- 3.4.1.2 - A documented procedure for archiving copies of the compliance artifacts of the supplied software - where the archive is planned to exist for a reasonable period of time (Determined by domain, legal jurisdiction and/or customer contracts) since the last offer of the supplied software; or as required by the identified licenses (whichever is longer). Records exist that demonstrate the procedure has been properly followed.

#### Rationale:

To ensure reasonable commercial efforts have been instituted in the preparation of the compliance artifacts that accompany the supplied software, as required by the identified licenses.

## 3.5 - Understanding open source community engagements

### 3.5.1 - Contributions

If an organization considers contributions to open source projects, then

- a written policy shall exist that governs contributions to open source projects;
- the policy shall be internally communicated; and
- a process shall exist that implements the policy

#### Verification material(s):

If an organization permits contributions to open source projects, then the following shall exist:

- 3.5.1.1 - A documented open source contribution policy;
- 3.5.1.2 - A documented procedure that governs open source contributions; and
- 3.5.1.3 - A documented procedure that makes all program participants aware of the existence of the open source contribution policy (e.g., via training, internal wiki, or other practical communication method).

#### Rationale:

When an organization permits open source contributions, the intent is that the organization has given reasonable consideration to developing and implementing a contribution policy. The open source contribution policy can be made a part of the overall open source policy or be its own separate policy.

## 3.6 - Adherence to the specification requirements

### 3.6.1 - Conformance

In order for a program to be deemed OpenChain conformant, the organization shall affirm that the program satisfies the requirements presented in this document.

#### Verification material(s):

- 3.6.1.1 - A document affirming the program specified in §3.1.4 satisfies all the requirements of this document.

#### Rationale:

To ensure that if an organization declares that it has a program that is OpenChain conforming, that such program has met all the requirements of this document. The mere meeting of a subset of these requirements is not considered sufficient.

### 3.6.2 - Duration

A program that is OpenChain conformant with this version of the specification shall last 18 months from the date conformance validation was obtained. The conformance validation registration procedure can be found on the OpenChain project's website.

#### Verification material(s):

- 3.6.2.1 - A document affirming the program meets all the requirements of this document, within the past 18 months of obtaining conformance validation.

#### Rationale:

It is important for a program to remain current with the specification if an organization wants to assert conformance over time. This requirement ensures that the program's supporting processes and controls do not erode if an organization continues to assert program conformance over time.
