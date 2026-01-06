# Hypothesis-and-A-B-testing
Project Goal

The goal of this project is to apply hypothesis testing and A/B testing techniques to evaluate statistically significant differences between groups, measure the impact of changes, and support data‑driven decision‑making.

This repository demonstrates a complete statistical workflow:
- Formulating null and alternative hypotheses
- Exploring and preparing datasets
- Applying statistical tests (t‑test, chi‑square, ANOVA, etc.)
- Designing and evaluating A/B experiments
- Interpreting results and extracting actionable insights

The project highlights practical skills in statistics, experimentation, Python, and analytical reasoning.

Analytical Focus

This analysis aims to answer questions such as:
- Are two groups significantly different?
- Does a change (e.g., layout, price, campaign) improve performance metrics?
- Do user behaviors shift after an intervention?
- What is the probability that an observed effect is due to chance?
- Statistical rigor ensures that conclusions are reliable and reproducible.

Statistical Methods Used
- Hypothesis Testing
  * Independent and paired t‑tests
  * Proportion tests
  * Chi‑square tests for categorical variables
  * ANOVA for comparing multiple groups
  * Non‑parametric tests when assumptions are violated

- A/B Testing
  * Control vs. treatment group design
  * Uplift calculation
  * Assumption checks (normality, variance, sample size)
  * p‑value interpretation
  * Confidence interval analysis
  * Practical vs. statistical significance
 
Methodology
1. Data Loading & Inspection
   * Import datasets
   * Check data types, missing values, and duplicates
   * Initial exploratory analysis

2. Data Cleaning
   * Remove duplicates
   * Convert data types (dates, numeric, categorical)
   * Normalize and standardize fields when needed

3. Statistical Testing
   * Define hypotheses
   * Select appropriate statistical tests
   * Execute tests using Python (SciPy, Statsmodels)
   * Interpret p‑values and effect sizes

4. A/B Testing
   * Split data into groups A and B
   * Compute key performance metrics
   * Apply statistical tests to compare groups
   * Evaluate significance and business impact

5. Visualization
   * Comparative charts
   * Distribution plots
   * Boxplots, histograms, bar charts
   * Visual summaries of test results

6. Insights & Conclusions
   * Summaries of statistical findings
   * Practical implications
   * Business recommendations

Example Insights
- Group B showed a statistically significant improvement in conversion rate.
- Differences between segments were meaningful both statistically and practically.
- A/B testing revealed that small design changes can produce measurable uplift.

Tools Used
- Python (Pandas, NumPy, SciPy, Statsmodels)
- Jupyter Notebook for exploratory analysis
- Matplotlib / Seaborn for visualization
- Scikit‑learn (when applicable)
- Git & GitHub for version control

Skills Developed
- Formulating and testing statistical hypotheses
- Designing and interpreting A/B experiments
- Data cleaning and preprocessing
- Visualizing data for decision‑making
- Communicating analytical results clearly
- Structuring a complete statistical workflow

How to Run the Project
1. Clone the repository (git clone https://github.com/Faissen/Hypothesis-and-A-B-testing)
2. Navigate into the project folder (cd Hypothesis-and-A-B-testing)
3. Install required libraries (pip install -r requirements.txt)
4. Launch Jupyter Notebook
5. Run the notebooks to reproduce the analysis
