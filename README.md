# Hospital Data Analysis

## Project Description

This project analyzes hospital patient data using Python and data analysis libraries.

The dataset contains information about patients, including:

- Patient ID
- Age
- Sex
- Blood Pressure
- Cholesterol
- Diagnosis

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

## Data Analysis

The project performs the following analyses:

- Displaying the first patient records using `df.head()`
- Computing statistical summaries using `df.describe()`
- Counting patients by sex
- Counting patients by diagnosis
- Visualizing the relationship between age and cholesterol

## Results

The dataset contains 10 patients.

### Patients by Sex

- Male: 5
- Female: 5

### Patients by Diagnosis

- Healthy: 4
- Diabetes: 3
- Hypertension: 3

### Main Statistics

- Average age: 47.5 years
- Average blood pressure: 138.5
- Average cholesterol: 221

## Project Structure

```text
HospitalDataAnalysis/
├── data/
│   └── patients.csv
├── notebooks/
│   └── patients_analysis.ipynb
├── .gitignore
├── requirements.txt
└── README.md