# AI-Powered CSV Data Analyzer

## 1. Project Introduction
The AI-Powered CSV Data Analyzer is a Python-based project that reads, cleans, analyzes, and visualizes data from a CSV file.

This project uses a Social Media Analysis dataset to understand social media usage patterns and predict students' academic performance using Machine Learning.

## 2. Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 3. Dataset Information
- Dataset Name: Social Media Analysis
- Total Rows: 1,605
- Total Columns: 22

The dataset contains information about students, social media usage, sleep hours, study hours, social media platforms, and academic performance.

## 4. Implementation Steps

### Step 1: Read the CSV File
Used Pandas to load the CSV dataset into a DataFrame.

### Step 2: Data Cleaning
- Checked missing values.
- Checked duplicate records.
- Removed duplicate records.
- Cleaned column names and text values.

Result: No missing values or duplicate records were found.

### Step 3: Data Analysis
Generated five meaningful insights:
1. Average daily social media usage is 4.87 hours.
2. Average sleep duration is 6.90 hours.
3. Average daily study time is 2.94 hours.
4. Instagram is the most-used platform.
5. Poor academic performance has the highest number of records (452).

### Step 4: Data Visualization
Created three visualizations:
1. Bar chart showing the most-used social media platforms.
2. Histogram showing daily social media usage.
3. Count plot showing academic performance.

### Step 5: Machine Learning
Implemented a Random Forest Classifier to predict academic performance.

The dataset was divided into training and testing data. A preprocessing pipeline was used for numerical and categorical features.

Model Accuracy: 81.93%

## 5. How to Run the Project

1. Install Python and Jupyter Notebook.
2. Download the project files.
3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

4. Keep the CSV file and notebook in the same folder.
5. Open Jupyter Notebook.
6. Open the project notebook.
7. Run all cells one by one.

## 6. Project Folder Structure

```text
AI-Powered-CSV-Data-Analyzer/
│
├── Social-media-Analysis.ipynb
├── Social_Media_Analysis.csv
└── README.md
```

## 7. Conclusion
This project helped me learn how to clean, analyze, and visualize data using Python. I also implemented a Random Forest Machine Learning model to predict academic performance.