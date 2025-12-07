# COVID-19 CT Classification (Student Research Project)

## Overview
This repository contains code used for a learning and reproduction project in medical image analysis.  
The goal is to classify chest CT scans into **COVID-19 vs. Non-COVID** using deep learning models.

This project helped me gain hands-on experience with:
- Working on real clinical imaging data
- Building end-to-end training and evaluation pipelines
- Understanding challenges such as data quality and generalization

⚠️ Note: This is **not** the official implementation of the dataset or baseline methods.  
The code is adapted and extended for research learning purposes.

---

## My Contributions
- Developed and debugged training + evaluation scripts in PyTorch  
- Built dataset loaders and augmentation workflows  
- Conducted experiments and performance analysis  
- Compared model variants and interpreted results  

---

## Project Highlights
- Reproducible DL workflow for CT image classification
- Practical understanding of medical imaging domain constraints
- Solid baseline performance for experimentation

---

## Technical Stack
- Python
- PyTorch, NumPy, OpenCV

---
Dataset Source (Original Authors)
This project uses the publicly available COVID-CT-Dataset, originally curated and released by:
Zhao, Jinyu et al.
COVID-CT-Dataset: A CT scan dataset about COVID-19
https://arxiv.org/pdf/2003.13865.pdf

Please cite the original authors if you use this dataset:
@article{zhao2020COVID-CT-Dataset,
  title={COVID-CT-Dataset: a CT scan dataset about COVID-19},
  author={Zhao, Jinyu and Zhang, Yichen and He, Xuehai and Xie, Pengtao},
  journal={arXiv preprint arXiv:2003.13865},
  year={2020}
}

Some benchmarking code references:
@Article{he2020sample,
  author  = {He, Xuehai and Yang, Xingyi and Zhang, Shanghang and Zhao, Jinyu and Zhang, Yichen and Xing, Eric and Xie, Pengtao},
  title   = {Sample-Efficient Deep Learning for COVID-19 Diagnosis Based on CT Scans},
  journal = {medrxiv},
  year    = {2020},
}

Disclaimer
This project is for research learning purposes only and should not be used for clinical decision-making.
 

