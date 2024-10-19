# A/B Testing on Fast Food Marketing Campaign
# Project Overview
This project aims to evaluate the effectiveness of three marketing promotions for a fast food chain using A/B testing methodology. The dataset contains weekly sales data collected across different markets of varying sizes over four weeks, with each market using one of the three promotional strategies.

The objective is to determine which marketing campaign has the highest impact on sales performance, ensuring that decisions are supported by statistical evidence.

# Dataset Description
The dataset used for this analysis contains the following columns:

MarketID: Unique identifier for each market <br>
MarketSize: Size of the market (Large, Medium, Small)<br>
LocationID: Unique identifier for each store location <br>
AgeOfStore: The number of years since the store opened <br>
Promotion: The promotion applied in a given market (1, 2, or 3)<br>
Week: The week of sales data (1 through 4)<br>
SalesInThousands: Sales recorded in thousands of dollars<br>

# Project Steps

# Exploratory Data Analysis (EDA):
Analyzed the distribution of sales across different market sizes and promotions.
Checked for any outliers and investigated their potential impact on the analysis.
Visualized sales trends over time to observe any patterns or anomalies.

# ANOVA (Analysis of Variance):

- Performed a one-way ANOVA to test if there are statistically significant differences in sales among the three promotional strategies.
- Ran a post-hoc Tukey HSD test to determine which specific promotions had significant differences in sales.
  
# Visualizations:

Created plots to show the average sales for each promotion across different market sizes.
Illustrated sales trends over the weeks for each promotional strategy to identify performance patterns over time.

# Key Insights
# ANOVA Results:

Found significant differences in sales between certain promotions, especially between Promotion 1 and Promotion 2, as well as between Promotion 2 and Promotion 3.
The Tukey HSD test confirmed that Promotion 2 performed significantly worse than the other two promotions.
