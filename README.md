# ML Practice

Small machine learning practice notebooks — learning ML step by step in Python (pandas, scikit-learn, matplotlib, seaborn).

## Contents

- `ML.ipynb` — data preparation (missing values, one-hot encoding, scaling), training a simple linear regression model to predict salary, and visualizing actual vs predicted salaries.
- `lesson-03-train-test-split.ipynb` — train-test split (Lesson 3): split the prepared data into train/test sets and evaluate the linear regression model on unseen data.
- `lesson-04-linear-regression.ipynb` — linear regression (Lesson 4): fit a model on age only, read the slope (coef_) and intercept, and predict salary at age 28.
- `lesson-05-cost-function-gradient-descent.ipynb` — cost function & gradient descent (Lesson 5): gradient descent by hand for linear regression; with learning rate 0.0001 it converges very slowly (m ≈ 1.46, MSE ≈ 1.12 after 1,000 steps).
- `lesson-06-overfitting-underfitting.ipynb` — overfitting / underfitting (Lesson 6): polynomial regression at degrees 1, 3 and 15; train R² rises with degree while test R² collapses at degree 15 — the overfitting demo.
- `lesson-07-logistic-regression.ipynb` — logistic regression (Lesson 7): classification with sigmoid + probability; breast cancer dataset, accuracy ≈ 0.967 with test_size=0.7.
- `lesson-08-evaluation-metrics.ipynb` — evaluation metrics (Lesson 8): confusion matrix + classification report on the Lesson 7 model; accuracy ≈ 0.96, precision 0.97/0.95 and recall 0.91/0.99 per class (test_size=0.2).

## Run it

Open `ML.ipynb` in [Google Colab](https://colab.research.google.com/) or Jupyter, and run the cells top to bottom.

## Requirements

See `requirements.txt`. Install with:

```bash
pip install -r requirements.txt
```
