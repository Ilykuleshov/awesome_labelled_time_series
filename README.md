---
title: README.md
---

## Awesome time series classification datasets

### Notation

Labels:

-  B - Binary label.

-  C - Multiclass classification label.

-  R - Regression label.

Some datasets have several labels, which is indicated by number (e.g. 4xBfour binary labels) or via comma-separated values (e.g. B,R - binary and regression labels).

### Transactions

| **Name**                   | **URL**                                              | **Label** | **Type** | **Balanced** | **Missing** |
|----------------------------|------------------------------------------------------|-----------|----------|--------------|-------------|
| Multimodal Banking Dataset | <https://huggingface.co/datasets/ai-lab/MBD>         | product   | 4xB      | No           | No          |
| Age                        | <https://ods.ai/competitions/sberbank-sirius-lesson> | age bin   | C        | Yes          | No          |

### Medical

| Name           | URL                                                   | Label     | Type | Balanced | Missing |
|----------------|-------------------------------------------------------|-----------|------|----------|---------|
| PhysioNet 2012 | <https://physionet.org/content/challenge-2012/1.0.0/> | mortality | B    | No       | Yes     |
| MIMIC          | <https://physionet.org/content/mimiciii/1.4/>         | mortality | B    | No       | Yes     |

### Retail

| Name    | URL                                                         | Label       | Type | Balanced | Missing |
|---------|-------------------------------------------------------------|-------------|------|----------|---------|
| X5-hero | <https://ods.ai/competitions/x5-retailhero-uplift-modeling> | Age, Gender | 2xC  | Yes      | No      |
| TaoBao  |                                                             | purchase    | B    |          |         |


