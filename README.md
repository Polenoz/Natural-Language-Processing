
# NLP Classification Project

**Note:** This project was developed and tested primarily in **Google Colab**. All instructions and code are fully compatible with Colab, and the recommended way to run and reproduce results is via the Colab badge below.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Polenoz/Natural-Language-Processing/blob/main/Nlp_Projekt.ipynb)

## Overview
This project demonstrates how to build a text classification model using natural language processing techniques. The notebook includes data loading, text cleaning, feature extraction, model training, and evaluation.

## Contents
- `Nlp_Projekt.ipynb`: Colab notebook with the full workflow
- `Yelp.csv`: Dataset used for text classification
- `requirements.txt`: List of required Python packages

## Dataset
The dataset (`Yelp.csv`) is loaded automatically from the repository when running in Colab.

## How to Run

### Google Colab (Recommended)
1. Click the **Open in Colab** badge above.
2. The notebook will open in Google Colab.
3. Run all cells from top to bottom. The dataset loads automatically from the repository.
4. No manual data upload or extra setup is required.

### Local (Jupyter, also possible)
1. Clone or download this repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Open the notebook with Jupyter: `jupyter notebook Nlp_Projekt.ipynb`
4. Run all cells.

## Expected Results
- Data exploration and visualizations of text data
- Text cleaning and feature extraction
- Training and evaluation of a classification model
- Example output:

```
[[  0 228]
 [  0 998]]
 
              precision    recall  f1-score   support

           5       0.81      1.00      0.90       998

   micro avg       0.81      1.00      0.90       998
   macro avg       0.81      1.00      0.90       998
weighted avg       0.81      1.00      0.90       998

```

- Classification report
- Precision and recall
