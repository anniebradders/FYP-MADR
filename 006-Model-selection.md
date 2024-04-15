
---
parent: Decisions
nav_order: 006
title: Selecting models to develop
---
# Selecting models to develop

## Context and Problem Statement

In the context of developing predictive analytics capabilities, we need to choose appropriate machine learning models that best fit the complexity, performance requirements, and nature of the data we are processing. The models must be capable of effectively handling time-series data for predicting outcomes based on historical patterns.

## Decision Drivers

* Accuracy and performance of the models in time-series prediction.
* Computational efficiency and resource requirements.
* Suitability of the model to the specific characteristics of the data.
* Sustainability and ease of maintenance.

## Considered Options

* Long Short-Term Memory Networks (LSTM)
* Recurrent Neural Networks (RNN)
* Convolutional Neural Networks (CNN)
* Artificial Neural Networks (ANN)

## Decision Outcome

Chosen options: "LSTM, RNN, CNN, and ANN". These models were selected to cover a broad spectrum of neural network architectures, offering various strengths in handling different aspects of time-series forecasting.

### Consequences

* See below

## Pros and Cons of the Options

### LSTM (Long Short-Term Memory Networks)

* Good because, they are excellent at capturing long-term dependencies in time-series data.
* Good because, reduces the risk of vanishing gradient problem common in standard RNNs.
* Bad because, computationally more complex and demanding than simpler RNNs.
* Bad because, longer training times.

### RNN (Recurrent Neural Networks)

* Good because, naturally fits time-series data due to its recurrent nature.
* Good for modeling sequence data and temporal information.
* Bad because, prone to vanishing and exploding gradient problems.
* Bad because, often outperformed by more advanced models like LSTM for long sequences.

### CNN (Convolutional Neural Networks)

* Good because, highly effective at extracting hierarchical spatial features from data.
* Good because, efficient computation via weight sharing and convolutions.
* Neutral because, not traditionally used for time-series data but can be adapted for such with appropriate architecture adjustments.
* Bad because, may overlook temporal dynamics if not properly configured.

### ANN (Artificial Neural Networks)

* Good because, simpler and quicker to implement and train compared to more complex architectures.
* Good because, effective for capturing non-temporal patterns and relationships in data.
* Bad because, less effective at processing time-dependent data without modifications.
* Bad because, generally lacks the depth required for more complex pattern recognition in time-series.


