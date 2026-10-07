# F1 Telemetry & AI Analytics Platform

Research-oriented engineering platform for legally accessible real-world Formula 1 and motorsport data.

## Current Phase

Real-data feasibility, literature review, dataset validation, and system architecture.

## Core Principle

Private/team ECU or telemetry is not assumed. Every data source must be evaluated for provenance, access, license, available signals, resolution, and limitations.

## Team Modules

- M1 — Data Pipeline & Spatial Signal Processing
- M2 — AI Driver Performance & Delta Modeling
- M3 — Tyre Degradation & Strategy Intelligence
- M4 — Vehicle Health & Sensor Anomaly Detection
- M5 — Interactive Telemetry UI & Visual Engine

## Repository Structure

- src/ — reusable application and analytics code
- data/ — data metadata and local datasets
- research/ — papers, datasets, patents, and research gaps
- docs/ — project and architecture documentation
- notebooks/ — experiments and exploration
- tests/ — automated tests
- archive/f1_22_prototype/ — previous simulator prototype

## Development Workflow

Issue → feature branch → implementation → tests → Pull Request → review → merge to main.
