# Making Decisions with Statistics and Hypothesis Testing  
**(Shopno Supershop Fake Data)**

## Overview
This project demonstrates how to apply statistical analysis and hypothesis testing techniques to business data. Using a simulated dataset from a fictional supermarket ("Shopno Supershop"), we explore sales patterns and test hypotheses to make informed business decisions.

## Key Objectives
- Analyze sales data based on sales channels and regions.
- Perform statistical hypothesis tests to compare group means.
- Examine the correlation between customer age and purchase amount.

## Techniques Used
- Descriptive statistics
- Data visualization (bar plots, distribution plots)
- Independent two-sample t-tests
- Pearson correlation analysis

## Hypothesis Tests Conducted
1. **Online vs Offline Sales**
   - **H₀ (Null Hypothesis):** Mean purchase amounts for online and offline sales are equal.
   - **H₁ (Alternative Hypothesis):** Mean purchase amounts for online and offline sales differ.
   - **Test Used:** Independent two-sample t-test.

2. **Dhaka vs Other Regions**
   - **H₀ (Null Hypothesis):** Mean purchase amounts for Dhaka and other regions are equal.
   - **H₁ (Alternative Hypothesis):** Mean purchase amounts for Dhaka and other regions differ.
   - **Test Used:** Independent two-sample t-test.

3. **Age vs Purchase Amount Correlation**
   - Analyzed using Pearson correlation.
   - Findings: Very weak negative correlation (-0.0316), suggesting no significant relationship between age and purchase amount.

## Technologies
- Python 3
- NumPy
- Pandas
- Matplotlib
- Seaborn
- SciPy

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/shopno_supershop_statistics.git
   cd shopno_supershop_statistics
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter notebook:
   ```bash
   jupyter notebook
   ```

4. Run the notebook `(shopno_supershop_fakedata)Making_Decision_with_statistics_and_hypothesis_testing_.ipynb`.

## Project Structure
```
.
├── (shopno_supershop_fakedata)Making_Decision_with_statistics_and_hypothesis_testing_.ipynb
├── README.md
└── requirements.txt
```

## Author
- **Mk Ador**  
- [Your LinkedIn Profile](#)  
- [Your Portfolio or Website](#)
