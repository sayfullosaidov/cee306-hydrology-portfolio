# HW4 — Snow Hydrology and Machine Learning

**CEE 306: Hydrology — Water and Climate | Princeton University | Spring 2026**

This folder contains my coursework notebook exploring snow hydrology and applications of convolutional neural networks (CNNs) to hydrologic prediction. The notebook includes analysis of snow water equivalent (SWE) and exercises using neural networks to predict SWE and streamflow from hydrometeorological inputs.

## Contents

- [`hw4_snow_machine_learning.ipynb`](hw4_snow_machine_learning.ipynb) — Coursework calculations, experiments, figures, and written interpretations.

## Methods and topics

- Snow water equivalent and SNOTEL observations
- CNN-based hydrologic prediction using PyTorch
- Model training, testing, and parameter experiments
- Comparison and visualization of predictions and observations

## Code dependencies and reproducibility

The CNN portions of this notebook use supporting Python scripts provided for the course, including `rmm_nn.py`, `Shapes.py`, `transform.py`, and `utilities.py`. Those scripts are **not included** in this public folder. The notebook may therefore not run end-to-end as published; saved notebook outputs document the results of the original coursework. Some analyses also depend on external data or model files.

## Attribution

This notebook was completed for CEE 306 at Princeton University, taught by **Professor Reed Maxwell**. The CNN architecture and supporting course scripts were provided as instructional resources; the original notebook identifies scripts created by **RMM**. I do not claim authorship of those components. The notebook presents my coursework experiments and interpretations, alongside any course-provided scaffolding retained in code cells.

The accompanying course materials and instructor-written assignment instructions are not redistributed here. If permission to redistribute the helper scripts is obtained, they can be added with appropriate attribution and any required license notice.
