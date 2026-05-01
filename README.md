# Group 8: Movie Financial Success Prediction
Tamanna Singh and Angie Avalos Joel

## Structure
```
term-project-team-8/
│
├── Project Assignments/
|   |-- P1_replot-scatter.ipynb
|   |-- P2_categorical_interactive_transform.ipynb
|   |-- P3_interactive.ipynb
│   └── machine_learning.ipynb
├── movies.csv
└── movies_metadata.csv
```
## Description
The film industry is a multi-billion-dollar market where investments carry significant financial risk. 
High budgets do not always guarantee financial success, and some films with large budgets fail to return high revenue, while other smaller productions can be profitable. 

We investigate the questions: 

This project analyzes movie datasets to identify factors that influence financial success and uses machine learning models to predict whether a movie will be profitable.
The questions being focused upon for this project are:

1. Which movie attributes (budget, popularity, vote count, etc.) have the strongest influence on profitability? 
2. How strongly does production budget influence box office revenue?
3. Can we accurately predict whether a movie will be financially successful using machine learning models? 
4. Does movie popularity correlate with financial success? 5. 
5. Are certain genres more likely to produce profitable films than others?


## Datasets
- movies.csv
- movies_metadata.csv
www.kaggle.com/datasets/rounakbanik/the-movies-dataset?select=movies_metadata.csv. 
https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset 


## Required libraries:
Packages And Libraries 
Pandas 
Plotly 
Numpy 
Seaborn 
Scikit-learn 
Matplotlib
Hvplot 
pip install pandas plotly numpy seaborn scikit-learn matplotlib
pip install panel hvplot

## Instructions On How To Run The Code 
1. Open the Jupyter Notebook or upload the notebook to Google Colab
2. Install the following required Python libraries if they are not already installed.
Pandas 
Plotly 
Numpy 
Seaborn 
Scikit-learn 
Matplotlib
3. The dataset files movies.csv and movies-metdata.csv must be placed in the same directory as the notebook.
4. Run each cell in order from top to bottom.
5. Visualizations and interactive plots created can be viewed after running.
6. The machine learning cells will output model performance including accuracy, confusion matrices, and classification reports.

## Interactive Visualization
An interactive scatter plot allows users to filter movies by genre to see how the budget and revenue change based on altering the genre 

## 3 Machine Learning Models Used
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

Models were evaluated using 5-fold cross-validation.

## Expected Outputs
- Data Visualizations
- Interactive Plot
- Accuracy, precision, recall, F1-score
- Confusion matrix
