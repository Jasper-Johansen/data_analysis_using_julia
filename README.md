# Student Performance Analysis and Visualization using Julia

This project involves analyzing and visualizing factors that affect student performance using the **StudentPerformanceFactors** dataset from Kaggle. The analysis is conducted in **Julia**, utilizing key packages such as `CSV`, `DataFrames`, `StatsBase` and `Plots`. The goal is to extract insights from the data and present them through meaningful visualizations.

## Project Objectives

The objective of this project is to:
1. Clean and explore the dataset.
2. Perform statistical analysis on student performance.
3. Create visualizations to uncover patterns and relationships.

## Dataset
The dataset used in this project is the **StudentPerformanceFactors** dataset from Kaggle, which includes various factors such as:
- Study time
- Parental education
- Attendance
- Sleep hours
- Extracurricular activities
- Grades

Download the dataset from [Kaggle](https://www.kaggle.com/) and place it in the root directory of the project.

## Requirements
To run this project, you will need:
- Julia 1.x or later
- The following Julia packages:
  - `CSV`
  - `DataFrames`
  - `StatsBase`
  - `Plots`

## Installation
To install the required packages, run the following commands in the Julia REPL:

```julia
using Pkg
Pkg.add("CSV")
Pkg.add("DataFrames")
Pkg.add("StatsBase")
Pkg.add("Plots")
```

## Results

1. The correlation data indicates that sleep and exam grades are weakly correlated. Students with sleep less than and greater than 7 hours of sleep showed small negative correlations, suggesting a narrow advantage for students with an average of 7 hours of sleep.
2. The positive slope between Hours Studied and Exam Scores indicates that increasing study hours is associated with higher scores achieved by students, at least moderately.
