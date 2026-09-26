# 📊 Customer Demographics & Statistical Insights 

## 📌 Project Overview
This project applies rigorous statistical hypothesis testing to a customer insights dataset to determine what truly drives purchasing behavior. By challenging standard industry assumptions using Python and SciPy, this analysis transitions from basic demographic segmentation to actionable, data-driven corporate strategy.

## 🛠️ Tech Stack & Tools
* **Data Manipulation:** Python (Pandas, NumPy)
* **Statistical Testing:** Python (SciPy) - *Independent T-Tests, One-Way ANOVA, Pearson Correlation*
* **Data Visualization:** Python (Matplotlib, Seaborn)

## 🔍 Methodology
1. **Data Integrity & Cleaning:** Verified a perfectly clean dataset with zero nulls or duplicates, and optimized temporal data types for analysis.
2. **Exploratory Data Analysis (EDA):** Visualized distributions (e.g., normally distributed age brackets) and identified baseline metrics, such as a predictable ~$330 average monthly spend.
3. **Hypothesis Testing:** Formulated and executed statistical tests to determine the variance in spend across Gender, Education, and State, as well as the correlation between Age and Churn.

## 📈 Key Business Insights & Strategic Takeaways
* **Demographics Do Not Dictate Cart Value:** Independent T-tests ($p=0.734$) and ANOVA tests ($p=0.922$) confirmed that Gender, Education, and State have absolutely no statistically significant impact on monthly spend. 
* **Shift to Behavioral Analytics:** Since demographic attributes do not dictate revenue variance, marketing budgets should pivot away from localized pricing tiers and focus entirely on behavioral triggers (e.g., past purchase categories, discount usage).
* **Age Does Not Drive Churn:** Pearson correlation analysis ($r = -0.004$, $p = 0.682$) mathematically debunked the assumption that older demographics disengage faster. Re-engagement campaigns must remain inclusive of all age groups.
* **High Revenue Predictability:** Symmetrical spending distributions reveal a stable baseline, allowing finance and supply chain teams to confidently forecast revenue and optimize inventory without fearing erratic outliers.

## 📁 Repository Contents
* `Customer_Insights_Analysis.ipynb`: The complete Jupyter Notebook containing data cleaning, visualizations, and statistical testing.
* `US_Customer_Insights_Dataset.csv`: The raw dataset utilized for the investigation.

---
**Author:** Jitendra Kumar  
*Master of Statistics | Data Analyst*
