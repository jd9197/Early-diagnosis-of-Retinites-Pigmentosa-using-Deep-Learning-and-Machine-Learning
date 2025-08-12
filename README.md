# Retinitis Pigmentosa Detection

## Overview
This project implements an AI-based system to detect and segment Retinitis Pigmentosa (RP) features from fundus images.  
It combines advanced deep learning models for precise pigment sign segmentation and classification to assist ophthalmologists.

## Features
- Image preprocessing and augmentation
- Segmentation using ResUNet-50, EfficientNet-B0, and custom CNN/DNN models
- Classification of disease stages
- Evaluation metrics (accuracy, IoU, Dice score)

## Dataset
- Publicly available fundus image datasets  
- Preprocessing steps for noise reduction and normalization

## Installation
```bash
git clone https://github.com/username/Retinitis-Pigmentosa-AI.git
cd Retinitis-Pigmentosa-AI
pip install -r requirements.txt
