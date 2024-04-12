
---
parent: Decisions
nav_order: 003
title: Selecting IDE for model development
---
# Selecting IDE for model development

## Context and Problem Statement

In order to begin developing our models we need to decide on an IDE to use. The development environment needs to support data science workflows, including data visualization, machine learning model development

## Decision Drivers

* Handling of computational resources, especially when dealing with large datasets or training machine learning models.
* User-friendly interface with accessible features for debugging, running, and writing code.

## Considered Options

* Jupyter Notebook in Google Colab
* PyCharm
* Visual Studio Code (VS Code)

## Decision Outcome

Chosen option: "Jupyter Notebook in Google Colab", because it provides a cloud-based environment that eliminates the need for local setup and maintenance of development environments. It offers free access to GPUs and TPUs which is beneficial for machine learning tasks as the laptop being used to develop this project has limited RAM avaliable. The notebook format is particularly user-friendly for data science workflows, allowing for the integration of code, text, and visuals in a single document.

### Consequences

* Good, because the cloud-based enviroment eliminates the need to install packages locally.
* Good, because it has access to GPUs and TPUs model development is not limited by hardware.
* Bad, because it has limited debugging capabilties.


## Pros and Cons of the Options

### Jupyter Notebook in Google Colab

* Good, because the cloud-based enviroment eliminates the need to install packages locally.
* Good, because it has access to GPUs and TPUs model development is not limited by hardware.
* Bad, because it has limited debugging capabilties.

### PyCharm

* Good, because IDE tailored for Python, with excellent support for debugging, testing, and project management.
* Bad, because requires configuration and setup, which can be time-consuming.
* Bad, because heavier on system resources
* Bad, because in order to access support for web applications you need the paid 'Professional' version

### Visual Studio Code (VS Code)

* Good, because supports a wide range of programming languages and technologies beyond Python, making it versatile.
* Bad, because requires local installation and does not provide direct access to high-performance computing resources.

