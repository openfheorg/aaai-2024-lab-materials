# OpenFHE AAAI 2024 Tutorial

## Fully Homomorphic Encryption for Privacy-Preserving Machine Learning Using the OpenFHE Library

This tutorial offers a comprehensive exploration of Fully Homomorphic Encryption (FHE) and its practical application to privacy-preserving machine learning (PPML). Aimed at data scientists, ML engineers, and students interested in FHE, the tutorial equips participants with a solid understanding of FHE concepts and hands-on experience using the OpenFHE Python library.

The tutorial covers essential FHE concepts related to ML such as noise accumulation, noise threshold levels, and noise refreshing methods. Participants will be introduced to various FHE flavors that enable ML, such as the lookup-table TFHE and Cheon-Kim-Kim-Song (CKKS) methods. This tutorial focuses on building applications with the CKKS scheme, paying special attention to various cryptographic parameters associated with it, contextualized in terms of how the parameters affect ML applications.

# Material

## Slides

[OpenFHE AAAI 2024 Tutorial ](./AAAI_Tutorial.pdf)

## Code

[OpenFHE Python Logistic Regression Examples](https://github.com/openfheorg/python-log-reg-examples)

contains code for:

- a naive implementation of linear regression
- an optimized logistic regression

## Tutorial Outline

**Introductory Words** 8:30 - 8:40 (10 minutes)

- Agenda
- Installation options

**Lab Discussion: Comparing and Contrasting PPML Methods** 8:40 - 8:55 (15 minutes)

- Federated Learning
- Split Learning
- Differential Privacy
- Secure multi-party computation (MPC)

**Spinning Up in Homomorphic Encryption for ML** 8:55 - 9:55 (1 hour)

- Introduction to FHE
- Classes of FHE schemes
- FHE approaches for ML
- Selected studies in PPML using FHE
- Introduction to approximate FHE

**Q&A on FHE for ML/Quick Break** 9:55 - 10:10 (15 minutes)

**OpenFHE Library** 10:10 - 10:40 (30 minutes)

- Underlying design principles and inner workings
- High-level comparison with other libraries
- Development plans, including the Python port and the Google Transpiler
- Python example

**Quick Break** 10:40 - 10:55 (15 minutes)

**Hands-on: Using an In-the-Clear Model in the OpenFHE Library** 10:55 - 11:15 (20 minutes)

- Using a plaintext-trained model for encrypted inference
- Performance comparison between CKKS inference and model trained under a separate encryption scheme

**Hands-on: Training an Encrypted Logistic Regression Model in the OpenFHE Framework** 11:15 - 12:00 (45 minutes)

- Implementing a naive logistic regression
- Discussing pitfalls and weaknesses as well as optimizations
- implementing the optimizations in a working fashion

**ML Applications and FHE Challenges** 12:00 - 12:30 (30 minutes)

- ML Applications
- Introduction to the [FHERMA Project](https://fherma.io/challenges), a competition platform for Fully Homomorphic Encryption (FHE) challenges
- Discussion on new FHE challenges

## Pre-requisite Knowledge

Prerequisite knowledge includes proficiency in Python programming, a grasp of logistic regression, familiarity with NumPy and Single Instruction, Multiple Data (SIMD), and a basic understanding of Support Vector Machines.

# Organizers

**In no particular order**

<img src="./assets/profile_quah.png" width="50%" height="50%" />

Ian Quah is a Ph.D. student at the University of Washington's Ahmed Lab, working on deep reinforcement learning and biologically plausible deep learning. He actively contributes to OpenFHE, focusing on the application of fully homomorphic encryption in machine learning, with an emphasis on outreach and education.

<img src="./assets/polyakov_headshot.png" width="50%" height="50%" />

Yuriy Polyakov is the Vice President of Cryptography and a Principal Scientist at Duality Technologies. He is a project lead for OpenFHE software library project and serves on the Steering Committee of the HomomorphicEncryption.org standardization consortium. His research has been funded by DARPA, IARPA, NIH, Simons Foundation, and Sloan Foundation.

<img src="./assets/sukanya-01-min.jpeg" width="50%" height="50%" />

Sukanya, a Research Engineer and Tech Lead, specializes in driving innovation in Data and AI. She has led teams in developing Federated Learning across diverse domains, focusing on its application in Edge AI. Her work involves extensive research and development, creating prototypes, solutions, and architecting data systems for industrial domains. She actively contributes to OpenFHE
