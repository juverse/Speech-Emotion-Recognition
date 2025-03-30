# Speech-Emotion-Recognition
In this project, we propose an emotion recognition system to model the Urdu
language using languages such as German, English and Italian. We want to see if we can
generalize across languages.  This project replicates the Paper "Cross Lingual Speech Emotion Recognition: Urdu vs. Western Languages.

## Tabel of Contents
- [Installation](#installation)
- [Features](#features)
- [Main Results](#results)
- [Critic](#critic)
  
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

## Code
#### Data Preprocessing
In this folder, we explore, prepare the data, and generate features.

#### Experiments
In this folder, we replicate the experiments from the original paper. In the file baseline_replication.ipynb, you will find the exact same procedure. However, as we made some improvements, we implemented a slightly different approach in baseline.ipynb.

#### Evaluation
In this folder, we evaluate the feature importances for the baseline model and the results of all experiments.

## Main Results

## Critic
The models were tested on a variety of languages, but many of the datasets are small and not representative of the broader linguistic diversity. This is especially true for Urdu, which is a relatively under-researched language in this context. Additionally, Urdu contains many English sequences, which may have influenced the performance of the models.
In this paper, we compared three Western languages—German, English, and Italian—with Urdu. The original paper referred to these as "Western languages." However, it is important to clarify a few points.
Urdu is the national language of Pakistan and is spoken by millions of people. Therefore, it is not a "small language" in terms of the number of speakers. However, compared to languages like English, it has been less extensively researched in the field of computational linguistics. This lack of research and available datasets may have impacted the results of our study.
Additionally, it is worth noting that Urdu often includes English sequences, which could have influenced model performance. Given these factors, our findings should be interpreted with caution, and further studies with more comprehensive and balanced datasets are necessary.


