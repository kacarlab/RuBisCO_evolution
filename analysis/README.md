## Installation

    conda env create --file environment.yml

    conda activate md-analysis

## Ploomber Pipeline
We have implemented a Ploomber pipeline to run all the analysis files sequentially to improve reproducibility of the analysis and results

Command for running the ploomber pipeline
    ploomber build

- The pre-run results of the jupyter notebooks from the ploomber pipeline are in the `output` directory

- Files for the MD-simulation used in these analyses are available at: `https://zenodo.org/records/12626901`

## Contact
Mail: amritkar at wisc.edu or cuevaszuviri at wisc.edu