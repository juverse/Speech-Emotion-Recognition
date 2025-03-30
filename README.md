# Speech-Emotion-Recognition
In this project, we propose an emotion recognition system to model the Urdu
language using languages such as German, English and Italian. We want to see if we can
generalize across languages.  This project replicates the Paper "Cross Lingual Speech Emotion Recognition: Urdu vs. Western Languages.

## Tabel of Contents
- [Installation](#installation)
- [Features](#features)
  
## Installation
#### 1. Clone the repository 
```bash
 git clone (https://github.com/juverse/Speech-Emotion-Recognition.git
```
#### 2. Install dependencies:
To run this project, the following dependencies are required. It is recommended to create a conda environment to manage the dependencies.

Python 3.11.11
XGBoost: 2.1.1
scikit-learn: 1.6.1
pandas: 2.2.3
matplotlib: 3.10.0
NumPy: 1.26.4
SciPy: 1.15.2
imbalanced-learn: 0.13.0
shap: 0.46.0

## Features
#### Data Preprocessing
In this folder, we explore, prepare the data, and generate features.

#### Experiments
In this folder, we replicate the experiments from the original paper. In the file baseline_replication.ipynb, you will find the exact same procedure. However, as we made some improvements, we implemented a slightly different approach in baseline.ipynb.

#### Evaluation
In this folder, we evaluate the feature importances for the baseline model and the results of all experiments.



