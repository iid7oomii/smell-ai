# smell-ai# 🧪 Odor Classification with Machine Learning

Predicting odor categories from molecular structure using the Leffingwell dataset.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iid7oomii/smell-ai/blob/main/smell_ai.ipynb)

## What this project does
Trains a Random Forest classifier on 2,512 molecules to predict
whether a molecule smells fruity, floral, sweet, green, or fatty —
using only its chemical properties (LogP, molecular weight, etc.)

## Results
| Model | Accuracy |
|---|---|
| Random Forest | **66.4%** |
| Gradient Boosting | 63.9% |
| KNN | 51.3% |
| SVM | 26.9% |
| Random baseline | 20.0% |

## Key finding
LogP (fat solubility) is the strongest predictor of odor category.

## Dataset
[Pyrfume / Leffingwell](https://github.com/pyrfume/pyrfume-data)
— 3,522 molecules, 113 odor descriptors

## How to run
Click the Colab badge above — no installation needed.
