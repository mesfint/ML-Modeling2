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
###  Displaying the First Few Rows
  ```py
# Display the first few rows of the dataset
print(titanic_df.head())



  ```
- Explanation: The head() method displays the first five rows of the DataFrame, giving us a quick look at the structure and some sample data.
