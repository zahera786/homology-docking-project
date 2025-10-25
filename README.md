Homology Modeling and Molecular Docking Project

Overview
This project focuses on predicting and analyzing the 3D structure of a target protein using homology modeling and exploring its interactions with potential ligands through molecular docking. These computational techniques are key in understanding protein structure–function relationships and drug design.

Tools Used
1. SWISS-MODEL (Homology Modeling)
SWISS-MODEL is an automated web-based server for protein structure prediction based on homology modeling. It builds a 3D structure of a target protein using a known protein as a template.
The process involves:

Identifying suitable template structures from the PDB database

Aligning the target sequence with the template

Building a comparative 3D model using the ProMod3 engine

Evaluating model quality using GMQE and QMEAN scores

This tool provides an accessible platform for protein structure modeling and validation through its online workspace.​

Website: https://swissmodel.expasy.org

2. AutoDock Vina (Molecular Docking)
AutoDock Vina is a widely used molecular docking program that predicts how small molecules (ligands) bind to protein structures. It performs efficient docking simulations and estimates binding affinity values (kcal/mol).
Key steps include:

Preparing the protein and ligand files (.pdbqt format)

Defining the docking grid box on the protein

Running docking simulations to identify binding conformations

Evaluating interaction energies and docking poses

AutoDock Vina provides accurate results and performs well for both rigid and flexible docking protocols, making it ideal for this project.

Website: https://vina.scripps.edu

Methodology
Retrieve the protein sequence from UniProt.

Use SWISS-MODEL to generate a 3D homology model.

Validate the model using quality scores (GMQE, QMEAN).

Prepare ligands and proteins for docking.

Perform docking using AutoDock Vina.

Analyze binding affinity and visualize protein–ligand interactions.

Results
The homology model generated through SWISS-MODEL provided a stable structure for docking. Docking results identified key residues responsible for interactions and predicted binding energies, supporting further biological or drug design studies.

Conclusion
Using SWISS-MODEL for 3D structure prediction and AutoDock Vina for docking enabled accurate analysis of protein–ligand interactions. These tools combined offer a powerful computational pipeline for molecular biology and bioinformatics research.

References
Waterhouse, A. et al. (2018). SWISS-MODEL: Homology modelling of protein structures and complexes. Nucleic Acids Research.

Trott, O. & Olson, A. J. (2010). AutoDock Vina: Improving the speed and accuracy of docking with a new scoring function. Journal of Computational Chemistry.
