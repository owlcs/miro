<header>
MIRO – Minimal Information for Reporting of an Ontology
==============
</header>
## Working draft 16 November 2016

**Editors**:
Robert Stevens, Manchester University

James Malone, FactBio Limited

Chris Mungall, National Evolutionary Synthesis Center, Lawrence Berkeley Labs, Gene Ontology Consortium

Nicolas Matentzoglu, Manchester University

**Edit history:**

| Version | Date | Contributors | Changes |
|---|---|---|---|
| 0.0.1 | 16.05.2016 | Robert Stevens, James Malone, Chris Mungall, Nicolas Matentzoglu | First version |
| 0.0.2 | 27.05.2016 | James Malone|Review first version for wording and examples |
| 0.0.3 | 28.06.2016 | Nicolas Matentzoglu | Unified capitalisation in Information Item names |
| 0.0.4 | 02.12.2016 | James Malone | Add elucidation to items |
----

# Summary 
This document contains the Minimal Information for Reporting of an Ontology (MIRO) guidelines. 

# Guidelines

## Basics

### Ontology name

|  | Specification |
|---|---|
| **Description:** | The full name of the ontology, including the acronym and the version number referred to in the report. |
| **Importance:** | MUST |
| **Example:** | Gene Ontology (GO), v2.13; Foundational Model of Anatomy Ontology (FMA), v4.22; |
----

### Ontology owner

|  | Specification |
|---|---|
| **Description:** | The names and affiliations (where appropriate) of the person, people or consortium that manager the ontology and their contact details. |
| **Importance:** | MUST |
| **Example:** | GO Administrators, go@geneontology.org |
----

### Ontology license

|  | Specification |
|---|---|
| **Description:** | The licence which governs the permissions surrounding the ontology. |
| **Importance:** | MUST |
| **Example:** | Creative Commons Attribution 3.0 (CC BY 3.0) |
----

### Ontology URL

|  | Specification |
|---|---|
| **Description:** | The web location where the ontology file is available. |
| **Importance:** | MUST |
| **Example:** | http://www.berkeleybop.org/ontologies/doid.owl |
----

### Ontology repository

|  | Specification |
|---|---|
| **Description:** | The web location (URL) of the version control system where current and previous versions can be found. |
| **Importance:** | MUST |
| **Example:** | https://github.com/geneontology |
----

### Methodological framework

|  | Specification |
|---|---|
| **Description:** | A description or name of the steps taken to organise the development of the ontology. |
| **Importance:** | OPTIONAL |
| **Example:** | OntoClean, Methontology |
----

## Motivation

### Need

|  | Specification |
|---|---|
| **Description:** | Description on why the ontology is needed. |
| **Importance:** | MUST |
| **Example:** | For example the 2015 JBMS article "Unification of multi-species vertebrate anatomy ontologies for comparative biology in Uberon" has the following: "Here we present the unification of anatomy ontologies into Uberon, a single ontology resource that enables interoperability among disparate data and research groups." http://jbiomedsem.biomedcentral.com/articles/10.1186/2041-1480-5-21 |
----

### Competition

|  | Specification |
|---|---|
| **Description:** | If there is another ontology or ontologies in the same general area, the names and references of these ontologies together with a description on why the one being reported is needed instead or in addition. |
| **Importance:** | MUST |
| **Example:** | ** |
----

### Target audience

|  | Specification |
|---|---|
| **Description:** | For which task or use was the ontology developed. |
| **Importance:** | MUST |
| **Example:** | For example the EFO 2010 Bioinformatics article, section 1.1 Motivation: the Gene Expression Atlas https://bioinformatics.oxfordjournals.org/content/26/8/1112.full |
----

## Scope, requirements, community

### Scope and coverage

|  | Specification |
|---|---|
| **Description:** | Boundaries of the domain or field of interest, granularity of representation and coverage extent. A high level visualisation or tabular representation is optional, but often helpful to illustrate the scope. |
| **Importance:** | MUST |
| **Example:** | This ontology represents a classification of infectious human diseases. It excludes related information such as organismal systems they affect. |
----

### Community

|  | Specification |
|---|---|
| **Description:** | The community that is being engaged and how it is being done. |
| **Importance:** | MUST |
| **Example:** | Description of use scenarios gathered and competency questions, any consultations held, size of engagement. |
----

### Email list and issue tracking

|  | Specification |
|---|---|
| **Description:** | Location of the email list and/or the issue tracking systems used for development and managing feature requests. |
| **Importance:** | MUST |
| **Example:** | http://www.ebi.ac.uk/efo/submit.html |
----

## Knowledge elicitation

### Source knowledge

|  | Specification |
|---|---|
| **Description:** | Detail on how the knowledge in the ontology was found, sorted, verified etc. |
| **Importance:** | MUST |
| **Example:** | Description of source, for example if experts were used, their broad qualifications (e.g. medical doctors). |
----

### Raw data location

|  | Specification |
|---|---|
| **Description:** | The 'raw data' location, if applicable. |
| **Importance:** | MUST |
| **Example:** | Description of data gathered such as found in: https://softwareontology.wordpress.com/2011/04/04/an-agile-ontology/. |
----

### Feature prioritisation

|  | Specification |
|---|---|
| **Description:** | The prioritisation of features. Which features were prioritised and how? |
| **Importance:** | MUST |
| **Example:** | Description of included/excluded features. Details of how decisions were reached. |
----

## Ontology content

### KR language

|  | Specification |
|---|---|
| **Description:** | The knowledge representation (KR) language used  and why. If the ontology is in OWL, indicate exact OWL Profile (EL, QL, RL), and potentially logical language (e.g. SROIQ, ALC; this is optional). |
| **Importance:** | MUST |
| **Example:** | OWL EL profile. |
----

### Development environment

|  | Specification |
|---|---|
| **Description:** | The development environment used. |
| **Importance:** | OPTIONAL |
| **Example:** | Protégé, WebProtégé, TawnyOWL, TopBraid Composer, Swoop, etc. |
----

### Ontology metrics

|  | Specification |
|---|---|
| **Description:** | Number of classes, properties, axioms, rules, individuals. |
| **Importance:** | SHOULD |
| **Example:** | From the Human Phenotype Ontology NAR 2013 article "Human Phenotype Ontology provides a structured, comprehensive and well-defined set of 10,088 classes (terms) describing human phenotypic abnormalities and 13,326 subclass relations between the HPO classes." https://academic.oup.com/nar/article-lookup/doi/10.1093/nar/gkt1026  |
----

### Imports and interoperability

|  | Specification |
|---|---|
| **Description:** | Versions of external ontologies consumed in the ontology. Is the ontology aligned/compatible with other ontologies? |
| **Importance:** | MUST |
| **Example:** | Import of Uberon core – extended version, 2016-05-11 release. |
----

### Entity naming convention

|  | Specification |
|---|---|
| **Description:** | Naming conventions for ontology entities. |
| **Importance:** | MUST |
| **Example:** | OBO Foundry naming conventions. |
----

### Identifier generation policy

|  | Specification |
|---|---|
| **Description:** | The entity identifier generation policy. |
| **Importance:** | MUST |
| **Example:** | Incremental class number, using 10 digit number with ontology name as prefix. |
----

### Entity metadata policy

|  | Specification |
|---|---|
| **Description:** | The entity metadata policy. |
| **Importance:** | MUST |
| **Example:** | Each class minimally requires a textual definition and a label. |
----

### Upper ontology

|  | Specification |
|---|---|
| **Description:** | If an upper ontology used, which one is used and why. If not, why. |
| **Importance:** | MUST |
| **Example:** | SUMO, BFO. |
----

### Ontology relationships

|  | Specification |
|---|---|
| **Description:** | The relationships used in the ontology, which were used and why. Were new relationships required? Why? |
| **Importance:** | MUST |
| **Example:** | The schema.org relationships were imported and used. |
----

### Axiom patterns 

|  | Specification |
|---|---|
| **Description:** | Axiom or statement patterns used in describing ontology classes. If none were used, was the description ad hoc? |
| **Importance:** | MUST |
| **Example:** |  |
----

### Dereferencable IRIs 

|  | Specification |
|---|---|
| **Description:** | Are dereferencable IRIs used? If not, why? Do you suggest any standard prefix (CURIE)? |
| **Importance:** | OPTIONAL |
| **Example:** | e.g. http://purl.obolibrary.org/obo/GO_0006915 |
----

## Managing Change

### Sustainability plan 

|  | Specification |
|---|---|
| **Description:** | Will the project be actively maintained and developed? Who will be responsible? Ideally, describe a sustainability plan for the next years. |
| **Importance:** | MUST |
| **Example:** | Outline of plan including method to sustain and who will be responsible. |
----

### Entity deprecation strategy 

|  | Specification |
|---|---|
| **Description:** | Deprecation strategy for ontology entities. |
| **Importance:** | MUST |
| **Example:** | Use of owl:DeprecatedClass, no class deleted. |
----

### Versioning policy

|  | Specification |
|---|---|
| **Description:** | The versioning policy of the ontology. |
| **Importance:** | MUST |
| **Example:** | Dated release number. |
----

## Quality Assurance

### Testing

|  | Specification |
|---|---|
| **Description:** | Description of testing performed on the ontology. |
| **Importance:** | MUST |
| **Example:** | Examples of competency questions that can be asked. Examples of inferences that can be made. |
----

### Evaluation

|  | Specification |
|---|---|
| **Description:** | Evaluation of the ontology. Does the ontology accomplish the original requirements? If the ontology contains optional modules, indicate the exact configuration of the ontology (version of imports etc.) used for the evaluation. |
| **Importance:** | MUST |
| **Example:** | Description of the evaluation and how the ontology meets the ontology scope and requirements. |
----

### Example use

|  | Specification |
|---|---|
| **Description:** | Examples of the ontology's usage. |
| **Importance:** | MUST |
| **Example:** | Example of data using the ontology. Example of an application using the ontology. |
----

### Institution endorsement

|  | Specification |
|---|---|
| **Description:** | Is your ontology endorsed by the W3C, the OBO foundry or another institution? |
| **Importance:** | OPTIONAL |
| **Example:** | W3C recommendation. OBO Foundry library ontology.  |
----

### Logical consistency

|  | Specification |
|---|---|
| **Description:** | Is the ontology logically consistent? Does it contain unsatisfiable classes. If so, why? |
| **Importance:** | MUST |
| **Example:** | Detail of reasoned used and status of satisfiability. |
----

### Evidence use

|  | Specification |
|---|---|
| **Description:** | List active projects and applications using the ontology. Illustrate the added value. |
| **Importance:** | MUST |
| **Example:** | List of projects, links to websites. |
----

