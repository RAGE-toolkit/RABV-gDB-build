
# RABV-gDB-build

`RABV-gDB-build` contains the RABV-specific files required to run the V-gTK workflow and build a rabies virus genomic database. This repository is intended to work together with V-gTK by providing the reference files, configuration files, curation files, test data, and build script needed to generate a local RABV SQLite database.

The repository provides a fully functional RABV example workflow. It demonstrates how V-gTK can be used to collect and organise rabies virus sequence data, link sequences with metadata, apply curation steps, prepare reference resources, and generate a structured genomic database for downstream analysis.

Once the RABV database has been generated, it can be used by V-gTK for sequence management, metadata curation, custom sequence addition, alignment preparation, phylogenetic analysis, and clade-assignment workflows.

## Repository contents

The repository contains the files required to execute the RABV database build workflow through V-gTK.

```text
RABV-gDB-build/
├── generic/
│   └── rabv/
├── test_data/
├── test_fix_debug/
├── rabv-gDB-build.sh
├── v-gTK-init.nf
├── nextflow.config
├── pytest.ini
├── TESTING.md
└── README.md
```

### Main components

- `generic/rabv/`  
  Contains RABV-specific reference files, curation files, clade information, alignment resources, and other configuration files required by the V-gTK database build workflow.

- `rabv-gDB-build.sh`  
  Main bash script used to run the RABV database build process.

- `test_data/`  
  Contains example or test input files that can be used for testing and validating the workflow.

- `test_fix_debug/`  
  Contains files used for testing, debugging, or fixing workflow-related issues.

- `v-gTK-init.nf` and `nextflow.config`  
  Nextflow-related files used for workflow configuration or execution where applicable.

- `pytest.ini` and `TESTING.md`  
  Testing-related files for validating the workflow and associated scripts.

## Purpose

The purpose of this repository is to provide a ready-to-use RABV resource layer for V-gTK. While V-gTK provides the general framework and scripts for viral genomic database construction, `RABV-gDB-build` provides the rabies virus-specific files needed to execute a complete RABV example.

This allows users to build a local RABV genomic database without manually preparing all reference and configuration files from scratch.

# Building RABV database
All the database building information can be found here at [V-gTK main repo](https://github.com/centre-for-virus-research/V-gTK/tree/main)
