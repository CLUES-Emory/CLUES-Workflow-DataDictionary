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
| [LC-HRMS Feature Table]({% link docs/data-dictionaries/lchrms-features.md %}) | LC-HRMS | Untargeted feature-level output from XCMS processing |
| [GC-HRMS Feature Table]({% link docs/data-dictionaries/gchrms-features.md %}) | GC-HRMS | Untargeted feature-level output from GC-HRMS processing |
| [Sample Metadata]({% link docs/data-dictionaries/sample-metadata.md %}) | All | Sample-level metadata linking analytical results to study information |
| [Annotation Results]({% link docs/data-dictionaries/annotation-results.md %}) | All | Chemical annotation output from database matching |
| [Microplastics Results]({% link docs/data-dictionaries/microplastics.md %}) | Py-GC-HRMS | Polymer identification and quantification results |

## Processing Workflows

Step-by-step documentation of data processing pipelines from raw instrument output through annotation and analysis.

| Workflow | Description |
|:---------|:------------|
| [LC-HRMS Pipeline]({% link docs/workflows/lchrms-pipeline.md %}) | Raw data → batch-corrected annotated feature table |
| [Batch Correction]({% link docs/workflows/batch-correction.md %}) | QC-RLSC and ComBat signal correction methods |
| [Sample Preparation]({% link docs/workflows/sample-preparation.md %}) | Extraction protocols for serum, plasma, urine, tissue |
| [QC Procedures]({% link docs/workflows/qc-procedures.md %}) | Quality control sample types and acceptance criteria |

## Reference

| Page | Description |
|:-----|:------------|
| [Naming Conventions]({% link docs/reference/naming-conventions.md %}) | Standardized naming for variables, files, and datasets |
| [Data Types]({% link docs/reference/data-types.md %}) | Guide to data type classifications used in this documentation |

---

{: .note }
This site is maintained by the CLUES lab group. Data dictionaries and workflows are updated as methods evolve. If you find errors or have suggestions, please [open an issue](https://github.com/YOUR_USERNAME/clues-data-docs/issues) on GitHub.
