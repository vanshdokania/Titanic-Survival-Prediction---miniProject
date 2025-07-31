# Titanic Survival Prediction 

A machine learning mini-project that predicts survival of passengers on the Titanic using Python and scikit-learn.

## Dataset
- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/alyelbadry/titanic-survive-model)
- `train.csv` and `test.csv` used for training and testing

## Approach
- Preprocessed categorical data (Sex, Embarked)
- Handled missing values
- Dropped unnecessary columns (Name, Ticket, etc.)
- Trained a Logistic Regression model

## Tools & Libraries
- Python
- Pandas
- NumPy
- scikit-learn
- Matplotlib / Seaborn (for visualization)

## Accuracy
- Achieved ~80.17676767676768% accuracy on the train set and ~77.77777777777778% accuracy on the test set

## How to Run
```bash
pip install -r requirements.txt
# Then run the Jupyter Notebook
