# SpaceX Landing Prediction

Predicting the success of SpaceX Falcon 9 landings using historical launch data and machine learning.

## Overview

This project explores how machine learning can help predict whether a Falcon 9 rocket will land successfully. It uses launch data from SpaceX, analyzes key features that influence landing success, and builds classification models to make predictions.

The goal: help understand the conditions under which landings succeed—and what patterns show up in the data.

## What's Inside

* `landing_predictive_SPACEX.ipynb`: Full notebook with data cleaning, visualization, feature engineering, model building (Logistic Regression, SVM, Decision Tree, KNN), and evaluation.
* `spacex_launch_data.csv`: Raw data scraped and compiled from the SpaceX API and other sources, cleaned for analysis.

## Key Techniques Used

* Data preprocessing with Pandas
* EDA with Matplotlib and Seaborn
* Feature selection and One-Hot Encoding
* Model building using:

  * Logistic Regression
  * Support Vector Machines
  * Decision Tree Classifier
  * K-Nearest Neighbors
* Hyperparameter tuning with GridSearchCV
* Model evaluation using accuracy, F1 score, and classification reports

## Requirements

* Python 3.x
* Jupyter Notebook
* Libraries: pandas, numpy, matplotlib, seaborn, sklearn

Install dependencies with:

```bash
pip install -r requirements.txt
```

*(Note: You can generate a `requirements.txt` using `pip freeze > requirements.txt`)*

## How to Run

1. Clone the repo:

   ```bash
   git clone https://github.com/yourusername/SPACEX-Landing-Prediction.git
   cd SPACEX-Landing-Prediction
   ```

2. Open the notebook:

   ```bash
   jupyter notebook landing_predictive_SPACEX.ipynb
   ```

3. Run the cells step by step to follow the full workflow.

## Author

**Siddharthan P S**

Feel free to connect or fork the repo if you want to explore or expand the project further.

---

Let me know if you want to add a license, badges, or a section about future work or improvements.
