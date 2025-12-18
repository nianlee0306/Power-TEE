# Power-TEE
This repository contains the source code for the paper:

**A Trusted Execution Environment for Secure Reasoning on Large-Scale Models in the Power Industry**

## Overview

This project implements a **TEE-based secure reasoning pipeline** for power system applications.
It combines:

- Trusted Execution Environment (TEE) for protected model inference  
- Explainable AI (XAI, SHAP) for feature attribution  
- Attribution-drift detection for identifying abnormal or adversarial inputs  

The goal is to ensure that large-scale model reasoning in power systems is **secure, auditable, and interpretable**.

## Key Features

- Secure model execution inside a TEE
- SHAP-based feature attribution computed in-enclave
- Attribution drift detection for FDI/anomaly awareness
- Hash-chained audit logs and remote attestation support
- Designed for power system datasets (e.g., microgrid scenarios)
