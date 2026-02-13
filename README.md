# PPMI Ontology Alignment

This repository provides a reproducible framework for aligning longitudinal Parkinson’s Progression Markers Initiative (PPMI) data with formal disease and measurement concepts defined in the Parkinson’s Disease Ontology (PDON) and Movement Disorder Ontology (PMDO).

The project supports ontology-based analysis of Parkinson’s disease trajectories and ontology-informed machine learning using longitudinal clinical, imaging, and biomarker observations.

---

# Objectives

This project aims to:

1. Map curated PPMI variables to PDON and PMDO ontology concepts  
2. Construct a patient-centric ontology instantiation (A-box) linking subjects, visits, and observations  
3. Evaluate alignment between ontology-defined disease concepts and observed longitudinal trajectories  
4. Assess ontology-informed feature representations for machine learning modelling  

---

# Conceptual Architecture

PPMI longitudinal data  
→ variable-to-ontology mapping  
→ bridge ontology (PDON + PMDO integration layer)  
→ ontology population (patient instances and observations)  
→ trajectory analysis and ontology-informed ML  

---

# Repository Structure

ppmi-ontology-alignment/
│
├── ontologies/
│ Source ontologies and bridge ontology
│
├── mapping/
│ Variable-to-ontology mapping definitions
│
├── notebooks/
│ Colab notebooks for ontology loading, mapping, and analysis
│
├── src/
│ Reusable Python modules for ontology processing and population
│
├── output/
│ Generated ontology instances and analysis results
│
└── requirements.txt
│ Python dependencies

---

# Ontologies

This project uses:

- Parkinson’s Disease Ontology (PDON)
- Movement Disorder Ontology (PMDO)

These ontologies are integrated through a bridge ontology that links PPMI data variables to ontology concepts.

---

# Data

PPMI data are not distributed in this repository.

PPMI data must be obtained from:

https://www.ppmi-info.org/

and stored locally or in Google Drive when running Colab notebooks.

---

# Reproducibility

All ontology mappings, ontology population procedures, and analysis workflows are implemented as reproducible Python pipelines and Colab notebooks.

---

# Requirements

Python 3.10+

Main libraries:

- rdflib
- pandas
- numpy
- scikit-learn

Install dependencies:

```bash
pip install -r requirements.txt

---

## Usage

Open notebooks from the `notebooks/` folder using:

- Google Colab  
- or  
- a local Jupyter environment  

and run them sequentially.

---

## Scientific Scope

This repository supports research on:

- ontology-based representation of longitudinal disease trajectories  
- semantic integration of multimodal cohort data  
- ontology-informed machine learning  
- empirical evaluation of disease ontology alignment  

---

## Status

Active research project.

Ontology mappings and pipelines are under continuous development.

---

## License

Specify license before publication (recommended: MIT or Apache 2.0).

---

## Contact

**Maintainer:** [Your Name]  
**Institution:** [Your Institution]
