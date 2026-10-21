# Body Image Anxiety among University Students: A Longitudinal Data Analysis
CISC7204 Data Science Portfolio Assignment
Student ID: MC64199 | Maggie

## Research Question
How do socio-demographic factors, self-perceived weight status and social media exposure predict the risk of elevated body image anxiety among university students over multiple survey waves?

## Dataset source and usage permissions
This demonstration uses a **simulated synthetic longitudinal student survey dataset** created only for this coursework portfolio.
No real participant survey records are included. The synthetic dataset follows the same variable structure as the original research, but all values are artificially generated. This synthetic dataset is permitted for academic demonstration in this public GitHub repository, and it contains no identifiable personal information.
The original confidential research dataset is protected by research ethics approval and will not be published publicly.

## Methods and tools used
- Programming language: Python 3.9
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn
- Analytical workflow:

![Analytical Pipeline Summary](figures/analytical_pipeline.png)

1. Data cleaning and missing value imputation
2. Descriptive statistics and exploratory visualization
3. Binary logistic regression to identify predictors of body anxiety
4. ROC-AUC analysis to evaluate model classification performance

## Key findings and one limitation
### Key findings (simulated for portfolio demonstration)
In this synthetic sample, higher frequency of social media appearance comparison and negative weight self-perception are associated with increased odds of body image anxiety. The logistic regression model achieves an AUC of 0.72 on the held-out test subset.
> Note: This is a mock result for assignment requirement only, not the empirical finding from my formal research.

### One limitation
This synthetic dataset has simplified correlation structures and does not replicate the complex attrition pattern that exists in real longitudinal survey data. The simulated model performance cannot be generalized to the true student population.

## Visualizations
Figure 1: Simulated ROC curve of the logistic prediction model
![Simulated ROC Example for Illustration](figures/simulated_roc.png)

## Instructions for running the analysis
1. Clone this repository to your local machine
2. Install dependencies with:
```bash
pip install -r requirements.txt
