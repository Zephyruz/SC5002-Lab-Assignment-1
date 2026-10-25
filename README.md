# SC5002 Lab Assignment 1

## Overview
This project is part of the SC5002 Artificial Intelligence Fundamentals & Applications lab assignment 1 at NTU.

It covers classical search algorithms and a machine learning experiment using the California Housing dataset.

## Part 1: Search Algorithms
- Breadth-First Search (BFS)
- A* Search
- 8-Puzzle problem using the misplaced tiles heuristic

The calculations and search steps are included in the PDF report.

## Part 2: Machine Learning
The experiment compares Linear Regression with Ridge Regression using different regularization strengths.

**Dataset:** California Housing Dataset (1,000 sampled records)

**Tools:** Python, Google Colab, scikit-learn, pandas, NumPy and Matplotlib

### Results

| Model | Mean 5-Fold CV R² |
|---|---|
| Linear Regression | 0.6457 |
| Ridge (alpha=0.1) | 0.6457 |
| Ridge (alpha=10) | 0.6443 |
| Ridge (alpha=1000) | 0.3574 |

Linear Regression and Ridge with alpha=0.1 achieved the highest reported scores. A very large alpha reduced the performance significantly, showing the effect of excessive regularization.

## How to Run
1. Open the `.ipynb` file in Google Colab.
2. Run the code cell.
3. View the dataset, cross-validation scores and model comparison chart.

## AI Assistance
Generative AI was used to explain search concepts, check A* calculations and help interpret the machine learning results. The prompts and reflections are documented in the PDF report.
