# Managing Error in GIS

**Authors:** Kenneth E. Foote and Donald J. Huebner  
**Affiliation:** Department of Geography, University of Texas at Austin  
**Original Date:** 1996  
**Source:** The Geographer's Craft Project

---

## Overview

This module addresses the critical issues of error, accuracy, and precision in Geographic Information Systems. It provides techniques for controlling and managing error in GIS projects.

---

## Major Sections Covered

### 1. The Problems of Error, Accuracy and Precision

- Fundamental definitions
- Difference between accuracy and precision in spatial data
- **Accuracy:** Closeness of a measurement to its actual value
- **Precision:** Level of detail or repeatability of measurements

### 2. Setting Standards for Procedures and Products

- Necessity of establishing clear guidelines
- Standards for data collection
- Standards for processing

### 3. Documenting Procedures and Products (Data Quality Reports)

- Focus on "lineage" of data
- Providing metadata for users
- Tracking data sources and transformations

### 4. Measuring and Testing Products

- Methods for evaluating dataset quality
- Testing protocols

### 5. Calibrating a Dataset to Ascertain How Error Influences Solutions

- **Sensitivity Analysis:** Understanding how input errors propagate
- Varying data layers slightly to see result changes
- Identifying critical/volatile inputs

### 6. Report Results in Terms of the Uncertainties of the Data

- Guidelines for presenting findings
- Avoiding implied absolute certainty
- Using confidence intervals
- Descriptive rankings (high/medium/low probability)

### 7. References and Supplemental Reading

- Key academic texts on error propagation
- Spatial accuracy literature

### 8. Examination and Study Questions

- Practical questions for students

---

## Key Error Management Concepts

### Accuracy vs. Precision

| Term          | Definition                                     |
| ------------- | ---------------------------------------------- |
| **Accuracy**  | Closeness of measurement to actual/true value  |
| **Precision** | Level of detail; repeatability of measurements |

### Lineage and Metadata

- History of dataset (source, transformations, processing)
- Crucial for assessing reliability
- Documenting who created what, when, and how

### False Certainty

- Warning against reporting results with more precision than data allows
- Example: Reporting population density to four decimal places when raw counts are rounded

### Sensitivity Analysis

- Technique where data layers are varied slightly
- Observes how much final result changes
- Identifies which inputs are most critical

### Spatial Data Transfer Standard (SDTS) Components

- Positional accuracy
- Attribute accuracy
- Logical consistency
- Completeness

### Reporting Uncertainty

- Use confidence intervals
- Use descriptive rankings instead of single deterministic values
- High-variability data requires careful presentation

---

## Archive Information

**Original URL:** `http://www.colorado.edu/geography/gcraft/notes/manerror/manerror_f.html`  
**Archive URL:** `https://web.archive.org/web/20020806045349/http://www.colorado.edu/geography/gcraft/notes/manerror/manerror_f.html`

---

## Modernization Notes for Version 2

This content should be enhanced with:

- Modern uncertainty quantification methods
- Machine learning accuracy assessment
- Cross-validation techniques
- Confusion matrices for classification
- **Cohen's Kappa** and other agreement measures
- ISO 19157 (Geographic Information - Data Quality)
- Monte Carlo simulation for error propagation
- Geostatistical uncertainty methods

---

_Archived: 2026-01-18_
