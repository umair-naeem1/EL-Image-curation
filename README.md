# EL-Image-curation

Quality Electroluminescence Image Curation and Benchmark Dataset for Photovoltaic Diagnostics

## Overview

This repository contains the dataset and  source code, experimental results and benchmarking framework associated with our research on low-cost Electroluminescence (EL) imaging for photovoltaic (PV) defect diagnostics using a modified DSLR camera.

The project focuses on:
- Cost-effective EL image acquisition
- EL image enhancement and curation
- AI-ready dataset preparation
- Leakage-free benchmarking protocols
- Deep learning and machine learning evaluation for PV defect classification

## Features

- Synchronized EL image acquisition workflow
- Multi-frame averaging and background subtraction
- EL preprocessing and PV cell segmentation
- Benchmarking pipeline with stratified cross-validation
- Evaluation using:
  - Accuracy, Recall, F1-score, PR-AUC, MCC, Confusion matrices, Complexity analysis (GFLOPs, inference speed, model size)

## Evaluated Models

- SVM, Random Forest (RF), MobileNetV2, ResNet18, ResNet34, DenseNet121


## Citation

If you use this dataset, code, or framework in your research, please cite:

> U. Naeem, K. Chaddha, X. Li, S. Vahaji, and E. Asadi,  
> “Quality Electroluminescence image curation and benchmark dataset for photovoltaic diagnostics,”  
> *Solar Energy Materials and Solar Cells*, vol. 306, Art. no. 114555, 2026.  
> https://doi.org/10.1016/j.solmat.2026.114555

### BibTeX

```bibtex
@article{NAEEM2026114555,
  title   = {Quality Electroluminescence image curation and benchmark dataset for photovoltaic diagnostics},
  journal = {Solar Energy Materials and Solar Cells},
  volume  = {306},
  pages   = {114555},
  year    = {2026},
  issn    = {0927-0248},
  doi     = {10.1016/j.solmat.2026.114555},
  url     = {https://www.sciencedirect.com/science/article/pii/S092702482600396X},
  author  = {Umair Naeem and Ken Chaddha and Xiaodong Li and Sara Vahaji and Ehsan Asadi},
}
