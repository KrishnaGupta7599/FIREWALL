# FIREWALL

FIREWALL is the main project repository for the FIREWALL security and machine learning suite.

## Project Overview

The FIREWALL project is designed to provide security monitoring, machine learning-driven threat detection, browser extension integrations, and backend analytics. 

## Repository Structure

The project is organized into the following major directories:

- `frontend/`: User interface and web dashboard application.
- `extension/`: Browser extension components and interface scripts.
- `backend/`: Core server logic, APIs, and business rules.
- `ml/`: Machine learning models, training scripts, pipelines, and evaluation utilities.
- `data/`: Data storage directory (ignored from Git tracking except for baseline structure).
  - `data/raw/`: Raw, unprocessed data files and datasets.
  - `data/processed/`: Cleaned, transformed, and feature-engineered datasets ready for modeling.
- `docs/`: Project documentation, architecture diagrams, and API specifications.

## Development Workflow

- **Primary Branch:** `main` serves as the official, stable development branch.
- **Branching & Pull Requests:** All team members should create feature/fix branches off `main` (e.g., `feature/login-page` or `fix/model-loader`) and submit Pull Requests (PRs) for review before merging into `main`.
