---
nav_order: 000
title: Deciding what ARD template to use
---
# Deciding what ADR template to use

## Context and Problem Statement

Decision records are required to keep track of all decision made throughout the development process for the project. This will contain rational for the decisions we have made as well as alternate options we considered.

## Decision Drivers

* Easily readable
* Decisions explained in full

## Considered Options

* **Option 1: MADR**
* **Option 2: Word Document**
* **Option 3: Confluence**

## Decision Outcome

Chosen option: "**Option 1: MADR**, because they are easiy readable making the files more accessible to a diverse range of people, they can also be easily tracked using version control as well as a consistency in the way decisions are recorded using a uniform structure.

### Consequences

* Good, because readability  markdown is deisgned to be human-readable and easy to understand.
* Good, because intergration with tools - markdown is widely supported by various tools and platforms. If the system is migrated to another system to decison records should experience minimal impact.
* Bad, because limited formatting options.

## Pros and Cons of the Options

### MARD

* Good, because readability  markdown is deisgned to be human-readable and easy to understand.
* Good, because intergration with tools - markdown is widely supported by various tools and platforms. If the system is migrated to another system to decison 
* Bad, because limited formatting options.

### Word Document

* Good, because widley used so non-technical people are able to read and edit it.
* Good, because diverse set of formatting options
* Bad, because not easy to collabrate on unless you want to edit the whole document

### Confluence

* Good, because collaborative editing
* Good, because easy to link between pages
* Bad, because a standard format may not be enforced

## More Information

MADR recommended as an ADR format (Zimmermann & Stocker, 2023).

Zimmermann, O., & Stocker, M. (2023). Design Practice Reference Activities and Templates to Craft Quality Software in Style. LeanPub. Retrieved from https://leanpub.com/dpr/read_sample