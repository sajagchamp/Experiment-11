
# **AIM:**

To create a dataset using Pandas, convert it into CSV format, and perform exploratory data analysis using various Pandas functions.

---

# **THEORY:**

* **pd.DataFrame():** Creates a tabular data structure (DataFrame) from dictionaries, lists, or arrays.

* **print():** Displays output or results on the console.

* **df.to_csv():** Converts a DataFrame into a CSV (Comma Separated Values) file.

* **index=False:** Prevents the DataFrame index from being written into the CSV file.

* **df.shape:** Returns the number of rows and columns in the dataset.

* **df.size:** Returns the total number of elements present in the dataset.

* **df.info():** Displays summary information such as column names, data types, and non-null values.

* **df.describe():** Generates statistical summary (mean, standard deviation, min, max, quartiles) for numeric columns.

* **df.duplicated():** Identifies duplicate rows in the dataset.

* **sum():** Calculates the total count of duplicate values when used with duplicated().

* **pd.read_csv():** Reads a CSV file and loads it into a DataFrame.

* **display():** Shows DataFrame output in a formatted tabular style (mainly used in Jupyter/Colab).

* **df.head():** Displays the first five rows of the dataset.

* **df.tail():** Displays the last five rows of the dataset.

* **df.sample():** Returns randomly selected rows from the dataset.

* **df.isnull():** Detects missing (null) values in the dataset.

* **df.isnull().sum():** Counts the number of null values in each column.

* **df.columns:** Returns the names of all columns in the dataset.

* **df.nunique():** Displays the number of unique values present in each column.

---

# **CONCLUSION :**

In this experiment, a dataset was created using Pandas and converted into CSV format. Various DataFrame operations such as checking shape, size, column names, and duplicate values were performed. Statistical analysis and data inspection were carried out using functions like describe(), head(), and sample(). Pandas proved to be an effective tool for analyzing and managing structured datasets.

---
