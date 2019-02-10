# Project: Titanic Survival Exploration

This is an exercise for Udacity's Nanadegree: Artificial Intelligence Programming with Python.

## Objective

Create a decision function to try to predict survivors of the 1912 Titanic disaster based on passenger attributes such as sex and age.

## Environment

This project requires **Python 3** and the following Python libraries installed:

- [Jupyter Notebook](http://ipython.org/notebook.html)
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

## Running on your own

After installed all environment libraries, run the following command:

```bash
jupyter notebook titanic_survival_exploration.ipynb
```

## Data Set

The dataset used in this project is `titanic_data.csv` file and contains the following attributes:

**Features**
- `pclass` : Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)
- `name` : Name
- `sex` : Sex
- `age` : Age
- `sibsp` : Number of Siblings/Spouses Aboard
- `parch` : Number of Parents/Children Aboard
- `ticket` : Ticket Number
- `fare` : Passenger Fare
- `cabin` : Cabin
- `embarked` : Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

**Target Variable**
- `survival` : Survival (0 = No; 1 = Yes)
