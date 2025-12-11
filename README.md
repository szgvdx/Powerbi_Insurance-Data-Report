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


## Page 1 Executive Summary Dashboard

<img width="1169" height="664" alt="image" src="https://github.com/user-attachments/assets/6b0e7a56-f121-418d-b2dc-d49d2c265176" />


This page is designed for quick business understanding. It provides a high-level overview including:
- Total premium, coverage, and claim value
- Claims by gender
- Claim amount by age group
- Premium amount by policy type
- Claim status overview
- Active vs inactive policy share


## Analysis Section


<img width="363" height="300" alt="image" src="https://github.com/user-attachments/assets/9b9ad71a-ac12-4cae-af91-58c1166ecc6e" />


The rejected claims take up the biggest portion, which suggests that many customers still struggle to meet the requirements or understand the policy conditions. This aligns with a study by Mathew & Ninan (2025), which found that in India the most common insurance complaint is claim rejection mostly caused by complicated documents, unclear instructions, and customers not fully understanding what is covered. Based on this, the company can reduce rejection rates by making documentation requirements clearer and easier to follow, for example through simple checklists, better guidance during submission, or short explanations of common policy exclusions. The same study also shows that company grievance cells are the fastest and most effective channel for resolving issues, so strengthening internal support, like quicker responses or clearer explanation when a claim is rejected, can help improve customer satisfaction. So, improving communication and the claim submission process should lead to fewer rejected claims.



<img width="536" height="468" alt="image" src="https://github.com/user-attachments/assets/72a6f5fe-6c35-431d-a184-09930e3ea515" />


Travel insurance leads premium revenue (~2.5M) but also shows high pending claim volume (57.24M total claim value).
Travel insurance generates high revenue but also high volatility in claims due to seasonality and external risk factors (flight cancellations, weather, etc).

Recommendation:

- Refine underwriting criteria for travel risk - such as trip duration, destination risk tiers.
- Incorporate dynamic pricing based on seasonality or traveler behavior.



<img width="377" height="233" alt="image" src="https://github.com/user-attachments/assets/98a7baaf-d8f6-4044-a7c4-16b1fc8ab0a7" />



More than half of the policies remain active, which signals relatively strong customer retention and ongoing trust in the company. However, the inactive segment which around 42% is indicating that many customers are discontinuing or letting their policies lapse. According to the study by Giri & Chatterjee (2022), high lapsation rates in the Indian insurance sector are strongly linked to mis-selling, low product understanding, and customers purchasing policies that do not match their actual needs. Their research found that many policyholders, especially younger or less financially literate groups, often do not fully understand what type of policy they own, and policies acquired due to agent influence or tax-saving motives tend to lapse later due to mismatched expectations or affordability issues.

Recommendation:

Increase customer education and improve after-sales support to ensure that customers understand their policy features and ongoing responsibilities.
This can include simple product explanations, periodic check-ins, and guidance for customers who may be at higher risk of lapsation, such as those with multiple policies or those who have recently faced claim rejection.


<img width="366" height="228" alt="image" src="https://github.com/user-attachments/assets/6a552b75-0cce-4914-bcf7-600dd45e9f6c" />



Adults contribute the highest claim amount because they are in a life stage with heavier responsibilities and higher exposure to health and financial risks. Work-related stress, family obligations, and the need for regular medical check-ups make them more likely to use their insurance coverage. Elderly customers follow closely behind, driven by chronic conditions and the need for ongoing or intensive care, which naturally increases their claim amount. Meanwhile, young adults record the lowest claim total not only because they tend to be healthier and visit healthcare facilities less frequently, but also because their insurance literacy is relatively low. Many in this group often do not fully understand their policy benefits or how to use them, which aligns with Giri & Chatterjee’s (2022) finding that younger and less informed buyers are more likely to own policies they do not fully comprehend. This lower awareness contributes to underutilization and fewer claims being filed.



## Page 2 Full Policy Table View
This page presents a complete data table containing all policy and claim records without any graphical visualization. It is designed to provide a detailed view of the dataset for deeper inspection and validation.

Users can:
- View all records in a structured tabular format
- Use drill-through to filter the table from Page 1 based on selected values

<img width="1141" height="650" alt="image" src="https://github.com/user-attachments/assets/b2fadd36-05d4-4482-8f94-3bcbaceceb0c" />




## Page 3 Sentiment Analysis
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



## References
- Giri, M., & Chatterjee, D. (2022). Life Insurance Purchase Motives, Policy Choice and Lapsation: A Case of Mis-selling? SSRN.
- Mathew, J. M., & Ninan, A. A. (2025). Redressal Mechanism Regarding Complaints on Insurance Products. JISEM.
