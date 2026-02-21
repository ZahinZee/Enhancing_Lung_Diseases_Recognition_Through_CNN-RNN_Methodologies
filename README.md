# Enhancing_Lung_Diseases_Recognition_Through_CNN-RNN_Methodologies
## Overview: 
This project implements a hybrid Convolutional Neural Network (CNN) + Recurrent Neural Network (RNN) architecture for multiclass classification of chest X-ray images.

The model classifies images into:
COVID, Lung Opacity, Normal & Viral Pneumonia

The goal is to combine: CNN → spatial feature extraction and RNN (LSTM) → sequential/patch-based dependencies to improve diagnostic performance.

## Dataset
Experiments use the COVID-19 Radiography Dataset from Kaggle
### Download:
https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database

## Installation
1. Clone repository

```
git clone <repo-url>
```

2. Install dependencies
```
pip install -r requirements.txt
```
3. Download dataset

Download manually from Kaggle and extract into the project folder.

## Running the Code

1. Start Jupyter:

```
jupyter notebook
```

2. Open:

```
Enhancing_Lung_Diseases_Recognition_Through_CNN-RNN_Methodologies.ipynb
```
Run all cells sequentially.

## Citation

If you use this work, please cite the associated paper or dataset.

## License

For research and educational use only.
