# NLP Classification Project

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Polenoz/Natural-Language-Processing/blob/main/Nlp_Projekt.ipynb)

This repository reproduces the Natural Language Processing exercise from the course `Python für Data Science, Maschinelles Lernen & Visualization` for `Prüfungsaufgabe 1`.

## Overview

This project demonstrates how to build and evaluate a text classification model using natural language processing techniques. The notebook includes data loading, text cleaning, feature extraction, model training, and evaluation.

## Contents

- `Nlp_Projekt.ipynb`: Jupyter notebook with the full workflow
- `Yelp.csv`: Dataset used for text classification
- `requirements.txt`: List of required Python packages

## Dataset

The dataset (`Yelp.csv`) contains text reviews and their corresponding labels. It is loaded directly from the repository when running the notebook.

## How to Run

### Google Colab (Recommended)

1. Click the **Open in Colab** badge above.
2. The notebook will open in Google Colab.
3. Run all cells from top to bottom in order.
4. No manual data upload is required.

### Local (Jupyter)

1. Clone or download this repository.
2. Install the dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebook with Jupyter:

```bash
jupyter notebook Nlp_Projekt.ipynb
```

4. Run all cells from top to bottom.

## Expected Results

The notebook should reproduce the NLP classification example on the Yelp review dataset and show:

- data exploration and visualizations
- text cleaning and preprocessing
- feature extraction
- training and evaluation of a classification model
- confusion matrix
- classification report

Example output:

```text
[[  0 228]
 [  0 998]]

              precision    recall  f1-score   support

           5       0.81      1.00      0.90       998
    micro avg       0.81      1.00      0.90       998
    macro avg       0.81      1.00      0.90       998
 weighted avg       0.81      1.00      0.90       998
```

## Notes

This repository is intended as one of the required exercise repositories for `Prüfungsaufgabe 1`.
