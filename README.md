# Student Performance & Academic Analytics

## Project Overview
This project analyzes student academic performance using the UCI Student Performance Dataset. It explores how academic history, study habits, family background, and lifestyle factors relate to students' final grades.

The analysis covers two subjects:
- Mathematics
- Portuguese

## Objective
- Understand and validate real-world student data.
- Perform data cleaning and quality checks.
- Analyze numerical and categorical variables.
- Identify patterns and relationships affecting academic performance.
- Create meaningful visualizations.
- Generate insights and educational recommendations.

## Dataset
**Source:** [UCI Student Performance Dataset](https://archive.ics.uci.edu/dataset/320/student+performance)

| Dataset | Students | Columns |
|---|---:|---:|
| Mathematics | 395 | 33 |
| Portuguese | 649 | 33 |

The target variable is `G3`, representing the final grade.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Project Workflow
1. Data loading and inspection
2. Data quality validation
3. Missing value and duplicate checks
4. Descriptive statistical analysis
5. Univariate analysis
6. Bivariate analysis
7. Multivariate analysis
8. Correlation analysis
9. Data visualization
10. Insights and recommendations

## Key Findings
- Previous academic grades (`G1` and `G2`) have the strongest positive relationships with final grades.
- Students with more previous class failures generally achieve lower final grades.
- Study time shows a positive association with academic performance, particularly in Portuguese.
- Mathematics grades show greater variability than Portuguese grades.
- Absences have relatively weak relationships with final grades.
- Academic performance patterns differ between Mathematics and Portuguese.

## Recommendations
- Identify students requiring academic support using previous academic performance.
- Provide additional guidance to students with previous class failures.
- Encourage consistent study habits.
- Monitor students' progress regularly.
- Consider multiple academic and personal factors instead of relying on a single variable.

## Limitations
- The analysis identifies associations, not causal relationships.
- The dataset represents specific schools and may not generalize to all students.
- Some categories contain relatively few observations.
- Academic performance can be influenced by factors not included in the dataset.

## Project Structure

```text
Student-Performance-Analysis/
│
├── student_performance_analysis.ipynb
├── student-mat.csv
├── student-por.csv
├── student.txt
└── README.md
```

## How to Run the Project

### 1. Download the Dataset
Download the Mathematics and Portuguese datasets from the UCI repository.

### 2. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Open Jupyter Notebook

```bash
jupyter notebook
```

### 4. Run the Analysis
Open `student_performance_analysis.ipynb` and select:

**Kernel → Restart & Run All**

Ensure both CSV files are in the same directory as the notebook and their filenames match the paths used in the code.

## Author
Amanraj Somawar
