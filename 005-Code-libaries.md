
---
parent: Decisions
nav_order: 005
title: Selecting code libraries 
---
# Selecting code libraries

## Context and Problem Statement

We aim to develop a neural network model that predicts the optimal tyre compounds to be used at various points during an F1 race. Choosing the right code library is crucial for effective model development, performance, and maintainability.

## Decision Drivers

* Library support for deep learning models and algorithms.
* Availability of community support and resources.
* Performance efficiency in model training and deployment.

## Considered Options

* TensorFlow
* PyTorch

## Decision Outcome

Chosen option: "TensorFlow", because it provides robust deployment capabilities, extensive support tools, and is highly compatible with our current production environments.

### Consequences

* Good because, it has a comprehensive suite of tools and libraries for various stages of model development.
* Good because, it has a large community and robust commercial support with extensive documentation.
* Bad because, its comprehensive nature may lead to slower initial development cycles compared to more lightweight frameworks.

## Pros and Cons of the Options

### Tensorflow

* Good because, it has a comprehensive suite of tools and libraries for various stages of model development.
* Good because, it has a large community and robust commercial support with extensive documentation.
* Bad because, its comprehensive nature may lead to slower initial development cycles compared to more lightweight frameworks.

### PyTorch

* Good because, there is an active development community, particularly in academic and research settings.
* Bad because, deployment in production environments can be less straightforward compared to TensorFlow.
* Bad because, steeper learning curve compared to Tensorflow
