# SHACL Validation for AI Act Ontology

This repository contains SHACL shapes designed to validate basic constraints and consistency logic within an ontology that is aligned with EU AI Act.

## Contents

- `SHACL_SHAPES.ttl` — Core SHACL shapes for validation
- `explanation.docx` — Conceptual rationale and mapping strategy

## Technologies

- RDF & Turtle syntax
- SHACL (Shapes Constraint Language)
- Compatible with pySHACL and other SHACL engines



## Quick Validation (Online)

To quickly validate the SHACL shapes against your ontology, you can use the [SHACL Playground]([https://shaclplay.sparna.fr/playground/](https://shacl.org/playground/)):

1. Open the link: ([https://shaclplay.sparna.fr/playground/](https://shacl.org/playground/))
2. Paste your ontology into the **Data Graph** tab.
3. Paste `SHACL_SHAPES.ttl` into the **Shapes Graph** tab.
4. Click **Validate**.
5. Review results in the bottom pane (valid/invalid + details).

This is especially useful for lightweight checks or sharing with collaborators.
