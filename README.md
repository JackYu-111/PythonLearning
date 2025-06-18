# Python Pandas Learning

Welcome to **Python Pandas Learning**, my personal journey of mastering Python and pandas for data analysis. This repository documents my self-study progress, capturing hands-on experiments with Jupyter Notebooks as I build skills for a career in Business or Data Analysis. Each notebook reflects a milestone in my learning, from importing data to manipulating DataFrames, driven by my passion for transforming raw data into actionable insights.

## My Learning Milestones

This repository contains Jupyter Notebooks (`*.ipynb`) in the root directory, each focusing on a key aspect of pandas. Below, I share what I explored, learned, and achieved in each notebook, reflecting my progress in mastering data analysis.

```
PythonLearning/
├── Learning1_import_data.ipynb                    # Importing data from various sources
├── Learning2_dataframe&series.ipynb               # Understanding Series and DataFrames
├── Learning3_query.ipynb                          # Querying and replacing data
├── Learning4_add new columns, replace data.ipynb  # Adding and sorting columns
└── README.md                                      # This file
```

## Learning Milestones

- **Learning1_import_data.ipynb**
  - **What I Explored**: Learned to import data from multiple formats: CSV, Excel (`.xlsx`), text files, and SQL databases.
  - **What I Learned**: Mastered `pd.read_csv()`, `pd.read_excel()`, `pd.read_table()`, and `pd.read_sql()`. I tackled challenges like handling missing headers and encoding issues in CSVs.
  - **Key Achievement**: Successfully loaded a sample CSV with student grades and an Excel file with sales data, displaying their contents in a notebook.
  - **Reflection**: This was my first step into data analysis. It showed me how versatile pandas is compared to Excel, which I used at SCB.

- **Learning2_dataframe&series.ipynb**
  - **What I Explored**: Dove into pandas’ core structures: Series (1D data) and DataFrames (2D tables).
  - **What I Learned**: Understood how Series work like columns and DataFrames like spreadsheets. I practiced creating DataFrames from dictionaries and accessing data with `.loc` and `.iloc`.
  - **Key Achievement**: Built a DataFrame of student records (e.g., names, grades) and extracted specific rows using indexing.
  - **Reflection**: Grasping the difference between Series and DataFrames was a lightbulb moment. It’s the foundation for all my later work.

- **Learning3_query.ipynb**
  - **What I Explored**: Focused on querying and replacing data in DataFrames.
  - **What I Learned**: Mastered filtering with boolean indexing (e.g., `df[df['Grade'] > 80]`) and replacing values with `df.replace()`. I also learned to handle missing data with `.fillna()`.
  - **Key Achievement**: Filtered a CSV to show high-performing students and replaced null values in a dataset, improving its quality.
  - **Reflection**: Querying felt like solving puzzles. It’s powerful for isolating specific data, like finding trends in SCB reports.

- **Learning4_add new columns, replace data.ipynb**
  - **What I Explored**: Added new columns to DataFrames and reordered existing ones, focusing on dynamic column manipulation.
  - **What I Learned**: Discovered how to add columns (e.g., `df['New_Column'] = ...`) and reorder them using `cols.pop()` and `cols.insert()`. I moved columns like 'Math_Grade' and 'Age' to specific positions and realized that excluding a popped column removes it permanently from the DataFrame.
  - **Key Achievement**: Reordered a DataFrame’s columns (e.g., placing 'Math_Grade' at index 1, 'Age' at index 2) and added a calculated column for grade averages.
  - **Reflection**: This was a big win! Manipulating columns dynamically makes data cleaning intuitive and connects to my business analysis goals.

## Will keep updating the self-learning progress
