If the Google Colab link does not work, use this: [Task 2 (Google Colab)](https://colab.research.google.com/drive/1XxgNNjnRjR8KgX0En-KlVlbC6di3XNtK?usp=sharing)

## Task 2: Data Cleaning & Missing Value Handling 📊

### Key Learnings

**Loading the Dataset and Identifying Missing Values 🔍**
- Learned how to load the dataset using pandas.
- Used `.isnull().sum()` to identify missing values in each column.

**Visualizing Missing Data 📈**
- Created simple bar charts to understand the pattern of missing values.
- This helped in deciding how to handle missing data effectively.

**Handling Missing Values (Numerical & Categorical) 🛠️**
- Filled missing values in numerical columns using the **median**.
- Filled missing values in categorical columns using the **most frequent value (mode)**.
- This made the dataset more consistent and ready for analysis.

**Removing Columns with High Missing Values ✂️**
- Identified columns with extremely high missing values.
- Removed those columns to improve data quality and usefulness.

**Validating the Cleaned Dataset ✅**
- Checked for remaining missing values.
- Verified dataset shape, data types, duplicates, and basic statistics.
- This confirmed that the dataset is clean and reliable.

**Comparing Before and After Cleaning 🔄**
- Compared the dataset before and after cleaning.
- Checked the number of rows, columns, and total missing values.
- This showed that the data quality improved after cleaning.
