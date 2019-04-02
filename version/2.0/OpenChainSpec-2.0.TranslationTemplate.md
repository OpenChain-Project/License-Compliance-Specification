#                 OpenChain Specification

Version 2.0

_Establishing trust in the Open Source from which Software Solutions are built_

**Contents**

 - 1)Introduction
 - 2)Definitions
 - 3)Requirements
	 - 1.0 Program Foundation
	 - 2.0 Relevant Tasks Defined and Supported
	 - 3.0 Open Source Content Review and Approval
	 - 4.0 Compliance Artifact Creation and Delivery
	 - 5.0 Understanding Open Source Community Engagements       
	 - 6.0 Adherence to the Specification Requirements
- Appendix I: Language Translations

This is an official translation from the OpenChain Project. It has been translated from the original English text. In the event there is confusion between this translation and the English version, The English text shall take precedence.

[_Translation of the above English text goes here_]




Copyright © 2016-2019 Linux Foundation. This document is licensed under the Creative Commons Attribution 4.0 International (CC-BY-4.0) license. A copy of the license can be found at [https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/).

## 1) Introduction

This specification defines the key requirements of a quality open source license compliance program. The objective is to provide a benchmark that builds trust between organizations exchanging software solutions comprised of open source software. Specification conformance provides assurance that a Program has been designed to produce the required Compliance Artifacts (_i.e._, legal notices, source code and so forth) for each software solution. The OpenChain Specification focuses on the &quot;what&quot; and &quot;why&quot; aspects of a Program rather than the &quot;how&quot; and &quot;when&quot;. This ensures flexibility for different organizations of different sizes in different markets to choose specific policy and process content that fits their size, goals and scope. For instance, an OpenChain Conformant Program may address a single product line or the entire organization.

This introduction provides the context for all potential users. Section 2 defines key terms used throughout the Specification. Section 3 defines the requirements that a Program must satisfy to achieve conformance. A requirement consists of one or more Verification Materials (_i.e._, records) that must be produced to satisfy the requirement. Verification Materials are not required to be made public, though an organization may choose to provide them to others, potentially under a Non-Disclosure Agreement (NDA).

The Specification is developed as an open initiative with feedback received from over 150 contributors. Insight into its historical development can be obtained by reviewing the Specification [mailing list](https://lists.linuxfoundation.org/mailman/listinfo/openchain-spec) and [Frequently Asked Questions (FAQs)](https://wiki.linuxfoundation.org/openchain/specification-questions-and-answers).





## 2) Definitions

**&quot;Compliance Artifacts&quot; -** a collection of artifacts that represent the output of the Program for the Supplied Software. The collection may include (but is not limited to) one or more of the following: source code, attribution notices, copyright notices, copy of licenses, modification notifications, written offers, Open Source component bill of materials, and SPDX documents.

**&quot;Identified Licenses&quot;** - a set of Open Source Software licenses identified as a result of following an appropriate method of identifying Open Source components from which the Supplied Software is comprised.

**&quot;OpenChain Conformant**&quot; - a Program that satisfies all the requirements of this specification.

**&quot;Open Source&quot;**  - software subject to one or more licenses that meet the Open Source Definition published by the Open Source Initiative (OpenSource.org) or the Free Software Definition (published by the Free Software Foundation) or similar license.

&quot; **Program**&quot; – the set of policies, processes and personnel that manage an organization&#39;s Open Source license compliance activities.

**&quot;Software Staff&quot;** - any organization employee or contractor that defines, contributes to or has responsibility for preparing Supplied Software. Depending on the organization, that may include (but is not limited to) software developers, release engineers, quality engineers, product marketing and product management.

**&quot;SPDX&quot;** - the format standard created by the Linux Foundation&#39;s SPDX (Software Package Data Exchange) Working Group for exchanging license and copyright information for a given software package. A description of the SPDX specification can be found at www.spdx.org.

**&quot;Supplied Software&quot;** - software that an organization distributes to third parties (_e.g._, other organizations or individuals).

**&quot;Verification Materials&quot;** -materials that demonstrate that a given requirement is satisfied.



## 3) Requirements

### 1.0 Program Foundation

####  1. 1 Policy

**A written Open Source policy exists that governs Open Source license compliance of the Supplied Software. The policy must be internally communicated.**

##### Verification Material(s):

- 1.1.1 A documented Open Source policy.
- 1.1.2 A documented procedure that makes Software Staff aware of the existence of the Open Source policy (_e.g._, via training, internal wiki, or other practical communication method).

##### Rationale :
To ensure steps are taken to create, record and make Software Staff aware of the existence of an Open Source policy. Although no requirements are provided here on what should be included in the policy, other sections may impose requirements on the policy.



#### 1.2 Competence

**The organization shall:**

- **Identify the roles and the corresponding responsibilities of those roles that affects the performance and effectiveness of the Program;**
- **Determine the necessary competence of person(s) fulfilling each role**
- **Ensure that these persons are competent on the basis of appropriate education, training, and/or experience;**
- **Where applicable, take actions to acquire the necessary competence; and**
- **Retain appropriate documented information as evidence of competence.**

##### Verification Material(s):

- 1.2.1 A documented list of roles with corresponding responsibilities for the different participants in the Program.
- 1.2.2 A document that identifies the competencies for each role.
- 1.2.3 Documented evidence of assessed competence for each Program participant.

##### Rationale :
To ensure that the identified participants fulfilling Program roles have obtained a sufficient level of competence for their respective roles and responsibilities.



#### 1.3         Awareness

**The organization shall ensure that Program participants are aware of:**

**a) The Open Source policy;**
**b) Relevant Open Source objectives;**
**c) Their contribution to the effectiveness of the Program; and**
**d) The implications of not following the Program&#39;s requirements.**

##### Verification Material(s):

- 1.3.1 Documented evidence of assessed awareness for each Program personnel including the Program&#39;s objectives, ones contribution within the Program, and implications of Program non-conformance.

##### Rationale :
To ensure Program personnel have obtained a sufficient level of awareness for their respective roles and responsibilities within the Program.



#### 1.4        Program Scope

**Different Programs may be governed by different levels of scope. For example, a program could govern a single product line, an entire department or an entire organization. The scope designation needs to be declared for each Program.**

##### Verification Material(s):

- 1.4.1 A written statement that clearly defines the scope and limits of the Program.

##### Rationale :
To provide the flexibility to construct a Program that best fits the scope of an organization&#39;s needs. Some organizations could choose to maintain a Program for a specific product line while others could implement a Program to govern the Supplied Software of the entire organization.



#### 1.5        License Obligations

**A process exists for reviewing the Identified Licenses to determine the obligations, restrictions and rights granted by each license.**

##### Verification Material(s):

- 1.5.1 A documented procedure to review and document the obligations, restrictions and rights granted by each Identified License.

##### Rationale :

To ensure a process exists for reviewing and identifying the license obligations for each Identified License for the various use cases an organization may encounter (as defined in requirement 3.2).

### 2.0 Relevant Tasks Defined and Supported

#### 2.1         Access

**Maintain a process to effectively respond to external Open Source inquiries. Publicly identify a means by which a third party can make an Open Source compliance inquiry.**

##### Verification Material(s):

- 2.1.1 Publicly visible method that allows any third party to make an Open Source license compliance inquiry (_e.g._, via a published contact email address, or the Linux Foundation&#39;s Open Compliance Directory).

- 2.1.2 An internal documented procedure for responding to third party Open Source license compliance inquiries.

##### Rationale :
To ensure there is a reasonable way for third parties to contact the organization with regard to Open Source compliance inquiries and that the organization is prepared to effectively respond.



#### 2.2          Effectively Resourced

**Identify and Resource Program Task(s):**

- **Assign accountability to ensure the successful execution of Program tasks.**
- **Program tasks are sufficiently resourced:**
  - **Time to perform the tasks have been allocated; and**
  - **Adequate funding has been allocated.**
- **A process exists for reviewing and updating the policy and supporting tasks;**
- **Legal expertise pertaining to Open Source license compliance is accessible to those who may need such guidance; and**
- **A process exists for the resolution of Open Source license compliance issues.**

##### Verification Material(s):

- 2.2.1 Document with name of persons, group or function in Program role(s) identified.
- 2.2.2 The identified Program roles have been properly staffed and adequate funding provided.
- 2.2.3 Identification of legal expertise available to address Open Source license compliance matters which could be internal or external.
- 2.2.4 A documented procedure that assigns internal responsibilities for Open Source compliance.
- 2.2.5 A documented procedure for handling the review and remediation of non-compliant cases.

##### Rationale :

To ensure: i) Program responsibilities are effectively supported and resourced and ii) policies and supporting processes are regularly updated to accommodate changes in Open Source compliance best practices.

### 3.0 Open Source Content Review and Approval

#### 3.1       Bill of Materials

**A process exists for creating and managing a bill of materials that includes each Open Source component (and its Identified Licenses) from which the Supplied Software is comprised.**

##### Verification Material(s):

- 3.1.1 A documented procedure for identifying, tracking, reviewing, approving, and archiving information about the collection of Open Source components from which the Supplied Software is comprised.
- 3.1.2 Open Source component records for the Supplied Software that demonstrates the documented procedure was properly followed.

##### Rationale :

To ensure a process exists for creating and managing a Open Source component bill of materials used to construct the Supplied Software. A bill of materials is needed to support the systematic review and approval of each component&#39;s license terms to understand the obligations and restrictions as it applies to the distribution of the Supplied Software.



#### 3.2          License Compliance

**The Program must be capable of managing common Open Source license use cases encountered by Software Staff for Supplied Software, which may include the following use cases (note that the list is neither exhaustive, nor may all of the use cases apply):**

- **distributed in binary form;**
- **distributed in source form;**
- **integrated with other Open Source such that it may trigger copyleft obligations;**
- **contains modified Open Source;**
- **contains Open Source or other software under an incompatible license interacting with other components within the Supplied Software; and/or**
- **contains Open Source with attribution requirements.**

##### Verification Material(s):

- 3.2.1 A documented procedure for handling the common Open Source license use cases for the Open Source components of the Supplied Software.

##### Rationale :

To ensure the program is sufficiently robust to handle an organization&#39;s common Open Source license use cases.  That a procedure exists to support this activity and that the procedure is followed.

### 4.0 Compliance Artifact Creation and Delivery

#### 4.1        Compliance Artifacts

**A process exists for creating the set of Compliance Artifacts for the Supplied Software.**

##### Verification Material(s):

- 4.1.1 A documented procedure that documents the process under which the Compliance Artifacts are prepared and distributed with the Supplied Software as required by the Identified Licenses.

- 4.1.2 A documented procedure for archiving copies of the Compliance Artifacts of the Supplied Software - where the archive is planned to exist for a reasonable period of time1 since the last offer of the Supplied Software; or as required by the Identified Licenses (whichever is longer). Records exist that demonstrate the procedure has been properly followed.

##### Rationale :

To ensure reasonable commercial efforts have been instituted in the preparation of the Compliance Artifacts that accompanies the Supplied Software, as required by the Identified Licenses.



### 5.0 Understanding Open Source Community Engagements

#### 5.1        Contributions

**If an organization permits contributions to Open Source projects then**

- **a written policy exists that governs contributions to Open Source projects;**
- **the policy must be internally communicated; and**
- **a process exists that implements the policy**

##### Verification Material(s):

If an organization permits contributions to Open Source projects then the following must exist:

- 5.1.1 a documented Open Source contribution policy;
- 5.1.2 a documented procedure that governs Open Source contributions; and
- 5.1.3 a documented procedure that makes all Software Staff aware of the existence of the Open Source contribution policy (_e.g._, via training, internal wiki, or other practical communication method).

##### Rationale :

When an organization permits Open Source contributions we want to ensure the organization has given reasonable consideration to developing and implementing a contribution policy.  The Open Source contribution policy can be made a part of the overall Open Source policy or be its own separate policy.


### 6.0 Adherence to the Specification Requirements

#### 6.1        Conformance

**In order for a Program to be deemed OpenChain Conformant, the organization must affirm that the program satisfies the requirements presented in this specification.**

##### Verification Material(s):
- 6.1.1 A document affirming the Program specified in requirement 1.4 satisfies all the requirements of this specification.

##### Rationale :

To ensure that if an organization declares that it has a program that is OpenChain Conforming, that such program has met all the requirements of this specification. The mere meeting of a subset of these requirements would not be considered sufficient.



#### 6.2        Duration

**A Program that is OpenChain Conformant with this version of the specification will last 18 months from the date conformance validation was obtained. The conformance validation registration procedure can be found on the OpenChain project&#39;s website.**

##### Verification Material(s):

- 6.2.1 A document affirming the Program meets all the requirements of this version of the specification (version 2.0), within the past 18 months of obtaining conformance validation.

##### Rationale :

It is important for the organization to remain current with the specification if that organization wants to assert program conformance over time. This requirement ensures that the program&#39;s supporting processes and controls do not erode if an organization continues to assert program conformance over time.

## Appendix I: Language Translations

To facilitate global adoption we welcome efforts to translate the specification into different languages. Because OpenChain functions as an open source project translations are driven by those willing to contribute their time and expertise to perform translations under the terms of the CC-BY-4.0 license and the project&#39;s translation policy.  The details of the policy and available translations can be found on the OpenChain project [specification webpage](https://wiki.linuxfoundation.org/openchain/spec-translations).
