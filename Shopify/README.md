# File Title: Shopify Power BI

This was the 6th project in the TripleTen Business Intelligence Analytics Program. It was an independent project designed to showcase the skills developed for using Power BI visualizations and analytical power. The purpose was to review the landscape of apps on the Shopify platform, using data scraped from publicly available Shopify websites, and to figure out what key factors play into the success of a Shopify app.


# Table of Contents for Repository Artifacts

| Project number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [README.md](https://github.com/zmite2000/Early-Data-Projects-TripleTen/blob/main/Shopify/README.md) | This current page with all relevant information about the project, just past the Table of Contents |
| 2 | [Requirements.rft](https://github.com/zmite2000/Early-Data-Projects-TripleTen/blob/main/Shopify/Requirements.rtf) | A simple .rft file with the provided project requirements as provided by TripleTen. |
| 3 | [Shopify Power BI Summary.pdf](https://github.com/zmite2000/Early-Data-Projects-TripleTen/blob/main/Shopify/Shopify%20Power%20BI%20Summary.pdf) | This pdf is a screen grab of each question answered for the assignment using Power BI for cards, graph requirement, and finding. |




# Table of Contents for README.md

| Section Title | Description |
| ------------- | ----------- |
| Description | Describes the final product's purpose, software, format and included visuals. |
| Process | Describes the process, including tools or tech used for the analysis and presentation. |
| Data | Describes the sources of data, including files, tables and fields. |
| Assumptions | Describes assumptions to include fiven by TripleTen and assumptionsmade based on the data and task. |
| Findings | Insights learned from the data analysis |


**Description:**

- 8 page Power BI Analysis
- Includes data analysis, KPI cards and Charts

**Process:**

Loading the data into Power BI revealed data cleaning was required. After the clean up the app store landscape was assessed first using KPI cards and charts. Then the review data was analyzed with cards and charts. Lastly, the app developers review types were analyzed for relationship and trending.

**Data**

The Excel file provided by TripleTenwas was public data scraped from the Shopify App Store.

- 'shopify.xlsx': Excel Workbook containing 4 sheets:
- 'apps': Details of the apps on the Shopify apps marketplace
- 'apps_categories': Join tables to connect apps with categories
- 'categories': Categories of the apps. Each app has multiple categories
- 'reviews': Each review (row) contains information on user opinion about the related app (rating and comment). Also, it contains response from the developer if present.

**Assumptions:**

- The scraped data from Shopify websites is accurate and representative of the actual app landscape.
- The data in the shopify.xlsx file is complete and consistent, with minimal missing values or inconsistencies.
- The provided column names and data types in the tables accurately reflect their content.

**Findings:**

1. New Apps are more likely to be rated early in their deployment.
2. Most apps are rated favorably.
3. Reviews are higher for an app if a developer answers the review.
4. The relationship between Reviews Count and Average Rating is positive correlation (strong) with clustering in the top left quadrant. The plot does have a couple of outliers.
5. Reviews that have been voted as helpful have a weighted average of 5.48.
