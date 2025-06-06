# AI Act Ontology Compliance Framework

This repository contains an ontology-based framework developed for modelling compliance obligations under the European Union AI Act.

The framework focuses on key regulatory domains including:
- Risk classification
- Conformity assessment
- Technical documentation
- Post-market monitoring
- Registration and system identification

It was developed as part of a master's thesis project and is intended to support reasoning over compliance obligations via semantic queries (SPARQL).

---

## Repository Structure

| Folder / File         | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| `ontology/`            | Contains the OWL ontology in Turtle format (`.ttl`).                        |
| `survey/`              | Survey structure, ontology diagram, and screenshots of Qualtrics interface.|
| `sparql_queries/`      | Competency Questions (CQs) and SPARQL queries used to validate the ontology.|
| `mapping_table/`       | Excel sheets used to map AI Act articles to ontology concepts.              |
| `Reusable_Elements/`   | RDF snippets representing custom or reused elements aligned with AI Act.    |
| `Shacl_Shapes/`        | SHACL shapes (`.ttl`) for validating AI Act constraints in the ontology.    |
| `README.md`            | You’re here! Overview and navigation guide for the repository.              |


---

## Competency Questions (CQs)

The ontology is designed to answer key compliance questions such as:

1. What is the risk category of a given AI system?
2. Has the system undergone the required conformity assessment?
3. What technical documentation is linked to the system?
4. What changes have been declared post-deployment?
5. Is there a post-market monitoring plan in place?
6. What compliance activities are assigned to the provider?
7. Is the AI system properly registered and traceable?

These are supported through SPARQL queries in the `sparql_queries/` folder.

---

## Validation Survey

As part of the evaluation, a short stakeholder survey was developed:

[**Click here to open the survey**](https://[your-survey-link-goes-here](https://uva.fra1.qualtrics.com/jfe/form/SV_26rVulCOdUfGzWe))

The survey assesses the usability, completeness, and relevance of the framework among AI governance professionals.

---

##Author

**Christos Psaradellis**  
christos.psaradellis@student.uva.nl  
University of Amsterdam – MSc Thesis Project

---

## License

*No license defined yet – this project is currently for academic research only.*
