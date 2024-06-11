This directory has the solvated pdbs for the ancestral and extant RuBisCO complexes used in our study. These are used for preparing the input files for the MD-simulations.

Parameters directory has the different parameter files for the ligands and gas molecules present along with the complex.

Tleap program is used for generating the topology files for performing the MD-simulation.
Here we have two example tleap files: 
- `tleap.inp` is used for generating the topology files for the regular MD-simulations
- `tleap_gas.inp` is used for generating the topology files after addition of the gas molecules in the system.

Replace the `anci` with the respective complex name.