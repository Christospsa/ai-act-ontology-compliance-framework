# Reusable Semantic Elements
This folder contains reusable ontology elements and patterns developed to support compliance modeling aligned with the EU AI Act. These elements are semantically grounded and structured to ensure interoperability, traceability, and reusability across AI system representations.

## Contents:

semantic reuse.xlsx
This spreadsheet offers a curated mapping of selected AI Act requirements (e.g., from Articles and Annexes) to reusable ontology elements. Each row includes:

The relevant AI Act Requirement and Article reference

The Requirement Type (e.g., Risk, Accountability, Documentation)

Candidate Ontology (e.g., DPV, ODRL, GDPRov)

A proposed Candidate Concept

Explanatory Notes

Recommended Type (Class, Data Property, Object Property)

semantic_reuse_snippets_examples.ttl
This Turtle file provides implementation examples of the reusable elements defined in the spreadsheet. It demonstrates how to instantiate classes, properties, and restrictions using terms from ODRL, DPV, and GDPRov, customized where needed. These examples are designed to plug into broader compliance ontologies or be extended for specific use cases.
