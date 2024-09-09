## overview
As part of a strategic initiative to diversify its portfolio, the company is expanding into the aviation industry, with a specific focus on purchasing and operating aircraft for both commercial and private enterprises. Given the high-risk nature of the aviation sector, it is crucial to identify which aircraft pose the least risk to the company's new business endeavor. This project aims to analyze aviation incident data to determine the safest aircraft types and provide actionable insights to guide the purchasing decisions for the company.
The analysis is based on historical aviation data, assessing factors such as the purpose of flights (business vs. personal), injury records, aircraft types, and conditions associated with incidents. By identifying trends and patterns in the data, the project seeks to make informed recommendations regarding the types of aircraft that offer the lowest operational risk, ensuring both safety and profitability for the company's aviation division.
Through statistical analysis and visualization, this project offers a comprehensive risk assessment to aid decision-making in aircraft selection, while ensuring compliance with safety standards and minimizing operational risks.

## Business problem
As the company expands into the aviation industry, it faces a critical decision in selecting the most appropriate aircraft for commercial and private operations. However, the company has limited knowledge of the risks associated with different types of aircraft and flight purposes. The primary objective is to analyze historical aviation data to identify which aircraft present the lowest risk for business and personal flights, enabling the company to make informed purchasing decisions that align with safety and operational efficiency. This analysis aims to provide actionable insights based on injury trends, aircraft performance, and other relevant factors, ensuring that the company can confidently invest in the aviation sector while minimizing risk.

## The Data
The data is sourced from (https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses) from the National Transportation Safety Board that includes aviation accident data from 1962 to 2023 about civil aviation accidents and selected incidents in the United States and international waters.

## Questions to consider:
1.Which types of aircraft are involved in the most accidents?
2.Are business flights consistently less risky compared to personal flights?
3.How does injury severity vary based on the purpose of flight?
4.How does the purpose of the flight (personal vs. business) influence the risk level?

## Description of data
>#numpy for high level mathematical functions and working with Arrays
>import numpy as np
>#pandas data manipulation and analysis for tablular data
>import pandas as pd
>#seaborn and matplotlib for data visualization
>import seaborn as sns
>import matplotlib.pyplot as plt
>%matplotlib inline

## loading data
>df_aviation_data = pd.read_csv("AviationData.csv", encoding = "cp1252",low_memory=False)
>df_states_codes = pd.read_csv("USState_Codes.csv")

## cleaning data
>cleaned(df_aviation_data_2)
>cleaned(df_states_codes_2)

## Visualizations

![output](./images/notebooks_output.png)
![output](./images/notebooks_output2.png)
![alt text](output-1.png)


## conclusion
1. Based on the analysis, business flights tend to exhibit fewer serious injuries and accidents compared to personal flights. It is recommended that the company prioritize aircraft designed for commercial use, as they appear to carry lower operational risk.
2. The analysis indicates that personal flights tend to have higher injury and fatality rates compared to business flights. Personal flights are associated with higher instances of severe injuries and fatalities, potentially due to less stringent operational protocols compared to commercial operations.
3. Business flights showed lower instances of serious and fatal injuries compared to personal flights. This suggests that business flights, likely conducted under stricter operational oversight, are generally safer and may be a lower-risk investment for the company.
4. The fatality rates are notably higher in personal flights, suggesting a higher risk for the company if it were to target the private aviation sector without strict risk management measures.# My-project
