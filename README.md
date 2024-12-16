# UFC Data Analysis - IDS 702 Final Project
<div align="center">
  <img src="https://github.com/user-attachments/assets/294ffa26-161d-4deb-bc8a-df7948146efb" alt="image">
</div>
### Contributors:
- Arko Bhattacharya
- Eric Ortega Rodriguez
- Mu Niu
- Nruta Choudhari

## Overview

This project explores performance dynamics in the Ultimate Fighting Championship (UFC), focusing on how physical attributes and tactical strategies impact fight outcomes. The analysis leverages data from 2010 to November 2024, including metrics like reach, strikes landed, and submission attempts.

### Key Research Questions:
1. How does fighter reach affect the total number of strikes landed during a fight?
2. Is the fight outcome associated with the number of submission attempts?

## Data

- **Source**: Kaggle
- **Description**: Data includes fighter attributes (height, weight, reach, etc.), fight statistics, betting odds, and outcomes.
- **Size**: 6,478 rows across 118 variables; preprocessed to 4,895 rows for analysis.

## Methodology

1. **Preprocessing**:
   - Columns with >6,000 missing values were removed.
   - Remaining data cleaned for consistency and relevance.
2. **Exploratory Analysis**:
   - Summary statistics for reach, strikes, and submission attempts.
   - Categorization by weight classes.
3. **Modeling**:
   - **Linear Regression**: Examined the relationship between reach and strikes landed.
   - **Logistic Regression**: Evaluated submission attempts' impact on fight outcomes.

## Results

### Research Question 1: Fighter Reach and Strikes Landed
- Significant but complex relationship between reach and strikes.
- Adjusted \( R^2 \): 0.068 (indicating modest explanatory power).
- Weight classes influenced the relationship:
  - Featherweight fighters landed more strikes.
  - Flyweight fighters landed fewer strikes.

### Research Question 2: Submission Attempts and Fight Outcomes
- Logistic regression revealed:
  - **Red Corner Submission Attempts**: Increased win probability (\( OR = 1.549, p < 0.001 \)).
  - **Blue Corner Submission Attempts**: Decreased win probability (\( OR = 0.709, p < 0.001 \)).
  - Significant role of reach and striking efficiency in determining outcomes.


