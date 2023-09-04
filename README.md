# pipeline_template
A template repository for pipeline code. For an example, see https://github.com/IGVF-UCSD/celloracle_pipeline/tree/dev. This should include:

# `README.md` (this file)
- With details on the method

# `bin`

- Compiled code that runs different iterations of each pipeline

## `pipeline_1`

- Maybe this is the simple one sample one run pipeline

## `pipeline_2`

- Maybe this is a SLURM pipeline

## `...`

# `data`

- Any auxiliary data needed for running methods
    - If it’s small, put it in the repo
    - If it’s large, link to it a file

# `env`

- .def file for singularity set-up so you can run (recommended for reproducbility)
- .yaml file for conda set-up so you can run (recommended for modifcation)
