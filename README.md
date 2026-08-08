# Academic Performance Predictor

A Machine Learning-based application that predicts student academic performance using academic and demographic factors. The project analyzes student data, predicts performance levels, and automatically generates personalized student report cards with teacher remarks and improvement suggestions.

## Project Overview

Educational institutions often find it difficult to identify students who may require additional academic support. This project uses Machine Learning to analyze student-related features and predict academic performance, helping educators identify students who need early intervention.

The application also generates professional PDF report cards containing:

- Student Details
- Academic Details
- Predicted Performance
- Teacher Remarks
- Personalized Suggestions

## Features

- Student Performance Prediction using Machine Learning
- Data Preprocessing and Feature Engineering
- Automatic Prediction on New Student Data
- Personalized Teacher Remarks
- Personalized Improvement Suggestions
- Automatic PDF Report Card Generation
- CSV Export of Prediction Results
- Data Visualization
- Model Evaluation using Classification Metrics

## Technologies Used

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- ReportLab
- Jupyter Notebook

## Project Structure

Academic-Performance-Predictor/
│── data/
│ ├── Students_Database.csv
│── notebooks/
│ ├── Student_Performance_Prediction.ipynb
│── outputs/
│ ├── Student_Report_Output.csv
│ ├── FINAL_REPORT_CARDS.pdf
│── screenshots/
│── README.md
│── requirements.txt

## Workflow

1. Load Student Dataset
2. Data Cleaning
3. Handle Missing Values
4. Feature Selection
5. Data Preprocessing
6. Train-Test Split
7. Train Machine Learning Model
8. Predict Student Performance
9. Generate Teacher Remarks
10. Generate Suggestions
11. Export Results to CSV
12. Generate PDF Report Cards

## Evaluation Metrics

The model can be evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
