# FairML4H-PostProcessing

This repository contains supplementary results for the paper *"Empirical comparison of post-processing debias methods for ML classifiers in healthcare"* by Vien Ngoc Dang et al. This project evaluates the effectiveness of various post-processing debias methods in improving fairness and performance of machine learning classifiers, focusing on healthcare applications to ensure equitable outcomes across different demographic groups.
## Methods

We evaluated seven state-of-the-art post-processing debiasing methods:

1. **CPP (Calibrated Equalized Odds Post-Processing)**: [Paper](https://proceedings.neurips.cc/paper_files/paper/2017/file/b8b9c74ac526fffbeb2d39ab038d1cd7-Paper.pdf)
2. **EPP (Equalized Odds Post-Processing)**: [Paper](https://papers.nips.cc/paper_files/paper/2016/file/9d2682367c3935defcb1f9e247a97c0d-Paper.pdf)
3. **ROC (Reject Option Classification)**: [Paper](https://ieeexplore.ieee.org/document/6413831)
4. **PSTA (Population Sensitivity-Guided Threshold Adjustment)**: [Paper](https://www.nature.com/articles/s41598-024-58427-7)
5. **FACT (Fairness-Confusion Tensor)**: [Paper](https://dl.acm.org/doi/10.5555/3524938.3525426)
6. **GSTAR (Group Specific Threshold Adaptation for Fair Classification)**: [Paper](https://cdn.aaai.org/ojs/20657/20657-13-24670-1-2-20220628.pdf)
7. **MAB (Multiaccuracy Boost)**: [Paper](https://dl.acm.org/doi/10.1145/3306618.3314287)

## Datasets

### Medical Datasets

1. **CDC Diabetes Health Indicators**: [Dataset](https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+Hospitals+for+Years+1999-2008)
2. **Heart Disease**: [Dataset](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)
3. **Depression Disease (UK Biobank)**: [Dataset](https://www.ukbiobank.ac.uk/enable-your-research/register)
4. **Medical Expenditure Panel Survey (MEPS)**: [Dataset](https://meps.ahrq.gov/mepsweb/)

### Non-Medical Datasets

1. **Adult**: [Dataset](https://archive.ics.uci.edu/ml/datasets/Adult)
2. **German Credit**: [Dataset](https://archive.ics.uci.edu/ml/datasets/Statlog+(German+Credit+Data))
3. **COMPAS**: [Dataset](https://github.com/propublica/compas-analysis)
4. **Bank Marketing**: [Dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)

## Evaluation Metrics

Performance metrics:
- **Balanced Accuracy (BAcc)**
- **Accuracy (Acc)**
- **F1-score**

Fairness metrics:
- **Equal Opportunity Difference (EOp)**
- **Equalized Odds Difference (EOd)**

## Supplementary Results

The results of our experiments, supplementary to those mentioned in the paper, are detailed in three Jupyter notebooks:
- **Medical_datasets.ipynb**: Includes supplementary results of debias methods on medical datasets.
- **Non-medical_datasets.ipynb**: Includes supplementary results of debias methods on non-medical datasets.
- **Overall_datasets.ipynb**: Provides a comprehensive supplementary evaluation of debias methods across both medical and non-medical datasets.
