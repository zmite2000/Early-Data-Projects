# File Title: Shopify Power BI

This was the fifth project in the TripleTen Business Intelligence Analytics Program. It was an independent project designed to showcase the use of Tableau Dashboards and Story Telling. The project's purpose and scope was to prepare an analysis for the CEO of Superstore to help them understand what is causing customers to return their orders and how to reduce the volume of returned orders.

<img width="1031" alt="Screenshot 2025-02-02 at 4 23 24 PM" src="https://github.com/user-attachments/assets/70983a72-49f2-429c-8e71-c2ef6c404317" />


# Table of Contents for Repository Artifacts

| Project number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [Mock-up Dashboard SuperStore.pdf](https://github.com/zmite2000/Early-Data-Projects-TripleTen/blob/main/SuperStore%20Returns/Mock-up%20Dashboard%20SuperStore.pdf) | The is a .pdf of three different mockups drawn out before creating them in Tableau. |
| 2 | [README.md](https://github.com/zmite2000/Early-Data-Projects-TripleTen/blob/main/SuperStore%20Returns/README.md) | This current page with all relevant information about the project, just past the Table of Contents |
| 3 | [Requirements.rft](https://github.com/zmite2000/Early-Data-Projects-TripleTen/blob/main/SuperStore%20Returns/Requirements.rtf) | A simple .rft file with the provided project requirements as provided by TripleTen. |
| 4 | [SuperStore Storytelling - Presentation.pdf](https://github.com/zmite2000/Early-Data-Projects-TripleTen/blob/main/SuperStore%20Returns/SuperStore%20Storytelling%20-%20Presentation.pdf) | This pdf is a screen grab by section in Tableau showcasing each graph requirement, dashboard and story board. |
| 5 | [Tableau SuperStore Dashboard Link.md](https://github.com/zmite2000/Early-Data-Projects-TripleTen/blob/main/SuperStore%20Returns/Tableau%20SuperStore%20Dashboard.md) | This document provides a link to the public Tableau dashboard - it is a live link that leverages filters and the resulting story board. |



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

- 7 Tableau Visualizations, 1 Dashboard, and a 9-page Story Presentation
- Includes data analysis, charts, dashboard mock-ups, final dashboard, and Tableau story

**Process:**

Uploaded the data file to Tableau and left join the data sheets for unique IDs. The analysis was performed using filters, formating of data, adding calcuations and visualizations to determine what is causing returns. A dashboard for monitoring returns ws created. Lastly, the Tableau story tool was used to present findings.

**Data**

The data was one Excel spreadsheet file provided by TripleTen:

- 'Superstore.xls': each row corresponds to one product sold; sheets were LEFT JOIN'd
- 'orders': details all fields for each ordered item
- 'returns': details all fields for each returned item

**Assumptions:**

- Profits from sales are totaling in the negative.
- There is one or more causes for negative profits directly related to orders and returns.
- The operations department will need to make changes.

**Findings:**

- There are several customers with unusually high return rates; Several customers have a return rate of 100%.
- There are several products with unusually high return rates; Several products have a return rate of 100%.
- The top three Total Sales months with the highest Return Rates: September, November, December.
- Returns are measured in two forms for this analysis: Return Rate (%) and Total Count of Returns. Total Count of Returns compares the impact of frequency - a higher frequency of return to lower total sales vs low frequency of return to higher total sales. Return Rates help to locate potential root causes much quicker when applied to different dimensions.
- Preliminary root causes indicate this could be Business Cycle implying yearend purchases to use up budgets with higher beginning of the year Return Rates. It could also be back to school (Sept and Dec) have higher sales and return rates during those months.

**Recommendations:**

1. Employee training in the technology department to better assist customers in choosing the right product.
2. Reach out to customers with a 100% return rate to determine the reasons behind their decision. Implement any changes needed in our website or shipping partners that are causing these returns.
3. As triage, immediately stop selling the problem products.
4. Focus internal efforts on updating product information, and size guides, and promoting customer reviews via social media collaborations.
5. Consider stricter return policies or charging a return fee for purchases made in problem states.
6. Adjust promotional strategies such as promoting gift cards for holiday peaks, and shifting from discounts to value-added like free shipping.

