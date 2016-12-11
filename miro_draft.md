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
| **Description:** | A A name or description of the steps taken to develop the ontology. |
| **Importance:** | OPTIONAL |
| **Example:** | OntoClean, Methontology |
----

## Motivation

### Need

|  | Specification |
|---|---|
| **Description:** | Justification of why the ontology is needed. |
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
| **Description:** | The domain or field of interest and the boundaries, granularity of representation and coverage extent. A high level visualisation or tabular representation is optional, but often helpful to illustrate the scope. |
| **Importance:** | MUST |
| **Example:** | From the Human Phenotype Ontology NAR 2013 article "human phenotypic abnormalities." https://academic.oup.com/nar/article-lookup/doi/10.1093/nar/gkt1026  |
----

### Community

|  | Specification |
|---|---|
| **Description:** | The target audience; the use cases the ontology will support; the competency questions or requirements the ontology fulfills. |
| **Importance:** | MUST |
| **Example:** | Table S1 in The Ontology for Biomedical Investigations article in PlOS One 2016. https://www.ncbi.nlm.nih.gov/pubmed/27128319|
----

### Communication

|  | Specification |
|---|---|
| **Description:** | Location, usually URL,  of the email list and/or the issue tracking systems used for development and managing feature requests. |
| **Importance:** | MUST |
| **Example:** | http://www.ebi.ac.uk/efo/submit.html |
----

## Knowledge elicitation

### Source knowledge

|  | Specification |
|---|---|
| **Description:** | Detail on how the knowledge in the ontology was gathered, sorted, verified etc. |
| **Importance:** | MUST |
| **Example:** | Description of source in Materials and method section of article The Software Ontology (SWO): a resource for reproducibility in biomedical data analysis, curation and digital preservation in JMBS 2014 https://jbiomedsem.biomedcentral.com/articles/10.1186/2041-1480-5-25 |
----

### Source knowledge location

|  | Specification |
|---|---|
| **Description:** | The location whence the knowledge was gathered. |
| **Importance:** | MUST |
| **Example:** | Description of data gathered such as found in: https://softwareontology.wordpress.com/2011/04/04/an-agile-ontology/. |
----

### Content selection

|  | Specification |
|---|---|
| **Description:** | The prioritisation of entities to be represented in the ontology and how that prioritisation was achieved. |
| **Importance:** | MUST |
| **Example:** | Description of the prioritisation process for the Software Ontology in https://softwareontology.wordpress.com/2011/04/04/an-agile-ontology/ |
----

## Ontology content

### Knowledge Representation language

|  | Specification |
|---|---|
| **Description:** | What knowledge representation language was used and why. For a language like OWL indicate the OWL profile and expressivity. |
| **Importance:** | MUST |
| **Example:** | OWL version 2, EL profile. |
----

### Development environment

|  | Specification |
|---|---|
| **Description:** | The tool(s) used in developing the ontology. |
| **Importance:** | OPTIONAL |
| **Example:** | Protégé, WebProtégé, TawnyOWL, TopBraid Composer, Swoop, etc. |
----

### Ontology metrics

|  | Specification |
|---|---|
| **Description:** | Number of classes, properties, axioms, rules and individuals. |
| **Importance:** | SHOULD |
| **Example:** | From the Human Phenotype Ontology NAR 2013 article "Human Phenotype Ontology provides a structured, comprehensive and well-defined set of 10,088 classes (terms) describing human phenotypic abnormalities and 13,326 subclass relations between the HPO classes." https://academic.oup.com/nar/article-lookup/doi/10.1093/nar/gkt1026  |
----

### Incorporation of other ontologies

|  | Specification |
|---|---|
| **Description:** | Versions of external ontologies imported into the ontology and where they are placed in the host ontology. |
| **Importance:** | MUST |
| **Example:** | Import of Uberon core – extended version, 2016-05-11 release under the 'anatomical entity' class. |
----

### Entity naming convention

|  | Specification |
|---|---|
| **Description:** | Describe the naming scheme for the entities in the ontology, capturing orthography, organisation rules, acronyms, and so on. |
| **Importance:** | MUST |
| **Example:** | OBO Foundry naming conventions. |
----

### Identifier generation policy

|  | Specification |
|---|---|
| **Description:** | What is the scheme used for creating identifiers for entities in the ontology. State whether identifiers are semantic-free or meaningful. |
| **Importance:** | MUST |
| **Example:** | Incremental class number, using 10 digit number with ontology name as the prefix. |
----

### Entity metadata policy

|  | Specification |
|---|---|
| **Description:** | What metadata for each entity is to be present. This could include, but not be limited to: A natural language definition, editor, edit history, examples, entity lable and synonyms, etc. |
| **Importance:** | MUST |
| **Example:** | *there must be a GO thing for this* Each class minimally requires a textual definition and a label. |
----

### Upper ontology

|  | Specification |
|---|---|
| **Description:** | If an upper ontology is used, which one is used and why is it used? If not, why. |
| **Importance:** | MUST |
| **Example:** | SUMO, BFO. *an example sentence would be good.* |
----

### Ontology relationships

|  | Specification |
|---|---|
| **Description:** | The relationships or properties used in the ontology, which were used and why? Were new relationships required? Why? |
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
| **Description:** | State whether the ontology wil be actively maintained and developed. Describe a plan for how the ontology will be kept up to date. |
| **Importance:** | MUST |
| **Example:** | Outline of plan including method to sustain and who will be responsible. |
----

### Entity deprecation strategy 

|  | Specification |
|---|---|
| **Description:** | Describe the procedures for managing entities that become removed, split, redefined. |
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
| **Description:** | Description of procedure used to judge whether the ontology achieves the claims made for the ontology. State, for example, whether the ontology answers the queries it claims to answer; is the ontology consistent, with all classes satisfiable, and with all necesssary subsumptions in place. |
| **Importance:** | MUST |
| **Example:** | Examples of competency questions that can be asked. Examples of inferences that can be made. |
----

### Evaluation

|  | Specification |
|---|---|
| **Description:** | Describe whether or not the ontology meets its stated requirements, competency questions  and goals. State whether the use cases given for the ontology can be met. The description of the evaluation may involve user studies. |
| **Importance:** | MUST |
| **Example:** | Description of the evaluation and how the ontology meets the ontology scope and requirements. |
----

### Example use

|  | Specification |
|---|---|
| **Description:** | Examples An illustration of the ontology in use in its intended application setting or use case. |
| **Importance:** | MUST |
| **Example:** | Example of data using the ontology. Example of an application using the ontology. |
----

### Institution endorsement

|  | Specification |
|---|---|
| **Description:** | State whether the ontology is endorsed by the W3C, the OBO foundry or another institution. |
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

