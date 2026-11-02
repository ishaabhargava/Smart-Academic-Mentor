# Smart Academic Mentor 🎓

An intelligent academic performance analysis system built using Python and Machine Learning. The project analyses student data, identifies performance patterns, groups students based on academic characteristics, and evaluates machine learning models to predict academic outcomes.

## Project Overview

Smart Academic Mentor aims to support academic performance analysis by combining unsupervised and supervised machine learning techniques.

## Key Features

- **Data Preprocessing:** Handles missing values, encodes categorical variables, and prepares data for machine learning.
- **Exploratory Data Analysis:** Examines student performance, academic trends, and relevant features.
- **K-Means Clustering:** Groups students into three performance categories: At-Risk, Average, and High-Performing.
- **Classification Models:** Trains and compares machine learning models for academic outcome prediction.
- **Model Evaluation:** Uses accuracy metrics, confusion matrices, and performance comparisons.
- **Feature Analysis:** Identifies important factors associated with academic performance.
- **Subject Analysis:** Examines performance across different subjects.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data manipulation |
| NumPy | Numerical computation |
| Scikit-learn | Machine learning |
| Matplotlib | Data visualisation |
| Seaborn | Statistical visualisation |
| Jupyter Notebook | Development and experimentation |

## Project Structure

```text
Smart_Academic_Mentor/
│
├── data/
│   └── student_data.csv
│
├── notebooks/
│   ├── aiml.ipynb
│   └── aiml2.ipynb
│
├── outputs/
│   └── Generated graphs and visualisations
│
├── report/
│   └── project_report_aiml.html
│
├── requirements.txt
├── README.md
└── .gitignore
```

## Machine Learning Approach

### 1. Unsupervised Learning
K-Means clustering is used to segment students into three academic performance groups.

### 2. Supervised Learning
Classification algorithms are trained to predict academic outcomes using student-related features.

### 3. Model Evaluation
Models are evaluated and compared using appropriate classification metrics and confusion matrices.

## Project Outputs

The `outputs/` directory contains visualisations generated during the analysis, including:

- K-Means clustering results
- Cluster profiles
- Classification performance
- Confusion matrices
- Model comparison graphs
- Feature importance analysis
- Subject-wise analysis
- Academic trend analysis

## Future Scope

- Develop an interactive web dashboard.
- Generate personalised academic improvement recommendations.
- Provide an interface for entering student information and viewing predictions.
- Expand model evaluation using additional datasets.

## Author

**Isha Bhargava**

B.Tech – Computer Science and Engineering

Jaypee Institute of Information Technology