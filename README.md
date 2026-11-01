# Student Performance Analysis – Exploratory Data Analysis (EDA)

## Project Overview
This project performs Exploratory Data Analysis (EDA) on the Students Performance dataset using Python. The main objective is to analyze students' academic performance in Mathematics, Reading, and Writing and understand the factors that influence their scores.

## Tools and Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset Description
The dataset contains students' performance information, including:
- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch Type
- Test Preparation Course
- Math Score
- Reading Score
- Writing Score

## Steps Performed

### 1. Data Loading
Imported the required Python libraries and loaded the Students Performance dataset using Pandas.

### 2. Data Inspection
- Displayed the first five records.
- Checked dataset shape and information.
- Generated descriptive statistics.
- Checked column names and missing values.

### 3. Data Cleaning
- Converted categorical values into lowercase.
- Removed unnecessary spaces.
- Checked unique values in categorical columns.
- Checked for duplicate records.

### 4. Statistical Analysis
Calculated:
- Mean
- Median
- Standard Deviation
- First Quartile (Q1)
- Second Quartile (Q2)
- Third Quartile (Q3)

### 5. Feature Engineering
Created two new columns:
- **Total Marks:** Sum of Mathematics, Reading, and Writing scores.
- **Percentage:** Calculated students' overall percentage out of 300 marks.

### 6. Outlier Detection
Used the Interquartile Range (IQR) method to identify outliers in Mathematics, Reading, and Writing scores.

### 7. Data Visualization
Created the following visualizations:
- Bar Chart – Average Scores by Parental Education.
- Bar Chart – Average Scores by Lunch Type.
- Box Plot – Test Preparation Course vs Subject Scores.
- Scatter Plot – Mathematics vs Reading Scores.
- Scatter Plot – Mathematics vs Writing Scores.
- Scatter Plot – Reading vs Writing Scores.
- Heatmap – Correlation Between Subject Scores.

  <img width="348" height="253" alt="Screenshot 2026-11-01 131607" src="https://github.com/user-attachments/assets/a154fb2a-98e4-4729-862d-edf0b4c3bb29" />
<img width="335" height="265" alt="Screenshot 2026-11-01 131420" src="https://github.com/user-attachments/assets/aaacf7d0-117a-403e-9d14-fb37fa6db72b" />
<img width="344" height="256" alt="Screenshot 2026-11-01 131403" src="https://github.com/user-attachments/assets/aee652ce-0604-4113-b31c-8e4499774580" />
<img width="339" height="263" alt="Screenshot 2026-11-01 131348" src="https://github.com/user-attachments/assets/97aa9d6f-9760-406c-ae9b-627b5768bdbd" />
<img width="323" height="236" alt="Screenshot 2026-11-01 131232" src="https://github.com/user-attachments/assets/97430e7a-f591-4850-97b4-4c8da0617ba1" />
<img width="329" height="229" alt="Screenshot 2026-11-01 131214" src="https://github.com/user-attachments/assets/871a0d37-41ef-4171-b23a-1b387eb3304e" />
<img width="339" height="247" alt="Screenshot 2026-11-01 131154" src="https://github.com/user-attachments/assets/810656c4-c72d-4754-b14f-bba8ede9b053" />
<img width="338" height="212" alt="Screenshot 2026-11-01 131007" src="https://github.com/user-attachments/assets/5303e7a8-d330-46fd-a50c-bdc090903eff" />
<img width="575" height="287" alt="Screenshot 2026-11-01 130840" src="https://github.com/user-attachments/assets/e7ea96e5-e0ba-4b19-93ea-85f136ec197d" />


### 8. Data Export
Saved the processed dataset as:

`Student_Performance_Cleaned.csv`

## Project Outcome
This project helps understand students' academic performance through statistical analysis and visualization. It explores the relationship between parental education, lunch type, test preparation, and students' subject scores.

## Conclusion
Exploratory Data Analysis provides useful insights into student performance. By using Python libraries, the dataset can be cleaned, analyzed, and visualized effectively.

---

