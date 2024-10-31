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

{% table %}

---

*  {% isHeader=true %}

   Name

*  {% colwidth=[208] isHeader=true %}

   URL

*  {% isHeader=true %}

   Label

*  {% isHeader=true %}

   Type

*  {% colwidth=[127] isHeader=true %}

   Balanced

*  {% isHeader=true %}

   Missing

---

*  {% colspan=6 colwidth=[0,208,0,0,127,0] %}

   ### Transactions

---

*  Multimodal Banking Dataset

*  {% colwidth=[208] %}

   <https://huggingface.co/datasets/ai-lab/MBD>

*  product

*  4xB

*  {% colwidth=[127] %}

   No

*  No

---

*  Age

*  {% colwidth=[208] %}

   <https://ods.ai/competitions/sberbank-sirius-lesson>

*  age bin

*  C

*  {% colwidth=[127] %}

   Yes

*  No

---

*  {% colspan=6 colwidth=[0,208,0,0,127,0] %}

   ### Medical

---

*  PhysioNet 2012

*  {% colwidth=[208] %}

   <https://physionet.org/content/challenge-2012/1.0.0/>

*  mortality

*  B

*  {% colwidth=[127] %}

   No

*  Yes

---

*  MIMIC

*  {% colwidth=[208] %}

   <https://physionet.org/content/mimiciii/1.4/>

*  mortality

*  B

*  {% colwidth=[127] %}

   No

*  Yes

---

*  {% colspan=6 colwidth=[0,208,0,0,127,0] %}

   ### Retail

---

*  X5-hero

*  {% colwidth=[208] %}

   <https://ods.ai/competitions/x5-retailhero-uplift-modeling>

*  Age, Gender

*  2xC

*  {% colwidth=[127] %}

   Yes

*  No

---

*  TaoBao

*  {% colwidth=[208] %}

   

*  purchase

*  B

*  {% colwidth=[127] %}

   

*  

{% /table %}
