# Projects
Overview of the Projects.

# Project 1: Descriptive Analysis

**Project Description:** Descriptive Analysis of Rental Issues in Vancouver

**Project Title:** Understanding Unresolved Rental Issues in Vancouver

**Objective:** The primary goal of this project is to conduct a descriptive analysis of rental issues data in Vancouver. We aim to summarize key characteristics of these issues, identify trends, and generate insights that can inform regulatory actions and improve living conditions for residents.

**Dataset:** The dataset includes information about rental properties in Vancouver that have five or more units and currently have unresolved by-law issues. The key features are:
•	Geo_Local_Area: Geographic location of the rental units
•	Total Units: Number of rental units
•	Total Issues: Number of unresolved rental issues

**Methodology:**
1.	Data Collection and Preparation:
o	Load the Dataset: The dataset was sourced from the Vancouver city open data portal and stored in an Amazon S3 bucket named foodhousing-raw-sai.
o	Data Cleaning: Using AWS Glue DataBrew, we performed profiling and cleaning to address missing values, correct data types, and remove duplicates.
2.	Descriptive Statistics:
o	Calculate Summary Statistics: Key variables were summarized to include the total number of unresolved issues per area, comparing these with the total units in each geographic location.
3.	Data Visualization:
o	Visual Representations: We created visualizations to illustrate findings, such as bar charts showing unresolved issues by area.
4.	Insights and Findings:
o	Summarize Insights: We tracked the number of units operating with unresolved issues and compared this across different areas in Vancouver. This information helps city authorities take steps to improve the process of clearing issues or resolving building problems, providing better living conditions for residents.
5.	Recommendations:
o	Actionable Steps: Based on our findings, we recommend targeted regulatory actions to address areas with high numbers of unresolved issues, ensuring quicker resolution and compliance with by-laws.

**Tools and Technologies:**
•	Amazon S3: For storing raw and transformed data.
•	AWS Glue DataBrew: For data profiling and cleaning.
•	AWS Glue ETL: For extracting, transforming, and loading data.

**Deliverables:**
•	Detailed Report: Summarizing methods, findings, and recommendations.
•	Visualizations: Charts and other graphics to present key insights.
•	Presentation: For stakeholders, communicating important findings and suggesting future actions.

![image](https://github.com/user-attachments/assets/25990da3-e528-4876-a73c-a93acc2683e0)

# Project 2: Exploratory Data Analysis

**Project Title:** Analyzing Unresolved Rental Issues in Vancouver

**Project Description:** This project involves an exploratory data analysis (EDA) of rental issues in Vancouver. Using the dataset, we aim to uncover patterns, trends, and insights related to unresolved rental problems across different areas in Vancouver. This analysis helps in identifying high-priority areas requiring attention and potential improvements.

**Objective:** The primary goal of this project is to perform an exploratory data analysis (EDA) on the rental issues dataset to identify trends and patterns, understand the distribution of unresolved issues, and generate insights that can assist city authorities in prioritizing areas for intervention.

**Dataset:** The dataset includes information about rental properties in Vancouver with unresolved by-law issues. Key features are:
•	Geo_Local_Area: Geographic location of the rental units
•	Total Units: Number of rental units
•	Total Issues: Number of unresolved rental issues

**Methodology:**
1.	Data Collection and Preparation:
o	Load the dataset from S3 storage (s3://foodhousing-trf-sai/Rental_Records/Data-Cleaning/System/).
o	Perform initial data cleaning to handle missing values, correct data types, and ensure data consistency.

2.	Descriptive Statistics:
o	Generate summary statistics for key variables such as the total number of units and issues across different areas.

3.	Data Visualization:
o	Create visualizations to illustrate key insights:
	Bar Charts: Showing the number of unresolved issues and total units by area.
	Histograms and Boxplots: To analyze the distribution of continuous variables like the total number of units and issues.
	Heatmaps: Visualizing the correlation between different variables.

4.	Issue Rate Analysis:
o	Calculate the issue rate for each area by comparing the total number of unresolved issues with the total units.
o	Identify areas with high issue rates to prioritize for intervention.

5.	Insights and Findings:
o	Summarize findings based on visualizations and statistical analyses, highlighting notable trends and patterns, such as areas with the highest and lowest issue rates.

6.	Conclusion:
o	Discuss the implications of the findings and suggest further actions or data-driven decisions that could help in addressing the unresolved rental issues more effectively.



![image](https://github.com/user-attachments/assets/e82e769d-791d-4ec7-a120-23c32bd74dda)




