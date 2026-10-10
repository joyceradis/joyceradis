# ENGINEERING / JOYCE RADIS
## A public guide to the projects and how they are presented

**Physician-led systems · Clinical integrity · Product engineering**

**[Machine-readable project identity](PROJECT_CARD.json)**

This page describes a presentation standard for the public portfolio. Each repository remains the authoritative source for its own code, requirements, evidence, and release status.

### 01 / Principles

| Principle | Meaning |
|---|---|
| Workflows before frameworks | start with the operational problem, not a preferred stack |
| Evidence before claims | distinguish shipped features from prototypes and proposals |
| Source before derivative | a dashboard or generated artifact does not become a second source of truth |
| Versioned decisions | document changes where their implementation actually lives |
| Independent ownership | a collection of projects is not one giant repository |
| Collaboration without competition | compare contributions on their merits; credit work and keep its provenance |

### 02 / The repository label standard

A useful project README should answer six questions in its first screen:

1. **Identity:** what is it and who uses it?
2. **Purpose:** which real workflow does it improve?
3. **State:** is it a concept, prototype, evolving product, or maintained release?
4. **Architecture:** what is canonical data versus presentation?
5. **Evidence:** where are implementation, tests, and limitations?
6. **Navigation:** where do I start, run it, and read the technical decisions?

Claims such as tested, released, deployed, or production-ready require direct evidence. No decorative certification or fictitious statistics.

### 03 / Project directory

The public [profile README](README.md) is the curated entry point to independently maintained public repositories, including healthtech, medico-legal and operational tools. Repository-specific policies, links and run instructions belong inside those individual projects.

Older sites or experiments can remain as historical references without being presented as the current product. A successor does not need to delete its predecessor.

### 04 / Design language

- Clear editorial hierarchy and meaningful whitespace.
- Consistent, human-readable section titles and short navigation paths.
- Use color to encode a domain or state, not to decorate every element.
- Accessible contrast and layouts that work on mobile.
- Favor a restrained visual system over badges, widgets and inflated activity counters.

### 05 / Engineering evidence

A portfolio page can point to existing evidence, but should not re-implement it. Tests, accessibility checks, architecture notes, dependency choices and deployment processes belong with the projects they assess.

### 06 / Scope

This document is a **public editorial standard**, not an operational mandate for collaborators. It does not expose private project inventories, local filesystem paths, credentials, unpublished interfaces or internal-only governance.
