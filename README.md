# Project 6 EDA Notebook

## Analysis of Diamonds dataset

## Overview
In project 6 I will create my own custom exploratory data analysis (EDA) project using GitHub, Git, Jupyter, pandas, Seaborn and other popular data analytics tools.

## Bukola Adeniyan

## Environment Setup
1. Created a new repo in GitHub with the name 'datafunn-06-EDA' on Git Hub.
1. Added the default README.md
1. Cloned project down to my machine (git clone site_URL)
1. Named the script "bykola_eda.ipynb"
1. Create and activate the project's virtual environment.
1. Install all required packages into your local project virtual environment.
1. After installing the required dependencies, update or generate a requirements.txt file.
1. Add a .gitignore file to your project with useful entries. See .gitignore example.
1. Document the steps and commands in your README.md.

## Created and activated a Python virtual environment
Used the following command to create a virtual environment:
```shell

py -m venv .venv

```
Used the following command to activate the virtual environment:
```shell

.venv\Scripts\activate 

```

## Created a requirements.txt file
Created a new file in the root project folder labeled requirements.txt

Listed the required external dependencies in this file

## Installed external dependencies in the requirements.txt file and froze
Installed dependencies using the following command:
```shell

py -m pip install jupyterlab pandas pyarrow matplotlib seaborn

```
Froze the requirements.txt file using the following command:
```shell

py -m pip freeze > requirements.txt

```

## Created .gitignore
Created a new file in my datafunn-06-eda-project folder named .gitignore

Typed .venv/ into line 1

Typed .ipynb_checkpoints/ into line 2

## Git add and commit changes
Git add and commit my initial changes with the following commands:
```shell

git add .
git commit -m "initial commit"

```

## Git push changes to GitHub
Git push your initial changes to GitHub with the following command:
```shell

git push origin main

```

## Chose a data set
Chose a data set that is pre-installed in Seaborn, using a well-known and clean dataset.
This'Diamonds.csv' dataset, contains various attributes of diamonds, including carat, cut, color, clarity, depth, table, price, and dimensions (x, y, z).

## Imported local dependencies and loaded data
Imported required local dependencies and loaded the required data into vs code.

```shell
import matplotlib.pyplot as plt
import pandas as pd
import seaborn as sns

# Load the dataset into a pandas DataFrame - adjust this process for your custom data
df = sns.load_dataset('Diamonds')

# Inspect the first rows of the DataFrame
print(df.head())

```

## Performed an initial data inspection
Took a quick look at the first 10 rows of the data, displayed the shape of the data, and inspected the type of data in each column. 

```shell

print(df.head(10))
print(df.shape)
print(df.dtypes)

```

## Performed an initial inspection of the data's descriptive statistics
Took a quick look at the data's summary statistics for each numerical column. This includes count, mean, standard deviation, minimum, and maximum. 

```shell

print(df.describe())

```

## Created various histograms for data distribution analysis
Created multiple histograms to analyze the data distribution of both the numerical columns and categorical columns.

## Data transformation and feature engineering
Transformed the data by renaming a column and adding one additional column.

## Created visualizations to present data and tell a story
Created scatter plots and box plot to illustrate the data analysis. Extensive data manipulation was also performed to ensure data integrity. 

## Repeated Git add and commit
Periodically add, commit, and push files from my machine to the associated online repo using the following commands:
```shell

git add .
git commit -m "add comments here"
git push origin main

```

## Created Module 6 project according to the following specifications:
- [datafun-06-spec](https://github.com/denisecase/datafun-06-spec)
