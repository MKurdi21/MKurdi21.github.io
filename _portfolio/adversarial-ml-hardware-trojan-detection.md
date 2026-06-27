---
title: "Adversarial ML for Hardware Trojan Detection"
excerpt: "M.S. and early Ph.D. research on robust ML-assisted hardware Trojan detection."
collection: portfolio
permalink: /portfolio/adversarial-ml-hardware-trojan-detection/
order: 2
---

This project summarizes Mohammed Alkurdi's M.S. research and early Ph.D. research under Professor Fathi Amsaad. The work connected adversarial machine learning, hardware Trojan detection, side-channel or ring-oscillator-informed measurements, and robust machine-learning pipelines.

## Problem

Machine-learning-assisted hardware Trojan detection can be useful for hardware-security-sensitive settings, but models may be brittle when inputs are noisy, adversarially perturbed, or collected under practical side-channel constraints. This project studies how adversarial machine learning affects hardware Trojan detection and how robust ML pipelines can improve trust in security-oriented detection results.

## My Role

Mohammed Alkurdi contributed to this research during his M.S. and early Ph.D. work under Professor Fathi Amsaad. His contributions centered on adversarial ML framing, robust hardware Trojan detection evaluation, research writing, and connecting model behavior to security-sensitive hardware detection workflows.

## Approach

The work considers ML-assisted hardware Trojan detection using side-channel or ring-oscillator-informed measurements and evaluates how detection behavior changes under adversarial or golden-reference-free conditions. The private implementation workspace supports a structured experiment pipeline around Ring Oscillator Network (RON) measurements, chip-disjoint/versioned train-test splits, supervised baselines, repeated-trial analysis, target-guided feature-space attack evaluation, practical attack ablations, adversarial retraining, adaptive defense evaluation, and paper-ready result consolidation.

Modeling and evaluation work includes conventional supervised learners and ensembles, PCA-informed comparisons, grouped validation to reduce chip-leakage risk, confusion-derived security metrics, confidence summaries, and reproducible manifests for experiment auditing. The public summary is intentionally limited to high-level methods and published evidence, avoiding restricted datasets, private implementation details, and unpublished result tables.

## Outputs and Evidence

- Conference paper: [Adversarial Attack Resilient ML-Assisted Hardware Trojan Detection Technique](/publication/2024-07-01-adversarial-attack-resilient-ml-hardware-trojan-detection)
- Conference paper: [Adversarial Attack Against Golden Reference-Free Hardware Trojan Detection Approach](/publication/2024-11-12-adversarial-attack-golden-reference-free-hardware-trojan)
- Conference paper: [Enhancing Hardware Trojan Security through Reference-Free Clustering using Representatives](/publication/2024-01-06-reference-free-clustering-representatives)
- Journal article: [A Golden-Free Unsupervised ML-Assisted Security Approach for Detection of IC Hardware Trojans](/publication/2025-07-01-golden-free-unsupervised-ml-ic-trojans)
- Thesis: [A Trusted Adversarial ML Countermeasure Approach for Secure and Resilient AI-Driven Hardware Trojan Detection](/publication/2024-12-14-ms-thesis-hardware-trojan-detection)
- Implementation repository private; public summary supported by peer-reviewed publications and M.S. thesis.

## Current Status

Published / completed.

## Security and Ethics

The page presents peer-reviewed and thesis-level outputs without exposing restricted datasets, sensitive implementation details, raw experiment artifacts, or unpublished numeric results. The emphasis is defensive robustness evaluation for hardware-security-sensitive settings.
