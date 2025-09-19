# Brain-Tumor-Classification

This repository contains the implementation of three deep learning models—ViT-Base, ResNet-50, and DenseNet-121—for classifying brain tumors from MRI images. The code focuses on the first dataset and includes training, evaluation, and model configuration.

## 📁 Repository Structure
ensemble_method.ipynb
```
tumor-classification
├── DenseNet-121
│   ├── DenseNet-121.pretrained.ipynb              
│   └── DenseNet-121.random.ipynb           
├── ResNet-50
│   ├── ResNet-50.pretrained.ipynb            
│   └── ResNet-50.random.ipynb   
├── ViT-Base
│   ├── ViT-Base.pretrained.ipynb          
│  └── ViT-Base.random.ipynb
├── ensemble_method.ipynb
└── README.md                 # Project overview
```

## 📊 Datasets

This project uses two labeled brain MRI datasets:

- SARTA Dataset: Available on [Kaggle](https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri/discussion?sort=hotness)  
  This dataset includes MRI images categorized into four classes: Glioma, Meningioma, Pituitary, and No Tumor.
  It is relatively compact and suitable for initial training and quick experimentation.

- Brain Tumor MRI Dataset: Available on [Kaggle](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset/data?select=Training)  
  It is ideal for extended training and deeper evaluation of model performance.

## 📌 Note

All models are implemented in separate notebooks. Pretrained and randomly initialized versions are provided for each architecture.
