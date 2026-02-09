# lukens_phm2025

Synthetic dataset supporting the 2025 PHM Society paper:

**Lukens, S., Bishof, M., Siddiqui, N., & West, D. (2025).
*An Evaluation Framework for Fault Diagnosis Using Technical Manuals in Retrieval-Augmented Large Language Models.*
Annual Conference of the PHM Society, 17(1).**
[https://doi.org/10.36001/phmconf.2025.v17i1.4549](https://doi.org/10.36001/phmconf.2025.v17i1.4549)

---

## Overview

This repository contains a **synthetic dataset of 300 operator observations** for the **LMTV (Light Medium Tactical Vehicle)**, each labeled with a corresponding **ground-truth fault code**.

The dataset was generated using **OpenAI GPT-5** guided by the official **LMTV technical manual** referenced in the paper.
It is intended for **research and benchmarking of fault diagnosis methods**, particularly:

* Retrieval-augmented generation (RAG)
* LLM-assisted troubleshooting
* Diagnostic classification from natural-language observations

---

## Dataset Location

```
data/lukens_phm2025_input_data.csv
```

The CSV file contains:

* Synthetic operator observation text
* Associated ground-truth fault code used for evaluation in the paper

---

## Intended Use

This dataset is suitable for:

* Testing **fault-diagnosis pipelines**
* Evaluating **LLM reasoning over technical manuals**
* Benchmarking **retrieval + classification architectures**
* Educational or reproducibility purposes related to the PHM 2025 study

**Not intended for:**

* Real-world maintenance decisions
* Safety-critical deployment
* Training production diagnostic systems without further validation

---

## Data Generation Notes

* Observations are **fully synthetic** and contain **no real operator data**.
* Text was generated using **GPT-5** with prompts derived from:

  * The **LMTV technical manual**
  * Fault-code structure described in the paper
* Ground-truth labels reflect the **intended simulated fault condition**, not field measurements.

---

## Reproducing the Study

See the published paper for:

* Prompting methodology
* RAG pipeline design
* Evaluation framework
* Performance metrics

Open-access paper:
[https://papers.phmsociety.org/index.php/phmconf/article/view/4549](https://papers.phmsociety.org/index.php/phmconf/article/view/4549)

Summary blog post:
[https://www.linkedin.com/pulse/from-demo-deployment-scaling-evaluating-llms-fault-diagnosis-lukens-qcw5e/](https://www.linkedin.com/pulse/from-demo-deployment-scaling-evaluating-llms-fault-diagnosis-lukens-qcw5e/)

---

## Citation

If you use this dataset, please cite:

```
Lukens, S., Bishof, M., Siddiqui, N., & West, D. (2025).
An Evaluation Framework for Fault Diagnosis Using Technical Manuals in Retrieval-Augmented Large Language Models.
Annual Conference of the PHM Society, 17(1).
https://doi.org/10.36001/phmconf.2025.v17i1.4549
```



