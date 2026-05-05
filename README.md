Computational Phytopharmacology for Endocrine Support

 Overview

This project performs in silico screening of phytochemicals using machine learning, network pharmacology, and molecular docking to identify potential endocrine-modulating compounds.

Workflow

Literature Collection (349 compounds)
↓
SMILES Retrieval
↓
STITCH (Compound–Protein Interaction)
↓
Toxicity Analysis (ProTox-II)
↓
ADME Analysis (SwissADME)
↓
ML Clustering (KNIME)
↓
PPI Network (STRING)
↓
Network Analysis (Cytoscape)
↓
Target Selection (TP53, TNF, IL6, CTNNB1)
↓
Molecular Docking (PyRx)

Key Results

* Screened 349 phytochemicals → 139 filtered candidates
* Identified key targets: TP53, TNF, IL6, CTNNB1
* Best docking score: −12.3 kcal/mol (Campesterol–TNF)
* ML clustering revealed structurally similar compound groups

Tools & Technologies

* Bioinformatics: STITCH, STRING
* ADME/Toxicity: SwissADME, ProTox-II
* Machine Learning: KNIME
* Network Analysis: Cytoscape
* Docking: PyRx (AutoDock Vina)

Project Structure

* 03_ml_clustering → ML clustering results
* 04_network_analysis → PPI network
* 05_docking → docking interactions
* 06_pipeline → workflow diagram

Thesis

[THESIS](THESIS.pdf)
