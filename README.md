# Step into the World of Fault Analysis

#### In a leading company, operations seemed to be running smoothly—systems were functioning, production was ongoing, and business was thriving. But beneath the surface, a hidden crisis was unfolding. Recurring faults and unexpected downtimes were causing inefficiencies, leading to rising maintenance costs and operational disruptions. As a data analyst, I was tasked with uncovering the root cause of these failures. What I discovered would reshape the company’s approach to fault management and system optimization. Join me as I delve into historical fault logs, uncovering hidden patterns and revealing the crucial insights that will lead to a game-changing solution. **

Following my initial analysis, the next critical step was data cleaning and preparation to ensure accuracy and reliability in fault detection. My steps included:

Examining summary statistics to identify inconsistencies, missing values, and anomalies.

Removing duplicate or erroneous logs to enhance data integrity.

Engineering new features by adding calculated columns to extract deeper insights.

Applying advanced techniques like anomaly detection, normalization, and imputation to refine the dataset.

Through this meticulous data cleaning process, previously hidden fault patterns emerged, allowing for a more precise and data-driven diagnosis of system inefficiencies. With this newfound clarity, we could now move forward in implementing targeted preventive measures, setting the stage for a more reliable and optimized system. 

## Analysis Insights from EDA

- Most Common Fault Type

![image](https://github.com/user-attachments/assets/b8f87b71-574b-4dd9-af37-ddace93a90d1)

- Average Load by Temperature

![image](https://github.com/user-attachments/assets/fcddae16-5ad5-44aa-8fd7-af937b061422)

- Number of fault by Temperature

![image](https://github.com/user-attachments/assets/cd1b8008-e8e5-462d-98aa-386277ec01a5)

- Downtime by Temperature Range

![image](https://github.com/user-attachments/assets/6a991e73-c815-4446-8a3c-ba08a3d02e6c)

- Faults at Different wind Speeds

![image](https://github.com/user-attachments/assets/4ccf06af-b193-4ae8-bfe9-fe5ad4502830)

- Component Health against Fault

![image](https://github.com/user-attachments/assets/8bc025d6-4bef-464e-80b9-6cdf88a7e94e)

- Downtown vs FAult Severity

![image](https://github.com/user-attachments/assets/d57c593f-d0aa-4bb5-be63-1c0752be80d7)


# Conclusion 

This project explored fault analysis using Python to identify key failure patterns and system performance trends. 


The findings revealed that transformer failures and overheating were the most common fault types, indicating potential areas for preventive maintenance.


A correlation analysis between temperature and power load showed a weak relationship (0.0886), suggesting that while temperature variations exist, they may not be the primary driver of increased load or failures. However, further investigation into weather conditions, such as high wind speeds during storms, is needed to determine their impact on system faults.


Additionally, an assessment of component health and fault occurrences highlighted that poor component conditions are often linked to failures, reinforcing the importance of regular maintenance. Finally, faults with the longest recovery times were identified, providing insights into which failures cause significant downtime and require optimized repair strategies.


Overall, this analysis helps improve fault detection, preventive maintenance, and system reliability, ensuring better operational efficiency.




