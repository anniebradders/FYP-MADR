
---
parent: Decisions
nav_order: 002
title: Selecting Version/Source Control System
---
# Selecting Version/Source Control System

## Context and Problem Statement

Over the development of the project we must use a system that will allow for efficient code management, and robust version control are critical to ensuring the project's success.

## Decision Drivers

* System should be stable and handle large repositories without performance issues.
* Compatibility with existing tools and services used in development
* Ease of use

## Considered Options

* Git
* Mercurial

## Decision Outcome

Chosen option: "Git", because it seamlessly intergrates with the majoirty of tools and platforms. It also offers superior performance when it comes to branching and merging, which are frequent in a project with a heavy focus on ongoing development. It is also the industry standard.

### Consequences

* Good, because strong support for branching and merging.
* Good, because a lot of intergration options
* Neutral, because used widely within indsutry
* Bad, because if not managed properly with techniques like squashing commits or pruning history, the repository can become unwieldy.

## Pros and Cons of the Options

### Git

* Good, because strong support for branching and merging.
* Good, because a lot of intergration options
* Neutral, because used widely within indsutry
* Bad, because if not managed properly with techniques like squashing commits or pruning history, the repository can become unwieldy.

### Mercurial

* Good, because strong support for branching and merging.
* Good, because cleaner command-line interface.
* Neutral, because not as widely used within the industry
* Bad, because fewer intergration options
