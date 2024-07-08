# RuBisCO Evolution

## Summary

Analysis of the molecular dynamics of Rubisco across extant and ancestral diversity.

## Content

- **data**: Data files, including:
	- *phylogeny*: Phylogenetic trees
	- *sequences*: MSAs and ancestral reconstructions.
	- *structures*: PDB structures of the simulation inputs.
	- *systems for MD*: Files to run moleculear dynamics from scratch.
- **figures**: Figures in the main text of the manuscript.
- **analysis**: Jupyter notebooks with the detailed analysis of the molecular dynamics simulation trajectories

## Installation
To replicate the analysis, we recommend installing a Python environment through Conda. Miniconda can be downloaded from its webpage.
To install the environment, run:

	conda env create --file md-analysis.yml
	conda activate md-analysis

The molecular dynamics simulations require either a very powerful CPU server or a high-end GPU. \
As they take hundreds of computing hours to run these simulations, and the resulting files are heavier, we provide an streamlined version of our analysis where data values have been extracted from the simulations.	\
The simulation files themselves are uploaded at: `https://zenodo.org/records/12626901`

## Contact
For any queries or issues:	\
**Mail**: amritkar at wisc.edu or cuevaszuviri at wisc.edu
