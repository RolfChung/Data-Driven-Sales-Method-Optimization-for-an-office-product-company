# Data-Driven Sales Method Optimization for an office product company

## Overview

This project aims to analyze sales data for a company founded in 1984 that provides high-quality office products. The primary business goals are to:

* Determine the most effective sales method for maximizing revenue.
* Establish a key business metric to monitor the performance of different sales methods over time.
* Identify potential levers within the existing data to further enhance revenue generation.

By achieving these goals, Pens and Printers can optimize their sales strategies, leading to increased revenue and a stronger understanding of their business success.

## Work Summary

The analysis to address these objectives was conducted in four key stages:

1.  **Data Validation & Cleaning:** This initial phase focused on ensuring the quality and integrity of the data. This involved identifying and handling:
    * Missing values
    * Outliers
    * Incorrect data types
    * Inconsistent string formats
    * A detailed data validation report was generated to document these steps.

2.  **Exploratory Data Analysis (EDA):** This stage involved exploring the data to gain initial insights and understand the underlying patterns. Key activities included:
    * Visualizing the distribution of individual variables using histograms.
    * Examining the relationship between different sales methods and the resulting revenue using boxplots.
    * Analyzing revenue trends over time (weekly) using line plots.

3.  **Sales Method & Business Metric Recommendation:** This core section addressed the main business questions:
    * **Sales Method Recommendation:** Identifying the most effective sales method based on the analysis.
    * **Business Metric for Monitoring:** Proposing a relevant metric to track the performance of sales methods and overall revenue generation. This recommendation was supported by statistical analysis using ANOVA and the Tukey post-hoc test.

4.  **Final Recommendations:** This concluding section synthesizes the findings from the previous stages to provide actionable recommendations for Pens and Printers.

## Key Findings

### Current Situation & Sales Method Recommendation

* After normalizing revenue by the number of customers exposed to each sales method, the **"Email+Call"** method demonstrated the highest average customer revenue.
* Based on this analysis and statistical validation (ANOVA and Tukey test), the **"Email+Call"** sales method is recommended for primary use.

### Business Metric for Monitoring

* The proposed business metric for ongoing monitoring is **"Normalized Revenue"**.
* **Normalized Revenue** is calculated by [Describe how Normalized Revenue is calculated - e.g., Total Revenue for a Sales Method / Number of Customers Exposed to that Method].
* This metric offers several advantages:
    * **Removes bias:** It eliminates the impact of varying customer base sizes for different sales methods, allowing for a fair comparison of their effectiveness.
    * **Highlights per-customer efficiency:** It provides a clearer understanding of how well each sales method converts individual customers into revenue.
    * **Offers deeper insights:** It facilitates a more nuanced evaluation of sales strategy effectiveness beyond just total revenue.
    * **Tracks performance trends:** Monitoring Normalized Revenue week-to-week allows for the identification of performance fluctuations and trends for each sales method.
    * **Actionable insights:** It helps identify underperforming sales channels that may require optimization.
    * **Alignment with business goals:** It directly supports the goal of maximizing revenue by focusing on efficient customer engagement.

## Business Recommendations

### Main Recommendations

* **Sales Method:** Prioritize and leverage the **"Email+Call"** sales method as the most effective approach based on the current data.
* **Business Metric:** Implement the **"Normalized Revenue"** metric to continuously monitor the performance of different sales methods and overall revenue generation.

### Further Recommendations

* **Lower Revenue Customers:** Implement targeted offers and strategies to encourage increased spending from customers who currently generate lower revenue.
* **High Revenue Customers:** Develop specific retention and loyalty programs to nurture relationships with high-value customers and ensure their continued engagement.
* **Website Engagement:** Implement a loyalty reward system for customers who visit the website frequently (e.g., more than 35 times) to foster deeper engagement and potentially increase conversion rates.
* **Long-Term Customer Loyalty:** Develop a comprehensive loyalty program that rewards customers based on their tenure (years as a customer) with exclusive benefits, discounts, or personalized offers to encourage long-term commitment.

## Technical & Data Recommendations

* **A/B Testing:** Conduct rigorous A/B testing to isolate the true impact of different sales methods on revenue. This should involve randomly assigning customers to different sales method groups to ensure unbiased results.
* **Include Cost Data:** Integrate cost information associated with each sales method to enable the calculation of profit, providing a more comprehensive understanding of business performance beyond just revenue.
* **Real-time Dashboard:** Create a dynamic dashboard to monitor key revenue metrics, including Normalized Revenue, in real-time. This will facilitate timely business interventions and decision-making based on current performance.
* **Collect More Data:** Explore opportunities to collect more granular and diverse data points to enable more advanced statistical analyses, such as sampling and more sophisticated predictive modeling in the future.