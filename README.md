# Street Interface Measurement — Nature 9.03 v0.7.1 UX

A research-oriented application for inspecting and validating the full Street Interface Measurement workflow.

## Purpose

This version is designed for researchers, planners, and technical users who need to see how the Street Interface score is produced.

Unlike the public-facing application, this version exposes the analytical process, intermediate variables, formulas, and validation results.

## Required Inputs

The application uses three main inputs:

1. Original street-view image
2. Semantic segmentation mask
3. VLM-generated CSV file

## Workflow

The application presents the full analytical pipeline, including:

- Street-view image input
- Segmentation-based measurements
- VLM data import
- Nature 9.03 variables and formulas
- Imageability
- Identity
- Dependence
- Street Interface Matrix synthesis
- Final Street Interface score
- Validation and research diagnostics

## Research Role

This interface prioritizes methodological transparency and technical inspection.

It is intended to support:

- Research validation
- Planning analysis
- Method inspection
- Reproducibility checks
- Review of intermediate measurements

## Scientific Baseline

The application preserves the Nature 9.03 Street Interface Matrix research workflow and the frozen scientific calculation core used by the project.

## Local Development

Install dependencies:

```bash
npm install