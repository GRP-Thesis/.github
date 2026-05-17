# Persuasion-Aware Taglish Smishing Detection

An undergraduate thesis project focused on detecting smishing in Filipino-English code-switched SMS messages using transformer-based natural language processing, Random Forest persuasion-aware features, and hybrid late fusion ensemble models.

---

## Overview

Smishing, or SMS phishing, has become an increasingly prevalent cybersecurity threat in the Philippines due to the widespread use of mobile messaging platforms and digital financial services. Existing phishing detection systems are primarily designed for English-only datasets and often fail to capture the linguistic and persuasive characteristics present in Filipino-English code-switched messages.

This study aims to develop an explainable and persuasion-aware smishing detection framework specifically tailored for Taglish SMS messages. The system combines transformer-based language models with persuasion-oriented linguistic indicators derived from established persuasion principles to improve detection capability and interpretability.

The project also includes a prototype dashboard that demonstrates real-time SMS classification, branch-level confidence analysis, persuasion-marker visualization, and ensemble decision explainability.

---

## Research Objectives

- Detect smishing in Filipino-English code-switched SMS messages
- Develop persuasion-aware linguistic feature extraction techniques
- Train and evaluate transformer-based and Random Forest classification models
- Implement a hybrid late fusion ensemble architecture
- Build an explainable dashboard prototype for SMS analysis and demonstration

---

## Proposed Architecture

The proposed framework consists of three primary branches:

### Branch A — Transformer-Based NLP Model
A transformer-based language model trained on Taglish SMS datasets for contextual smishing classification.

### Branch B — Random Forest Persuasion Classifier
A Random Forest classifier trained on persuasion-aware linguistic features derived from persuasion principles such as:

- Authority
- Reciprocity
- Commitment / Consistency
- Social Proof
- Likeability
- Scarcity

### Branch C — Hybrid Late Fusion Ensemble
An ensemble layer that combines the outputs of the transformer and Random Forest branches to generate the final classification result.

---

## Key Features

- Taglish SMS classification
- Persuasion-aware linguistic analysis
- Explainable smishing analysis dashboard
- Branch-level confidence visualization
- Ensemble prediction analysis
- Persuasion-marker detection and visualization
- Frontend and backend integration for live demonstration

---

## Technology Stack

### Backend
- Python
- FastAPI
- PyTorch
- scikit-learn
- NumPy

### Frontend
- React
- TypeScript
- TailwindCSS
- Apache ECharts

### Development Tools
- GitHub Projects
- GitHub Actions
- Prettier
- ESLint

---

## Repository Structure

```text
thesis-development/
├── data/
├── inter_annotation_agreement/
├── models/
├── notebooks/
├── prototype/
│   ├── backend/
│   └── frontend/
├── results/
├── scripts/
└── README.md
