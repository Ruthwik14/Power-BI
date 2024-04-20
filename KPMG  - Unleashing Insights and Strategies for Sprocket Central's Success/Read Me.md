# KPMG Project Overview

## Task 1: Data Quality Assessment

### Data Quality Assessment Mail

**Subject:** Assessment of Data Quality and Recommendations for Sprocket Central Pty Ltd

Dear Manager,

I hope this email finds you well. Thank you for providing the datasets from Sprocket Central Pty Ltd. Our team is excited to work on assessing the quality of the data you've shared. As part of this process, we will also be drafting recommendations to address any issues identified and ensure the data is ready for our upcoming analysis in phase two.

Upon reviewing the datasets—Customer Demographic, Customer Addresses, and Transaction data from the past three months—we have identified several data quality issues that may impact the accuracy and reliability of our analysis. I would like to share these findings with you and propose strategies to mitigate these concerns.

**Transaction Data:**
- Productid column: Some entries have a product id “ 0”, and there is a mix of brand, product line, product class, for product ids 1, 2, 4, 5, etc.
- Transaction date: column should be in date format.
- Online order: Blank values present.
- Brand, product line, product class, product size: Blank values detected.
- List price, standard cost: Different values for the same product.
- Product first sold date: Varied formats and blank values.
- Remove the first row.

**New Customer List:**
- Remove the first row.
- past_3_years_bike_related_purchases: Incorrect data format.
- DOB: Incorrect format and blank values.
- Job title: Blank values.
- Postcode, property valuation: Incorrect format.
- Extra column With no name

**Customer Demographic:**
- Gender: Variations in entries (e.g., "f," "Female," "Femal," "M," "Male").
- DOB: Blank entries and anomalies (e.g., 1843).
- Job title: Blank values.
- Default: Unrelated values.

**Customer Address:**
- Address: Some entries have a '0' in front of the address.

To mitigate these issues and ensure the data's quality for our analysis, we recommend the following actions:
- Standardize data formats, especially for dates (e.g., transaction date, DOB).
- Fill or correct missing or incorrect values in categorical variables (e.g., gender, job title).
- Remove rows with anomalies or unrelated values.
- Validate and correct entries with formatting errors (e.g., productid, past_3_years_bike_related_purchases).
- Regularize address entries without leading zeros.

Please find attached a Data Quality Framework Table for your reference, which includes criteria and dimensions considered during the assessment. If you have any questions or require further clarification, feel free to reach out. We look forward to collaborating with you to ensure the data meets the highest standards for our analysis.

Thank you for your attention to this matter.

Best regards,
Devanapalli Ruthwik,
Data Analyst
KPMG

## Task 2: Data Insights

### Introduction:

Task 2 marks a pivotal phase in our analysis journey for Sprocket Central Pty Ltd. Here, we delve into the intricacies of transforming data into actionable insights, leveraging advanced analytics techniques to recommend targeted strategies for driving business growth. With a focus on analyzing a new list of 1000 potential customers, our goal is to unlock valuable customer insights and optimize resource allocation for targeted marketing.

### Data Exploration:

In the Data Exploration phase, we embark on a journey to unravel the hidden patterns and trends within the dataset. Our approach involves a meticulous examination of the characteristics and distributions of key variables, shedding light on customer demographics, preferences, and behaviors. Through exploratory data analysis techniques, we gain a deeper understanding of the dataset's structure and uncover potential biases or anomalies. This phase lays the foundation for subsequent analysis, guiding our path towards informed decision-making.

### Model Development:

The Model Development phase represents a critical stage in our analysis process, where we harness the power of predictive modeling to derive actionable insights. Here, we leverage sophisticated algorithms and machine learning techniques to construct predictive models tailored to Sprocket Central Pty Ltd's specific objectives. Our approach involves selecting appropriate algorithms, fine-tuning model parameters, and rigorously validating model performance to ensure robustness and accuracy. By transforming data into predictive intelligence, we aim to uncover valuable customer behavior patterns and inform strategic decision-making.

### Interpretation:

In the Interpretation phase, our focus shifts to extracting meaningful insights from the developed models and translating them into actionable recommendations. Here, we dissect the model outputs, examine the significance of key features, and analyze the relationships between variables. Through comprehensive interpretation, we bridge the gap between complex analytics and practical business strategies, ensuring that the results generated have real-world impact and contribute to the overarching success of Sprocket Central Pty Ltd. This phase serves as the culmination of our analysis journey, where data-driven insights pave the way for informed decision-making and strategic growth.

## Task 3: Data Insights and Presentation

In Task 3, the focus shifted to creating a dynamic and visually appealing dashboard to present the results of the analysis to the client. The dashboard served as a centralized platform to showcase data summaries, analysis results, and key findings, enabling stakeholders to gain actionable insights at a glance. Specific recommendations were provided regarding Sprocket Central's marketing and growth strategy, targeting the 40-60 age group in NSW State, with a preference for the manufacturing industry. The presentation highlighted the significance of leveraging data-driven insights to inform strategic decision-making and maximize business impact.

![Alt Text](https://github.com/Ruthwik14/Power-BI/blob/main/KPMG%20%20-%20Unleashing%20Insights%20and%20Strategies%20for%20Sprocket%20Central's%20Success/Power%20BI%20Dashboard.jpg)


## Conclusion:

Overall, this project exemplifies the power of data analytics in driving informed decision-making and achieving strategic objectives. By conducting comprehensive data analysis, assessing data quality, and presenting actionable insights in a clear and concise manner, Sprocket Central Pty Ltd can enhance its marketing effectiveness, optimize resource allocation, and ultimately, achieve sustainable business growth. The project underscores the importance of collaboration between data analysts and business stakeholders to unlock the full potential of data-driven strategies and propel organizations towards success.

For detailed documentation and deliverables related to each task, please refer to the respective folders in this repository.

Thank you for your interest in this project.
