---
layout: default
title: Home
nav_order: 1
---

# CLUES Data Documentation
{: .fs-9 }

Reference documentation for datasets, variable definitions, and analytical workflows developed by the Comprehensive Laboratory for Untargeted Exposome Science (CLUES) at Emory University.
{: .fs-6 .fw-300 }

---

## Data Dictionaries

Variable definitions, data types, units, and allowable values for each dataset produced by the lab.

| Dataset | Platform | Description |
|:--------|:---------|:------------|
| [LC-HRMS Feature Table](docs/data-dictionaries/lchrms-features.html) | LC-HRMS | Untargeted feature-level output from XCMS processing |
| [GC-HRMS Feature Table](docs/data-dictionaries/gchrms-features.html) | GC-HRMS | Untargeted feature-level output from GC-HRMS processing |
| [Sample Metadata](docs/data-dictionaries/sample-metadata.html) | All | Sample-level metadata linking analytical results to study information |
| [Annotation Results](docs/data-dictionaries/annotation-results.html) | All | Chemical annotation output from database matching |
| [Microplastics Results](docs/data-dictionaries/microplastics.html) | Py-GC-HRMS | Polymer identification and quantification results |

## Processing Workflows

Step-by-step documentation of data processing pipelines from raw instrument output through annotation and analysis.

| Workflow | Description |
|:---------|:------------|
| [LC-HRMS Pipeline](docs/workflows/lchrms-pipeline.html) | Raw data → batch-corrected annotated feature table |
| [Batch Correction](docs/workflows/batch-correction.html) | QC-RLSC and ComBat signal correction methods |
| [Sample Preparation](docs/workflows/sample-preparation.html) | Extraction protocols for serum, plasma, urine, tissue |
| [QC Procedures](docs/workflows/qc-procedures.html) | Quality control sample types and acceptance criteria |

## Reference

| Page | Description |
|:-----|:------------|
| [Naming Conventions](docs/reference/naming-conventions.html) | Standardized naming for variables, files, and datasets |
| [Data Types](docs/reference/data-types.html) | Guide to data type classifications used in this documentation |

---

{: .note }
This site is maintained by the CLUES lab group. Data dictionaries and workflows are updated as methods evolve. If you find errors or have suggestions, please [open an issue](https://github.com/YOUR_USERNAME/clues-data-docs/issues) on GitHub.
