# Survival-Analysis

## Overview
This analysis employs **advanced survival analysis techniques** to understand and predict into a customer churn dataset, aiming to uncover the key factors influencing churn risk. Analytical models including the **Log-Normal Accelerated Failure Time (AFT)**, **Weibull**, and **Cox Proportional Hazards models** are utilized to dissect the dynamics of customer retention.

## Insights and Analysis
- **Significant Predictors**: Identification of critical factors such as `tenure`, `age`, `income`, and `education level`, each presenting a distinct influence on churn likelihood.
- **Vulnerable Segments**: The analysis brings to light segments particularly at risk, such as younger and lower-income demographics, demonstrating a heightened churn potential.

## Customer Lifetime Value (CLV)
- **Segmentation and Value Definition**: We delve into an exploration of Customer Lifetime Value (CLV) to identify and characterize high-value customer segments. By understanding which segments are most valuable, we can develop targeted strategies aimed at enhancing retention and optimizing profitability. This focused approach allows us to tailor our efforts to the specific needs and potential of different customer groups, ensuring that resources are used efficiently to foster loyalty and drive long-term succes

## Recommendations
- **Strategic Initiatives**: Recommendations include tailored retention strategies like targeted promotions and enhanced customer service. These initiatives are designed to cater specifically to the needs of identified segments, aiming to:
  - Reduce churn rates
  - Boost customer loyalty
  - Enhance overall business decision-making through the strategic application of survival analysis.

## Conclusion
By adopting personalized and data-driven strategies, this analysis equips us with a robust set of tools to reduce churn and build enduring customer relationships. These efforts are key to driving continuous growth and ensuring the long-term success of our business.


# Setup and Running Instructions

Follow these steps to set up your environment and run the Jupyter notebook:

## Prerequisites
Ensure you have Python and pip installed on your system. You will also need `virtualenv` installed to create a virtual environment.

### 1. Clone the Repository
First, clone the repository to your local machine using Git:
```bash
git clone [repository-url]
cd [repository-name]
```

### 2. Create and Activate Virtual Environment
Create a virtual environment in the project directory:
```bash
python -m virtualenv venv
```

Activate the virtual environment:

- **Windows:**
```bash
venv\Scripts\activate
```

- **macOS/Linux:**
```bash
source venv/bin/activate
```

### 3. Install Required Packages
Install all required packages listed in the `requirements.txt` file:
```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook
Run Jupyter Notebook:
```bash
jupyter notebook
```

### 5. Open the Notebook
In the Jupyter Notebook interface, navigate to the notebook file `Homework 3 | Survival Analysis.ipynb` and open it.

### 6. Run the Notebook
Execute the cells sequentially to see the analysis results.

## Conclusion
By following these steps, you should be able to successfully set up your environment and run the notebook to explore the survival analysis techniques applied to the customer churn dataset.
