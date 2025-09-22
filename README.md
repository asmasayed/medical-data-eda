# Medical Data Visualizer

This project is part of the **FreeCodeCamp Data Science Certification**. It is **Project 3 of 5** required projects for the course: *Data Analysis with Python*.  

In this challenge, I analyzed a dataset of medical examinations to visualize key health indicators and identify patterns in cardiovascular risk factors. The project focuses on **categorical and correlation analysis** of patients’ health data.

---

## Project Description

The goal of this project is to create visualizations that show the distribution of various medical features and their relationship with cardiovascular disease (cardio). Key steps include:

1. **Importing the dataset** from `medical_examination.csv`  
2. **Feature Engineering**:  
   - Added an `overweight` column by calculating BMI  
   - Normalized `cholesterol` and `gluc` columns so that 0 = good, 1 = bad  
3. **Categorical Plot**:  
   - Created a categorical plot for variables: `cholesterol`, `gluc`, `alco`, `active`, `smoke`, and `overweight`  
   - Split by `cardio` outcome (0 = healthy, 1 = cardiovascular disease)  
   - Counted the number of people in each category using `pd.melt` and grouped the data appropriately  
4. **Heat Map**:  
   - Cleaned the data by filtering out incorrect or extreme measurements (e.g., diastolic > systolic, height/weight outliers)  
   - Calculated the correlation matrix of all numerical features  
   - Visualized correlations using a heatmap (`sns.heatmap`) with an upper triangle mask  

---

## Skills & Tools Learned
- **Python (Pandas, NumPy)** for data manipulation  
- **Data Cleaning & Feature Engineering**  
- **Exploratory Data Analysis (EDA)** for categorical and continuous data  
- **Data Visualization** with Seaborn and Matplotlib  
- **Correlation Analysis** for understanding feature relationships  

---

## Project Outcome
This project helped me:  

- Understand how to preprocess and clean real-world medical data  
- Learn to create **categorical plots** to compare groups  
- Use **correlation heatmaps** to identify feature relationships  
- Strengthen my confidence in handling datasets for data science projects  

---

Project instructions and challenge description can be found here:  
[FreeCodeCamp Medical Data Visualizer](https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/medical-data-visualizer)
