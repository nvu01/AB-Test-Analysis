# A/B Test Analysis
### Introduction
This project analyzes the results of an A/B test run by an e-commerce website to determine whether the company should implement a new page, keep the old page, or run the experiment longer.  
The experiment compares user behavior between two versions of a webpage: the old version (control) and a new version (treatment).  
The dataset is stored in a CSV file named `ab_data.csv` and contains three key columns:

- **country**: The country of the user (UK, US, CA)
- **group**: The group the user was assigned to (treatment or control)
- **converted**: Whether the user completed the desired action (1 = converted, 0 = not converted)

### Part I - Descriptive Statistics
In this section, we explore the dataset collected during the A/B test.

### Part II - Probability
This section covers how different factors are related to the conversion rate.

### Part III - Experimentation
In this section, we will perform hypothesis testing. Key points include:
- Simulate 500 samples of treatment and control groups
- Analyze the likelihood of the observed differences being due to chance
- Assess the statistical significance of the results

### Part IV - Algorithms
In this section, we will use statsmodels to fit the regression model to see if there is a significant difference in conversion based on which page a customer receives.  
We also use the model to analyze the impact of country on the conversion rate.

### Requirements
To run this notebook, ensure you have the following Python libraries installed:
- `numpy`
- `pandas`
- `matplotlib`
- `statsmodels`

You can install the required libraries using the following command:

```bash
pip install numpy pandas matplotlib statsmodels