
---
parent: Decisions
nav_order: 003
title: Selecting deliverable for model development
---
# Selecting IDE for deliverable development

## Context and Problem Statement

We need to develop a web application to work as the "deliverable" for our project. It will allow users to utilise our developed predictive model to see predictions. The IDE needs to support Django.

## Decision Drivers

* Compatibility with Python and Django.
* Support for version control systems, particularly Git.
* IDE efficiency and performance on developers' machines.

## Considered Options

* Visual Studio Code (VS Code)
* PyCharm
* Sublime Text

## Decision Outcome

Chosen option: "Visual Studio Code", because it provides extensive support for Python and Django through powerful extensions like the Python extension and Django snippets. It is lightweight, customizable, and integrates seamlessly with our existing development workflows and version control systems.

### Consequences



## Pros and Cons of the Options

### Visual Studio Code

* Good because, lightweight and fast, providing an efficient development experience.
* Good because, strong community support and regular updates.
* Good because, integrated terminal and native Git support enhance workflow integration.
* Bad because, being a general-purpose editor, it may require additional setup to optimize for Django development.
* Bad because, lacks some of the deeper project management features inherent in full-fledged IDEs like PyCharm.

### PyCharm

* Good because, specifically designed for Python, with excellent support for Django out of the box.
* Good because, comprehensive development features including superior debugging tools, database support, and environment management.
* Bad because, more resource-intensive, which can lead to slower performance on less powerful machines.
* Bad because, requires a paid subscription for the full set of features (Professional Edition).

### Sublime Text

* Good because, fast and lightweight, with a focus on efficiency and speed.
* Good because, xxtensible with plugins, although not as easily as VS Code.
* Bad because, requires a license for continued use beyond the trial period.
* Bad because, lacks the depth of dedicated Python and Django support found in PyCharm or the VS Code extensions ecosystem.
