# dataset-summary-report-day-7
Python and Pandas based dataset analysis project demonstrating data loading, exploration, structure inspection, descriptive statistics, data types, and missing value analysis using a student dataset.
# Dataset Summary Report – Day 7

## 📌 Overview

This project is a **Dataset Summary Report** created using **Python and Pandas**. The notebook demonstrates how to load a CSV dataset into a Pandas DataFrame and explore its basic structure and characteristics.

The analysis is performed on a student dataset containing information about student ID, name, age, course, marks, attendance percentage, and city.

## 🎯 Objectives

The main objectives of this project are to:

- Load a CSV dataset into a Pandas DataFrame
- Inspect the first few rows of the dataset
- Inspect the last few rows of the dataset
- View random samples from the dataset
- Check the dataset shape
- Examine column names
- Check the dataset index
- Identify the data types of each column
- Generate detailed dataset information using `info()`
- Generate descriptive statistics using `describe()`
- Identify missing values
- Record basic observations about the dataset

## 🛠️ Technologies Used

- **Python 3**
- **Pandas**
- **Google Colab**
- **CSV**

## 📂 Project Structure

```text
dataset-summary-report-day-7/
│
├── Dataset_Summary_Report_Day_7.ipynb
├── Day7_Student_Dataset.csv
└── README.md
```

### Files Description

**`Dataset_Summary_Report_Day_7.ipynb`**

Google Colab notebook containing the complete dataset exploration and summary analysis.

**`Day7_Student_Dataset.csv`**

The student dataset used for the analysis.

**`README.md`**

Documentation describing the project, dataset, analysis performed, and how to run the notebook.

## 📊 Dataset Overview

The dataset contains:

- **25 student records**
- **7 columns**

### Available Features

| Feature | Description |
|---|---|
| `Student_ID` | Unique identifier for each student |
| `Name` | Student name |
| `Age` | Age of the student |
| `Course` | Course enrolled by the student |
| `Marks` | Marks obtained by the student |
| `Attendance_Percentage` | Student attendance percentage |
| `City` | City associated with the student |

## 🔍 Data Exploration

The notebook performs the following analysis:

### 1. Loading the Dataset

The CSV file is loaded into a Pandas DataFrame using `pd.read_csv()`.

### 2. First Few Rows

The `head()` function is used to display the first five rows of the dataset.

### 3. Last Few Rows

The `tail()` function is used to display the last five rows of the dataset.

### 4. Random Samples

The `sample()` function is used to display five randomly selected records from the dataset.

### 5. Dataset Shape

The `shape` attribute is used to determine the number of rows and columns.

**Dataset shape:**

```text
(25, 7)
```

This indicates that the dataset contains **25 rows and 7 columns**.

### 6. Column Names

The `columns` attribute is used to display all available feature names.

The dataset contains the following columns:

```text
Student_ID
Name
Age
Course
Marks
Attendance_Percentage
City
```

### 7. Dataset Index

The `index` attribute is used to inspect the DataFrame index.

The dataset uses a default integer index ranging from **0 to 24**.

### 8. Data Types

The `dtypes` attribute is used to identify the data type of each column.

The dataset contains:

- Integer (`int64`) columns
- Floating-point (`float64`) columns
- Object/string (`object`) columns

### 9. Dataset Information

The `info()` function is used to examine:

- Number of entries
- Column names
- Non-null values
- Data types
- Memory usage

### 10. Descriptive Statistics

The `describe()` function is used to generate statistical summaries for the numerical columns, including:

- Count
- Mean
- Standard deviation
- Minimum
- 25th percentile
- Median
- 75th percentile
- Maximum

### 11. Missing Value Analysis

The `isnull().sum()` function is used to identify missing values in each column.

The analysis identifies missing values in:

- `Marks`
- `Attendance_Percentage`
- `City`

Each of these columns contains **one missing value**.

## 📌 Basic Observations

Based on the analysis:

- The dataset contains **25 student records and 7 columns**.
- The available features are `Student_ID`, `Name`, `Age`, `Course`, `Marks`, `Attendance_Percentage`, and `City`.
- `Student_ID` and `Age` are integer data types.
- `Marks` and `Attendance_Percentage` are floating-point data types.
- `Name`, `Course`, and `City` are object/string data types.
- Missing values are present in `Marks`, `Attendance_Percentage`, and `City`, with one missing value in each column.
- The dataset contains both numerical and categorical features.
- Among the available values, `Marks` range from **68 to 96**, while `Attendance_Percentage` ranges from **72 to 98**.

## 📈 Key Findings

The dataset provides a basic representation of student academic and attendance information.

The numerical features allow statistical analysis of student age, marks, and attendance, while categorical features such as course and city provide descriptive information about the students.

The missing-value analysis also demonstrates the importance of checking data completeness before performing further data analysis.

## ▶️ How to Run

### Using Google Colab

1. Open the `Dataset_Summary_Report_Day_7.ipynb` notebook in Google Colab.
2. Upload `Day7_Student_Dataset.csv` to the Colab environment if it is not already available.
3. Run the notebook cells sequentially.
4. Review the generated outputs and observations.

### Using Jupyter Notebook

1. Clone or download this repository.
2. Make sure `Dataset_Summary_Report_Day_7.ipynb` and `Day7_Student_Dataset.csv` are in the same directory.
3. Open the notebook using Jupyter Notebook or JupyterLab.
4. Run the cells sequentially.

## 🎓 Learning Outcomes

Through this project, the following Pandas concepts were practiced:

- Reading CSV files
- Creating and working with DataFrames
- Inspecting DataFrame structure
- Accessing rows and columns
- Understanding DataFrame indexes
- Identifying data types
- Generating descriptive statistics
- Inspecting missing values
- Summarizing and interpreting a dataset

