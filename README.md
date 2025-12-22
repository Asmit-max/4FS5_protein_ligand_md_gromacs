# 4FS5_protein_ligand_md_gromacs
All-atom molecular dynamics simulation and stability analysis of a human protein–ligand complex (PDB: 4FS5) using GROMACS and CHARMM36.


# Molecular Dynamics Simulation of Protein–Ligand Complex (PDB: 4FS5)

## Overview
This repository contains the complete workflow, input files, and analysis scripts for a
~100 ns all-atom molecular dynamics (MD) simulation of a human protein–ligand complex
derived from the PDB structure 4FS5.

The simulation was performed using GROMACS 2021.4 with the CHARMM36 force field and
TIP3P water model under near-physiological ionic conditions.

## Biological Objective
The primary objective of this study is to evaluate whether the co-crystallized ligand
remains stably bound within the protein binding pocket and maintains key intermolecular
interactions throughout the simulation timescale.

## Why Molecular Dynamics
Molecular dynamics simulations were employed to:
- Validate docking-derived binding stability
- Observe protein–ligand interaction dynamics
- Assess conformational fluctuations under physiological conditions
- Complement static structural data from X-ray crystallography

## Simulation Details
- **Protein:** Human protein (PDB ID: 4FS5)
- **Ligand:** Co-crystallized ligand from PDB
- **Simulation type:** Protein–ligand complex
- **Simulation length:** ~100 ns
- **Force field:** CHARMM36
- **Water model:** TIP3P
- **Ions:** Na⁺ / Cl⁻ (~0.15 M)
- **Software:** GROMACS 2021.4

## Analyses Performed
- Root Mean Square Deviation (RMSD)
- Root Mean Square Fluctuation (RMSF)
- Radius of Gyration (Rg)
- Hydrogen bond analysis
- Solvent Accessible Surface Area (SASA)
- Secondary structure analysis (DSSP)
- Distance-based interaction analysis

## Repository Structure
- `input_files/` → GROMACS input files and topologies
- `scripts/` → MD execution and analysis scripts
- `analysis/` → Raw analysis outputs
- `results/` → Processed plots and tables
- `environment/` → Software version information

## Reproducibility
All input parameters, force field selections, and analysis scripts are provided.
Large trajectory files are intentionally excluded and can be regenerated using the
provided setup.

## Asmit-max
Asmit Santra  
B.Tech Biotechnology, Amity University Kolkata
