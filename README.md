# Powerbi_Insurance-Data-Report

This project showcases an interactive data visualization dashboard built using Power BI to analyze an insurance company dataset. The dashboard highlights key metrics such as policy distribution, financial performance (premium, claim, and coverage amounts), customer demographics, and sentiment trends from customer feedback.

The primary objective of this project is to present a clear, data-driven overview of business performance and customer behavior, enabling better decision-making in areas such as underwriting, marketing strategy, and claims management.

| **Feature Category**   | **Description**                                                                                                                     |
| ---------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| **Customer Details**   | Includes demographic information such as gender and age group.                                                                      |
| **Policy Information** | Displays policy details including type, policy status, and policy number.                                                           |
| **Claim Records**      | Tracks claim activity, including pending, rejected, and settled claims along with total claim amounts.                              |
| **Financial Metrics**  | Covers premium totals, policy coverage values, and claim financial insights.                                                        |
| **Sentiment Insights** | Customer feedback is processed and categorized by sentiment to identify experience quality and improvement areas (shown on Page 3). |


## Page 1 — Executive Summary Dashboard
This page provides a high-level overview including:
- Total premium, coverage, and claim value
- Claims by gender
- Claim amount by age group
- Premium amount by policy type
- Claim status overview
- Active vs inactive policy share

It is designed for quick business understanding.

<img width="1169" height="664" alt="image" src="https://github.com/user-attachments/assets/6b0e7a56-f121-418d-b2dc-d49d2c265176" />


#### Insights:
- Total Premium, Coverage, and Claim Values provide a high-level financial overview of the insurance performance.
- Travel insurance contributes the highest premium value, indicating strong product demand or higher policy pricing.
- Adults are the largest contributing age group in claim amounts, followed by elderly customers, while young adults have the lowest claim volume.
- Most policies are active, showing high customer retention and policy continuity.
- Claim status distribution shows a significant amount of rejected and settled claims, with pending claims being the smallest segment which indicate an efficient claim resolution process.

## Page 2 — Full Policy Table View
This page presents a complete data table containing all policy and claim records without any graphical visualization. It is designed to provide a detailed view of the dataset for deeper inspection and validation.

Users can:
- View all records in a structured tabular format
- Use drill-through to filter the table from Page 1 based on selected values
<img width="1141" height="650" alt="image" src="https://github.com/user-attachments/assets/b2fadd36-05d4-4482-8f94-3bcbaceceb0c" />



## Page 3 — Sentiment Analysis
This page visualizes customer feedback insights through sentiment evaluation and keyword extraction. The goal is to understand customer perception, recurring topics, and overall satisfaction trends.

Components on this page include:
- Word Cloud
Highlights commonly used words from customer feedback, providing a quick overview of recurring themes and topics mentioned by customers.
- Sentiment Score Table
Displays each feedback entry along with its sentiment score (0–1 scale) and a short summary. Higher scores indicate more positive feedback, while lower scores reflect dissatisfaction or improvement needs.
- Sentiment Category Chart
The feedback is grouped into three categories for easier interpretation:
  - Excellent
  - Good
  - Needs Improvement

This page can help identify customer satisfaction levels, key service strengths, and areas that require improvement based on direct customer comments.
<img width="1152" height="661" alt="image" src="https://github.com/user-attachments/assets/a9d62b05-3fe5-4480-8623-eaa8783d8254" />

#### Insights:
- Majority of customer feedback falls under the Excellent category, showing overall positive perception toward the insurance services.
- Common keywords such as “service,” “process,” “policy,” and “satisfied” indicate strong satisfaction with service experience and policy handling.
- Negative feedback mainly relates to delays and unclear policy terms, suggesting opportunities for improving communication clarity and response times.
- Higher sentiment scores correlate with smooth claim processing and easy policy management, emphasizing the importance of efficiency in customer experience.
