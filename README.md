## Context
Ensuring safety of operation is one of biggest challenges for market introduction of autonomous driving vehicles. Autonomous vehicle must manage with any kind of traffic scenario that can possibly occur. Therefore, to verify autonomous driving, the comprehensive set of traffic scenarios needs to be identified. There is need for a mathematical model to determine what should be interpreted as similar scenarios, and what should not be.

## Project
The project aims to find a model and investigate its capability to identify all possible kinds of complex traffic scenarios around autonomous vehicles.

## Responsibilities
- Propose a state transition model for describing the traffic scenarios.
- Describe the surrounding traffic objects in the model by occupation grids. The grids are translated into binary matrices where 1 denotes the occupation of nearby traffic object. Also attributes such as the vehicle’s speed and angular movement are used.
- Evaluate the model by analysing sequences of states computed from real traffic data provided by Viscando.
- Use clustering method to distinguish different scenarios represented by the model.

## Environment
Windows, Python.
