# File Title: Zomato Customer Segmentation Analysis

This was the Final project for the TripleTen Business Intelligence Analytics Program. It was an independent project designed to showcase what has been learned throughout the TripleTen Program. The purpose was to complete the Zomato onboarding project to showcase analytical skills to the mock company.


<img width="1180" alt="Screenshot 2025-02-02 at 6 16 31 PM" src="https://github.com/user-attachments/assets/94894979-35f8-456a-a3c8-bd05a43d5dc7" />

# Table of Contents for Repository Artifacts

| Project number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [Zomato Data](https://github.com/zmite2000/Early-Data-Projects-TripleTen/tree/main/Zomato/Zomato%20data) | Folder containing 2 CSV files, one for each table used in the analysis. |
| 2 | [README.md](https://github.com/zmite2000/Early-Data-Projects-TripleTen/blob/main/Zomato/README.md) | This current page with all relevant information about the project, just past the Table of Contents |
| 3 | [Requirements.rft](https://github.com/zmite2000/Early-Data-Projects-TripleTen/blob/main/Zomato/Requirements.rtf) | A simple .rft file with the provided project requirements as provided by TripleTen. |
| 4 | [Final Project - Zomato - Analysis.pdf](https://github.com/zmite2000/Early-Data-Projects-TripleTen/blob/main/Zomato/Final%20Project%20-%20Zomato%20%E2%80%93%20Analysis.pdf) | The final project analysis and report in pdf format. |
| 5 | [Final Project - Zomato - Planning.pdf](https://github.com/zmite2000/Early-Data-Projects-TripleTen/blob/main/Zomato/Final%20Project%20-%20Zomato%20%E2%80%93%20Research%20Plan.pdf) | The planning package for research to be done, approach to data, analysis questions and tool consideration. |



# Table of Contents for README.md

| Section Title | Description |
| ------------- | ----------- |
| Description | Describes the final product's purpose, software, format and included visuals. |
| Process | Describes the process, including tools or tech used for the analysis and presentation. |
| Data | Describes the sources of data, including files, tables and fields. |
| Assumptions | Describes assumptions to include fiven by TripleTen and assumptionsmade based on the data and task. |
| Findings | Insights learned from the data analysis |
| Recommendations | Recommended direction for the stakeholders based on final analysis. |



**Description:**

- This was a Customer Segmentation Analysis.
- 3 pages in Power BI. Includes KPI cards, Pie charts, bar charts, and RFM analysis.
- 2 pages of conclusions
- 1 page of recommendations

**Process:**

The project began with a Decomposition Plan outlining the approach, data plans, analysis and conclusion concepts. After the plan was approved Power BI was the tool selected to use for the analysis and visualizations. Data cleaning was required to convert to standard currency, date formats and removal of negative data. A calcuation was performed to better understand the data. The data was then broken into segments to gather insights and determine relationships. A set of insight statements is provided in the conclusion and recommened next steps.

**Data**

TripleTen provided an archived file of 5 separate Excel files from the mock company Zomato. Two of those files were used for the project.

- 'Zomato data.zip': Compressed Excel files provided by team lead
    - 'orders': All orders made from the menu by all customers at all restaurants between Oct. 4th, 2017, and June 26th, 2020.
    - 'users': All customers who completed orders during the designated time frame and their demographic information.

**Assumptions:**

- The provided test datasets are accurate, complete, and consistent.
- Missing values or inconsistencies were corrected where possible. Those that were note corrected were minimal and will not significantly impact the analysis.
- The column descriptions accurately reflect the content of each table.
- The provided tables (orders and users) contain all the necessary information for the chosen analysis.
- Zomato's business context and industry trends are considered while interpreting the data.

**Findings:**

- Primary Customer Segement:
    - Age: 75% of purchasers are ages 21-26 years old (dataset range is 18-33 years old)
    - Gender: 45% female/55% male (dataset split 43% female/57% male)
    - Marital Status: 83% are single (dataset 69% single)
    - Occupation: 66% are students/23% are employees (dataset 54% student/30% employee)
    - Monthly Income: 56% have no income (dataset 48% no income)
    - Education: 53% Post-Graduate/40% Graduate (dataset 45% Post-Graduate/45% Graduate)

- Sales Insights
    - Total monthly sales is consistently Students, Employee, Self Employed, House Wife in that order of highest to lowest month over month.
    - There is a strong correlation between age and average total sale. As age increases the average sales total increases as well. This was stronger in males than females.
    - From a sales month perspective highest sales were July and August. Whereas the lower months are Sept-Dec. Males have a higher purchasing amount due there being more of them in the sample size. This also holds true for education levels of purchasers (90% are Graduate or Post Graduate).

- Recommendations:
    - The data shows over 1600 purchases equal to 0 INR. This may indicate a sales initiative to bring customers in with a free offering. It is recommended exploring the effectiveness of that campaign in retaining customers. What is the frequency of purchases? What is the purchase value each time? What percentage never came back?
    - 494 distinct purchasers (0.63%) have orders greater than 200,000 INR. Sales totaling 187,589,412 INR. This accounts for roughly 20% of the total sales in the data. Most of it comes from students and employees. Further research is recommended for this customer segment in terms of large orders.
