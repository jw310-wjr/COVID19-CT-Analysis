# COVID-19 CT Classification (Student Research Project)

## Overview
This repository contains code for a convolutional neural network (CNN) based system to classify chest CT scans into COVID-19 vs. Non-COVID cases.  
This project was developed as part of my early research in AI for medical imaging.

---

## Project Highlights
- End-to-end deep learning pipeline for CT image classification  
- Implemented model training, validation, and evaluation workflows  
- Data preprocessing and augmentation for improved generalization  
- Reproducible experiment configurations and analysis scripts  

---

## Technical Stack
- Python, PyTorch
- OpenCV, NumPy

---

## My Contributions
- Implemented training loop and evaluation scripts  
- Preprocessed dataset and configured data loaders  
- Performed experiment analysis and visualization  

---

## Quick Start
```bash
python train.py --epochs 50 --batch_size 32

Dataset Source and Citation (from original authors)
The CT images in this repository come from the publicly released COVID-CT-Dataset.
For dataset details and citation, please refer to the original publication:
COVID-CT-Dataset: A CT Scan Dataset about COVID-19
https://arxiv.org/pdf/2003.13865.pdf
Please cite the original authors if you use this dataset:
@article{zhao2020COVID-CT-Dataset,
title={COVID-CT-Dataset: a CT scan dataset about COVID-19},
author={Zhao, Jinyu and Zhang, Yichen and He, Xuehai and Xie, Pengtao},
journal={arXiv preprint arXiv:2003.13865},
year={2020}
}
Additional Notes
This project is intended for research and learning purposes only and should not be used for clinical decision-making.
 


