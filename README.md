# 🎵 Music Recommendation ML Project

This repository contains a simple machine learning project that uses demographic features to predict a user's music preferences. The model is trained using a decision tree classifier.

## 📁 Files

- `ML.ipynb` - Main Jupyter Notebook containing the full workflow: data loading, preprocessing, model training, and visualization.
- `music.csv` - Dataset containing features like age, gender, and music preferences.

## 📊 Dataset Overview

The dataset includes the following columns:

- `age` (int): Age of the individual
- `gender` (str): Gender of the individual (`male`/`female`)
- `genre` (str): Preferred music genre (target variable)

## 🧠 Model

- **Model Used**: Decision Tree Classifier (`sklearn.tree.DecisionTreeClassifier`)
- **Libraries**: `pandas`, `scikit-learn`, `matplotlib`

The model is trained to predict the genre of music a person is likely to enjoy based on their age and gender.

## 📈 Features

- Data preprocessing using `LabelEncoder`
- Model training and prediction
- Visualization of the decision tree

## 🚀 Getting Started

### Prerequisites

Install the necessary Python packages:

```bash
pip install pandas scikit-learn matplotlib
