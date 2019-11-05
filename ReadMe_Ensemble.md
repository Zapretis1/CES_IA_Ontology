# Ontology with Protégé
## Find your musical ensemble
Work of Zapretis1
***
MIRO facts for the Ensemble Ontology
==============

## Published 05 November 2019

**Editors**:

Zapretis1, CES IA

**Edit history:**

| Version | Date | Contributors | Changes |
|---|---|---|---|
| 0.1.0 | 21.09.2019 | Zapretis1 | First version |
| 1.0.0 | 30.09.2019 | Zapretis1 | Added properties |
| 1.1.0 | 05.11.2019 | Zapretis1 | Added classes - completed tutorial |
---

# Summary
This document contains the MIRO facts (Minimum Information for Reporting of an Ontology) for the ontology ***ensemble.owl*** created as part of the CES IA course at Telecom Evolution.

The ontology tackles the following decision making problem: **choose musical instruments to create an acoustic atmosphere**.

Depending on the ensemble one wants to listen to, on the acoustic climate one wants to create, the ontology helps choose the appropriate set of instruments to be combined.

---

## A. Basics

### A.1 Ontology name

|  | Specification |
|---|---|
| **Description:** | The full name of the ontology, including the acronym and the version number referred to in the report. |
| **Importance:** | MUST |
| **Label:** | Musical Ensemble (ME), v1.0.0 |
----

### A.2 Ontology owner

|  | Specification |
|---|---|
| **Description:** | The names, affiliations (where appropriate) and contact details of the person, people or consortium that manage the development of the ontology. |
| **Importance:** | MUST |
| **Label:** | Zapretis1, CES IA Telecom Evolution |
----

### A.3 Ontology license

|  | Specification |
|---|---|
| **Description:** | The licence which governs the permissions surrounding the ontology. |
| **Importance:** | MUST |
| **Label:** | GNU General Public License v3.0 |
----

### A.4 Ontology URL

|  | Specification |
|---|---|
| **Description:** | The web location where the ontology file is available. |
| **Importance:** | MUST |
| **Label:** | http://www.semanticweb.org/ontologies/ensemble.owl; https://github.com/Zapretis1/CES_IA_Ontology |
----

### A.5 Ontology repository

|  | Specification |
|---|---|
| **Description:** | The web location (URL) of the version control system where current and previous versions of the ontology can be found. |
| **Importance:** | MUST |
| **Label:** | https://github.com/Zapretis1/CES_IA_Ontology |
----

### A.6 Methodological framework

|  | Specification |
|---|---|
| **Description:** | A name or description of the steps taken to develop the ontology. This should describe the overall organisation of the ontology development process. |
| **Importance:** | MUST |
| **Label:** | The musical ensemble ontology describes various ensembles based on instrument classifcation, sounds and types of conducting means. The construction of the ontology was inspired by the Pizza Ontology described in the tutorial **A Practical Guide To Building OWL Ontologies Using Protégé 4 and CO-ODE Tools Edition 1.3** and was based on wikipedia resources regarding musical instruments classification.  https://en.wikipedia.org/wiki/Musical_ensemble  https://en.wikipedia.org/wiki/Musical_instrument_classification |
----

## B. Motivation

### B.1 Need

|  | Specification |
|---|---|
| **Description:** | Justification of why the ontology is required. |
| **Importance:** | MUST |
| **Label:** | The ontology tackles the following decision making problem: **choose musical instruments to create an acoustic atmosphere**. |
----

### B.2 Competition

|  | Specification |
|---|---|
| **Description:** | The names and citations for other ontology or ontologies in the same general area as the one being reported upon, together with a description on why the one being reported is needed instead or in addition to the others. |
| **Importance:** | MUST |
| **Label:** | The western musical instrument classification is often used in classical music. This ontology associates Hornbostel–Sachs classification and elements of physics-based organology presented by Steve Mann. https://en.wikipedia.org/wiki/Hornbostel%E2%80%93Sachs |
----

### B.3 Target audience

|  | Specification |
|---|---|
| **Description:** | The community or organisation performing some task or use for which the ontology was developed. |
| **Importance:** | MUST |
| **Label:** | Any music amateur who wants to create an acoustic atmosphere depending on their mood or entertainment requirements. |
----

## C. Scope, requirements, development community

### C.1 Scope and coverage

|  | Specification |
|---|---|
| **Description:** | The domain or field of interest for the ontology and the boundaries, granularity of representation and coverage of the ontology. State the requirements of the ontology, such as the competency questions it should satisfy. A visualisation or tabular representation is optional, but often helpful to illustrate the scope. |
| **Importance:** | MUST |
| **Label:** | From the  Hornbostel–Sachs classification. https://en.wikipedia.org/wiki/Hornbostel%E2%80%93Sachs |
----

### C.2 Development community

|  | Specification |
|---|---|
| **Description:** | The person, group of people or organisation that actually creates the content of the ontology. This is distinct from the Ontology Owner (above) that is concerned with the management of the ontology's development. |
| **Importance:** | MUST |
| **Label:** | Zapretis1, CES IA Telecom Evolution. |
----

### C.3 Communication

|  | Specification |
|---|---|
| **Description:** | Location, usually URL,  of the email list and/or the issue tracking systems used for development and managing feature requests for the ontology. |
| **Importance:** | MUST |
| **Label:** | https://github.com/Zapretis1/CES_IA_Ontology |
----

## D. Knowledge acquisition

### D.1 Knowledge acquisition methodology

|  | Specification |
|---|---|
| **Description:** | How the knowledge in the ontology was gathered, sorted, verified, etc. |
| **Importance:** | MUST |
| **Label:** | The knowledge was gathered using wikipedia resources https://en.wikipedia.org/wiki/Musical_instrument_classification and personal musical knowledge acquired during a 25-year musical training. |
----

### D.2 Source knowledge location

|  | Specification |
|---|---|
| **Description:** | The location of the source where the knowledge was gathered. |
| **Importance:** | SHOULD |
| **Label:** | As mentioned above for instruments and ensembles https://en.wikipedia.org/wiki/Musical_instrument_classification |
----

### D.3 Content selection

|  | Specification |
|---|---|
| **Description:** | The prioritisation of entities to be represented in the ontology and how that prioritisation was achieved. Some knowledge is more important or of greater priority to be in the ontology to support the requirements of that ontology. |
| **Importance:** | SHOULD |
| **Label:** | The instruments were grouped in undisputable categories based on physics organology. This allows an instrument to belong to one and only one category of EnsembleInstrument. For some instrument such as instruments with keyboards, there is a debate as to whether the should belong to a category according to the way they produce the sound (string, pipes, metal bars) or belong to a category of their own. The physics-based organology solves this issue. A subset of classical ensembles has been described in the ontology for the purpose of this work. The list is not exhaustive. ***EnsembleInstrument*** is equivalent to ***PizzaTopping*** of the pizza.wol ontology. Similarly ***EnsembleLeader*** is equivalent to ***PizzaBase*** and ***Ensemble*** is equivalent to ***Pizza***. |
----

## E. Ontology content

### E.1 Knowledge Representation language

|  | Specification |
|---|---|
| **Description:** | the knowledge representation language used and why it was used. For a language like OWL, indicate the OWL profile and expressivity. |
| **Importance:** | MUST |
| **Label:** | OWL version 2.0.0, DL profile. |
----

### E.2 Development environment

|  | Specification |
|---|---|
| **Description:** | The tool(s) used in developing the ontology. |
| **Importance:** | OPTIONAL |
| **Label:** | Protégé v5 |
----

### E.3 Ontology metrics

|  | Specification |
|---|---|
| **Description:** | Number of classes, properties, axioms and types of axioms, rules and individuals in the ontology. |
| **Importance:** | SHOULD |
| **Label:** | See File ensemble.owl on https://github.com/Zapretis1/CES_IA_Ontology |
----

### E.4 Incorporation of other ontologies

|  | Specification |
|---|---|
| **Description:** | The names, versions and citations of external ontologies imported into the ontology and where they are placed in the host ontology. |
| **Importance:** | MUST |
| **Label:** | Not relevant. Information collected from internet resources in non ontology format. |
----

### E.5 Entity naming convention

|  | Specification |
|---|---|
| **Description:** | The naming scheme for the entities in the ontology, capturing orthography, organisation rules, acronyms, and so on. |
| **Importance:** | MUST |
| **Label:** | CamelBack notation. |
----

### E.6 Identifier generation policy

|  | Specification |
|---|---|
| **Description:** | What is the scheme used for creating identifiers for entities in the ontology. State whether identifiers are semantic-free or meaningful. |
| **Importance:** | MUST |
| **Label:** | Incremental class number, using 10 digit number with ontology name as the prefix. |
----

### E.7 Entity metadata policy

|  | Specification |
|---|---|
| **Description:** | What metadata for each entity is to be present. This could include, but not be limited to: A natural language definition, editor, edit history, Labels, entity label and synonyms, etc. |
| **Importance:** | MUST |
| **Label:** | The labels used refer directly to natural language instruments and ensembles. For instance A wind quintet has at least one instrument of each family of instruments. https://fr.wikipedia.org/wiki/Quintette_%C3%A0_vent and https://en.wikipedia.org/wiki/Wind_quintet |
|
----

### E.8 Upper ontology

|  | Specification |
|---|---|
| **Description:** | If an upper ontology is used, which one is used and why is it used? If not used, then why. |
| **Importance:** | MUST |
| **Label:** | Not relevant; dat was collected from non ontology sources. |
----

### E.9 Ontology relationships

|  | Specification |
|---|---|
| **Description:** | The relationships or properties used in the ontology, which were used and why? Were new relationships required? Why? |
| **Importance:** | MUST |
| **Label:** | The relationships between ontology individuals rely on already mentioned sources https://en.wikipedia.org/wiki/Musical_instrument_classification. As suggested by the pizza tutorial: a ***ProbeClass*** has been created and a reasoner has been used (§4.9) for consistency checking, necessary and sufficient conditions have been used to create defined classes (i.e. WindQuintetEnsemble), with existential or universal restrictions (StringEnsemble), closure axioms, data type properties, individuals, value partition design pattern. |
----

### E.10 Axiom patterns

|  | Specification |
|---|---|
| **Description:** | An axiom pattern is a regular design of axioms or a template for axioms used to represent a category of entities or common aspects of a variety of types of entities. An axiom pattern may comprise both asserted and inferred axioms. The aim of a pattern is to achieve a consistent style of representation. An important family of axiom patterns are Ontology Design pattern (ODP) which are commonly used solutions for issues in representation.  |
| **Importance:** | MUST |
| **Label:** | Value Partition Design Pattern and Tree-like architecture. |
----

### E.11 Dereferenceable IRIs

|  | Specification |
|---|---|
| **Description:** | State whether or not the IRI used are dereferencable to a Web resource. Provide any standard prefix (CURIE). |
| **Importance:** | SHOULD |
| **Label:** | Not applicable |
----

## F. Managing Change

### F.1 Sustainability plan

|  | Specification |
|---|---|
| **Description:** | State whether the ontology will be actively maintained and developed. Describe a plan for how the ontology will be kept up to date. |
| **Importance:** | MUST |
| **Label:** | The ontology is part of an illustration of operating with OWL concepts using Protégé; its purpose is not to be maintained as is but thanks to versioning, it can be edited and further developed. |
----

### F.2 Entity deprecation strategy

|  | Specification |
|---|---|
| **Description:** | Describe the procedures for managing entities that become removed, split or redefined. |
| **Importance:** | MUST |
| **Label:** | The owl:DeprecatedClass; no class is deleted from the ontology, but deprecated classes are labelled as obsolete with an annotation property. |
----

### F.3 Versioning policy

|  | Specification |
|---|---|
| **Description:** | State or make reference to the policy that governs when new versions of the ontology are created and released. |
| **Importance:** | MUST |
| **Label:** | Github versioning policy. |
----

## G. Quality Assurance

### G.1 Testing

|  | Specification |
|---|---|
| **Description:** | Description of the procedure used to judge whether the ontology achieves the claims made for the ontology. State, for Label, whether the ontology is logically consistent, answers the queries it claims to answer, and whether it can answer them in a time that is reasonable for the projected use case scenario (benchmarking). |
| **Importance:** | MUST |
| **Label:** | The ontology was successfully classified by both Pellet 2.2.0 and HermiT 1.4.3.456 in less than 1 second. ProbeInconsistentInstrument was identified as incorrect. |
----

### G.2 Evaluation

|  | Specification |
|---|---|
| **Description:** | A determination of whether the ontology is of value and significance. An evaluation should show that the motivation is justified and that the objectives of the ontology's development are met effectively and satisfactorily. Describe whether or not the ontology meets its stated requirements, competency questions and goals.  |
| **Importance:** | MUST |
| **Label:** | The ontology provide information about the type of instruments and ensembles combining instruments of different kinds, with different popularity levels and from different origins. |
----

### G.3 Label of use

|  | Specification |
|---|---|
| **Description:** | An illustration of the ontology in use in its an application setting or use case. |
| **Importance:** | MUST |
| **Label:** | A use case could be to select ensembles depending on the musical climate a person wants to experience. Or to set prices of tickets to a concert. |
----

### G.4 Institutional endorsement

|  | Specification |
|---|---|
| **Description:** | State whether the ontology is endorsed by the W3C, the OBO foundry or some organisation representing a community. |
| **Importance:** | OPTIONAL |
| **Label:** | Not applicable.   |
----


### G.5 Evidence of use

|  | Specification |
|---|---|
| **Description:** | An illustration of active projects and applications that use the ontology.   |
| **Importance:** | MUST |
| **Label:** | The Ensemble Ontology is an application of the Protégé Tutorial for the CES course with Music as a domain of application. |
----
