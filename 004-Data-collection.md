
---
parent: Decisions
nav_order: 004
title: Selecting Data collection method
---
# Selecting Data collection method

## Context and Problem Statement

We need to select a data collection method to train our neural network model that will optimize both the quality of the training data and the efficiency of our development process.

## Decision Drivers

* Data quality and relevance to the model’s objectives.
* Time and resources available for dataset preparation.
* The complexity of the dataset integration and processing.

## Considered Options

* Pre-made dataset
* Custom made dataset using FastF1 API
* Pre-made dataset with feature engineering

## Decision Outcome

Chosen option: "Pre-made dataset with feature engineering", because it combines the baseline quality and comprehensive coverage of a pre-made dataset with enhancements specific to our model's needs, offering a good balance between effort and performance.

### Consequences

* Good because, tailors a reliable data source to specific model requirements through feature enhancement.
* Good because, strikes a balance between customization and resource efficiency.
* Bad because, requires expertise in both the domain and feature engineering techniques.
* Bad because, Initially more resource-intensive than using a pre-made dataset alone.

## Pros and Cons of the Options

### Pre-made dataset with feature engineering

* Good because, tailors a reliable data source to specific model requirements through feature enhancement.
* Good because, strikes a balance between customization and resource efficiency.
* Bad because, requires expertise in both the domain and feature engineering techniques.
* Bad because, Initially more resource-intensive than using a pre-made dataset alone.

### Custom made dataset using FastF1 API

* Good because, highly customised to specific needs, ensuring data relevance.
* Good because, full control over data collection parameters.
* Bad because, requires significant time and resources to develop and maintain.
* Bad because, potential risks in data consistency and long-term availability.

### Pre-made dataset

* Good because, quick to acquire and integrate.
* Good because, lower initial effort.
* Bad because, may not perfectly align with specific data needs for the model.
* Bad because, limited control over data quality and features.

