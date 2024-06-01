# Titanic Dataset - Classification Data model
## 1. Data Exploration & Visualization.
###  Loading the Dataset
  ```py
import pandas as pd

# Load the dataset
url = "https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv"
titanic_df = pd.read_csv(url)


  ```
-  Explanation: We import the pandas library and load the Titanic dataset from a URL into a DataFrame named "titanic_df".
