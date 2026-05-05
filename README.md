Computational Phytopharmacology for Endocrine Support

 Overview

This project performs in silico screening of phytochemicals using machine learning, network pharmacology, and molecular docking to identify potential endocrine-modulating compounds.

Workflow

[Workflow](06_pipeline/workflow.png)

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
