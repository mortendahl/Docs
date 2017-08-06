# Development Scope

> system evolution and component features 🛣📦

<!-- TOC depthFrom:2 -->

- [Phases](#phases)
    - [0. Demonstration](#0-demonstration)
    - [1. Proof of concept](#1-proof-of-concept)
    - [2. Hardening](#2-hardening)
    - [3. Usability](#3-usability)
- [Component features](#component-features)
    - [pySonar](#pysonar)
    - [Mine](#mine)
    - [Capsule](#capsule)
    - [Sonar](#sonar)
    - [syft](#syft)
    - [adapters](#adapters)

<!-- /TOC -->

## Phases

### 0. Demonstration

Scope: Have a demo that includes the most important aspects of Open Mined

Status: ✅ _done_

### 1. Proof of concept

Scope: Develop the ecosystem to a state that allows skilled people to run their own mine to evaluate feasability and evaluate technological bottlenecks.

Phases:
1. single components working locally
2. global system using ethereum testnet
3. optional: ethereum mainchain

Status: 👷 _in progress_

### 2. Hardening

Scope: Fix issues to ensure scalability, security and privacy concerns identified during the PoC.

Status: _open_

### 3. Usability

Scope: Make the system usable by a wider range of people. This includes making it easy to run Mines and import data, support for further data sources (adapters) as well as more variety in available models.

Status: _open_

## Component features

Individual features that the components might develop.

### pySonar

### Mine

1. mine model (read model from sonar, fetch model from IPFS, call `syft` to train, publish new gradients to IPFS & sonar)
2. use adapters to transform data for the model
3. identify models that can be trained
    * model still in training
    * source data available
4. mining strategies
    * which models should be trained
    * keep track how often a model was trained

### Capsule

### Sonar

### syft

### adapters
