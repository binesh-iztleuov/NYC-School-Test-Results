# Analyzing NYC School Performance Data Using Pandas

## Overview
This project analyzes the performance of New York City (NYC) schools using a dataset containing information about SAT scores, boroughs, and school attributes. The analysis explores the overall performance of schools, identifies top-performing schools, and examines borough-level statistics to provide insights into educational outcomes.

The project is implemented in Python using the Pandas library for data manipulation and analysis. 

## Objectives
The primary goals of this project are:
1. **Calculate Overall SAT Scores**: Combine Math, Reading, and Writing SAT scores to compute a total SAT score for each school.
2. **Identify Top-Performing Schools**: Determine the top 10 schools with the highest total SAT scores.
3. **Analyze Borough-Level Statistics**: Find the borough with the largest variability in SAT scores, based on standard deviation, and calculate relevant borough-level metrics.

## Dataset
The dataset contains information about NYC schools, including:
- `school_name`: Name of the school.
- `borough`: Borough where the school is located.
- `building_code`: School building code.
- `average_math`, `average_reading`, `average_writing`: Average SAT scores for Math, Reading, and Writing.
- `percent_tested`: Percentage of students who participated in SAT tests.

### Data Source
The dataset is provided as a CSV file and processed using Pandas. It is assumed to be accurate and up-to-date for the analysis.

## Project Workflow
The project follows these steps:
1. **Data Loading and Preparation**:
   - Read the dataset into a Pandas DataFrame.
   - Inspect the structure and initial rows of the data.
2. **Task 1: Calculate Total SAT Scores**:
   - Compute the total SAT score for each school by summing the Math, Reading, and Writing scores.
3. **Task 2: Identify Top-Performing Schools**:
   - Sort schools by their total SAT scores in descending order.
   - Extract the top 10 schools with the highest scores.
4. **Task 3: Analyze Borough-Level Statistics**:
   - Group data by borough and calculate:
     - Number of schools.
     - Average total SAT score.
     - Standard deviation of total SAT scores.
   - Identify the borough with the highest standard deviation in SAT scores.

## Key Results
### Task 1: Total SAT Scores
Each school's total SAT score was calculated successfully. Schools with missing values in any subject score were handled to avoid errors.

### Task 2: Top 10 Schools
The following schools achieved the highest total SAT scores:
1. Stuyvesant High School (2144)
2. Bronx High School of Science (2041)
3. Staten Island Technical High School (2041)
4. High School of American Studies at Lehman College (2013)
5. Townsend Harris High School (1981)

_(Full list available in the code)_

### Task 3: Borough with Largest Standard Deviation
The borough with the largest standard deviation in SAT scores is **Manhattan**, with:
- **Number of schools**: 89
- **Average SAT score**: 1340.13
- **Standard deviation**: 230.29

## Technology and Libraries
- **Python 3.9+**
- **Pandas**: Data manipulation and analysis.
- **Jupyter Notebook**: Interactive coding and visualization.


## How to Use
### Prerequisites
- Install Python (3.9 or later) and ensure that Pandas is installed:
  ```bash
  pip install pandas
  ```

### Steps to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your_username/NYC-School-Performance-Analysis.git
   cd NYC-School-Performance-Analysis
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook notebook.ipynb
   ```
3. Follow the tasks in the notebook to view the analysis and results.


## Lessons Learned
This project strengthened my skills in:
- Data cleaning and aggregation using Pandas.
- Grouping and sorting data to extract meaningful insights.
- Performing statistical analysis with real-world datasets.
