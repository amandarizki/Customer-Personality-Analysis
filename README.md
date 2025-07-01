# Customer-Personality-Analysis
A data-driven project to understand customer demographics, purchasing behaviors, and campaign responsiveness. This analysis provides actionable insights for designing targeted marketing strategies and improving customer engagement.


## Project Overview

**Objective:**  
To analyze and segment customers based on demographic profiles, income levels, purchasing channels, and product preferences to uncover patterns that drive purchasing decisions.

**Key Questions Addressed:**

Below are several key questions to be addressed using the **5W+1H** approach:

### **How**
* How is the data structured, and what are the distribution patterns of customer characteristic variables (age, income, and family status)?
### **What**
* Which products are most frequently purchased by customer segments based on age?
### **Why**
* Is there a difference in the average spending on wine (*MntWines*) between married and unmarried customers?
### **Where**
* Through which channels do customers shop most often? (Website, catalog, physical store)
### **Why**
* Does customer age influence their preferred purchasing channel (web, catalog, physical store)?
* Are high-income customers more responsive to promotions?
### **When**
* Do newly joined customers (*Dt\_Customer*) tend to be more active in purchasing products?

## Key Insights

### Demographics
- **Education:** Majority hold a Bachelor's degree.
- **Marital Status:** Predominantly married or living together.
- **Age:** Average age is 56 years.
- **Children:** Most customers do not have children at home.

*Implication:* Use clear, rational communication targeting adults in stable households.

---

### Income Distribution
- **Mean Income:** ~52,247
- **Distribution:** Highly skewed with a few high-income outliers.
- **Variation:** Significant income inequality among customers.

*Implication:* Marketing offers should be flexible to appeal to both mid- and low-income segments.

---

### Purchasing Behavior
- **Channels:** 
  - Most purchases occur in physical stores.
  - Website is the second most popular channel.
  - Catalogs are least used.
- **Tenure:** Longer-standing customers make slightly more purchases (weak positive correlation).

*Implication:* Invest in in-store experience and optimize the website to grow online sales.

---

### Product Preferences by Age
| Age Group | Highest Spending |
|-----------|------------------|
| 61–80     | Wine             |
| 18–45     | Meat Products    |

*Implication:* 
- Promote premium wine offers to older customers.
- Highlight nutrition and lifestyle benefits for younger segments.

---

### Campaign Responsiveness
- **Highest Response:** Customers earning 90,000–120,000.
- **Largest Segment:** Customers earning 30,000–60,000 but less responsive.

*Implication:* 
- Use personalized campaigns for high-income customers.
- Educate and incentivize mid-income segments to increase engagement.

---

### Statistical Testing
- No significant difference in wine spending between married and unmarried customers (*p-value = 0.7758*).


## Methodology

The analysis included:
- Descriptive statistics (mean, median, mode, skewness, kurtosis)
- Grouped aggregations by demographic segments
- Correlation analysis
- Visualizations (bar charts, heatmaps)
- Hypothesis testing (Independent T-Test)

**Tech Stack:**
- Python (pandas, numpy, seaborn, matplotlib, scipy)
- Jupyter Notebook


## How to Run the Project

1. Clone this repository:
```

git clone https://github.com/amandarizki/Customer-Personality-Analysis.git
cd Customer-Personality-Analysis

```
2. Install dependencies:
```

pip install -r requirements.txt

```
3. Start Jupyter Notebook:
```

jupyter notebook

```
4. Execute the analysis cells in order.


## Business Recommendations

- Focus marketing campaigns on middle-aged, married customers.
- Develop premium product lines for higher-income segments.
- Invest in omnichannel strategies emphasizing in-store and digital experiences.
- Tailor messaging to educated customers with rational, benefit-focused content.


## Author

Amanda Rizki Koreana

---

*This project was developed to practice data engineering and analytics workflows and can be reused as a reference for similar ETL pipelines.*

```
