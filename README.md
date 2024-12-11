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
   
   • Load the Dataset: The dataset was sourced from the Vancouver city open data portal and stored in an Amazon S3 bucket named foodhousing-raw-sai.
   •	Data Cleaning: Using AWS Glue DataBrew, we performed profiling and cleaning to address missing values, correct data types, and remove duplicates.

3.	Descriptive Statistics:
   
   •	Calculate Summary Statistics: Key variables were summarized to include the total number of unresolved issues per area, comparing these with the total units in each geographic location.

5.	Data Visualization:
   
   •	Visual Representations: We created visualizations to illustrate findings, such as bar charts showing unresolved issues by area.

7.	Insights and Findings:
   
   •	Summarize Insights: We tracked the number of units operating with unresolved issues and compared this across different areas in Vancouver. This information helps city authorities take steps to improve the process of clearing issues or resolving building problems, providing better living conditions for residents.

9.	Recommendations:
    
   •	Actionable Steps: Based on our findings, we recommend targeted regulatory actions to address areas with high numbers of unresolved issues, ensuring quicker resolution and compliance with by-laws.

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
   
   •	Load the dataset from S3 storage (s3://foodhousing-trf-sai/Rental_Records/Data-Cleaning/System/).
   •	Perform initial data cleaning to handle missing values, correct data types, using AWS data brew and ensure data consistency.

3.	Descriptive Statistics:
   
   •	Generate summary statistics for key variables such as the total number of units and issues across different areas.

5.	Data Visualization:
   
   •	Create visualizations to illustrate key insights
   •	Bar Charts: Showing the number of unresolved issues and total units by area.
   •	Histograms and Boxplots: To analyze the distribution of continuous variables like the total number of units and issues.



7.	Issue Rate Analysis:
   
   •	Calculate the issue rate for each area by comparing the total number of unresolved issues with the total units.
   •	Identify areas with high issue rates to prioritize for intervention.

9.	Insights and Findings:
    
   • Summarize findings based on visualizations and statistical analyses, highlighting notable trends and patterns, such as areas with the highest and lowest issue rates.

11.	Conclusion:
    
   • Discuss the implications of the findings and suggest further actions or data-driven decisions that could help in addressing the unresolved rental issues more effectively.



![image](https://github.com/user-attachments/assets/e82e769d-791d-4ec7-a120-23c32bd74dda)


# Project 3: Data Wrangling

**Project Description** 

This project showcases my experience in data wrangling for HR and Occupational Health & Safety analytics using AWS DataBrew. By performing profiling, cleaning, and transformation using ETL pipelines, I prepared a robust dataset that enhanced the accuracy and usability of HR and OHS data for analysis and reporting.

**Objective**

The primary goal of this project was to perform comprehensive data wrangling to prepare a robust dataset for HR and OHS analytics at UCW. By cleaning, transforming, and consolidating data from various sources, the project aimed to enhance the accuracy and usability of HR and OHS data for subsequent analysis and reporting.

**Background**
UCW accumulated data from multiple departments, including HR records, safety incident reports, and worker lists. However, this data was often inconsistent, incomplete, or fragmented, making it challenging to derive meaningful insights. Effective data wrangling facilitated better decision-making and more targeted safety and HR strategies.

**Dataset**

The data wrangling process involved various datasets, including:

•HR-OHS-SRL-Prj-Sai: Supervisor Reports List

•HR-OHS-SIL-Prj-Sai: Safety Incident List

•HR-OHS-WL-Prj-Sai: Workers List

**Methodology**

1. Data Collection

•Gathered datasets from various sources, including internal HR databases, safety incident reporting systems, and worker management platforms.
•Ensured all relevant datasets were identified for a comprehensive view of HR and OHS metrics.

2. Data Assessment

•Conducted an initial assessment of data quality to identify issues such as missing values, duplicates, and inconsistencies across different datasets.
•Documented data types, formats, and any discrepancies.

3. Data Cleaning

•Addressed missing values through appropriate methods based on their significance and context.
•Removed duplicate records and corrected inconsistencies in data formats.
•Normalized categorical variables to ensure consistency across datasets.

4. Data Transformation

•Performed data type conversions to ensure all fields were in suitable formats for analysis.
•Derived new features that aided in analytics, such as incident frequency, resolution time, and worker tenure.
•Aggregated data as necessary to ensure it aligned with the intended analysis.

5. Data Consolidation

•Merged datasets into a unified HR and OHS database, ensuring all relevant information was accurately linked through unique identifiers.
•Created a comprehensive view of each worker by combining HR records, safety incidents, and supervisor reports.

6. Documentation and Validation

•Documented the data wrangling process, including data sources, cleaning methods, and transformations applied.
•Validated the final dataset through exploratory data analysis (EDA) to confirm accuracy and completeness.

**Tools and Technologies**

•AWS DataBrew: For data profiling, cleaning, and transformation.

**Deliverables**

•A cleaned and transformed HR and OHS dataset ready for analysis, available in a suitable format (e.g., CSV, Excel Database).


# Project 4: Data Quality and Control #

**Project Description**

This project showcases my experience in implementing comprehensive Data Quality Control (DQC) measures using AWS Glue. By performing profiling, cleansing, and transformation through ETL pipelines, I ensured the data's high quality, privacy, compliance with laws, and security for City of Vancouver

**Objective**

The primary objective of this project was to establish a comprehensive DQC framework to ensure the accuracy, completeness, consistency, and reliability of the organization's data, enhancing decision-making processes and overall business performance.

**Background**

As City of Vancouver continued to expand its operations and data sources, issues related to data quality surfaced, including inaccuracies, duplicate records, and inconsistent formats. Poor data quality can lead to misguided business strategies, inefficiencies, and regulatory compliance risks. This project aimed to implement robust data quality control measures to mitigate these issues.

**Scope**

The project focused on the following key areas:

•Data Profiling: Analyzing existing datasets to assess quality levels.
•Data Cleansing: Developing processes to correct inaccuracies and eliminate duplicates.
•Data Validation: Implementing validation rules and checks to ensure data integrity.
•Monitoring and Reporting: Establishing ongoing monitoring processes and dashboards to track data quality metrics.

**Methodology**

1. Current State Assessment

•Conducted a thorough analysis of current data sources, workflows, and existing data quality challenges.
•Identified key datasets that significantly impact business operations and decision-making.

2. Data Profiling

•Utilized data profiling tools to assess the quality of identified datasets, focusing on completeness, uniqueness, validity, consistency, and accuracy.
•Documented findings to highlight areas requiring immediate attention.

3. Establish Data Quality Metrics

•Defined clear data quality metrics and key performance indicators (KPIs) to evaluate and track data quality over time, such as error rates, duplicate records, and compliance with data standards.

4. Data Cleansing Processes

•Developed and implemented procedures for data cleansing, which included:
•Removing duplicates and correcting errors.
•Standardizing data formats and values.
•Filling in missing values using appropriate imputation techniques.

5. Validation Rules and Procedures

•Set up validation rules for new data entries to reduce the risk of poor-quality data being introduced into the system.
•Created data entry guidelines to promote consistency and accuracy.

6. Monitoring and Reporting

•Implemented monitoring tools and dashboards that provide real-time data quality metrics and alerts for significant deviations.
•Scheduled regular reports to review data quality trends and performance against established KPIs.

7. Feedback Mechanism
•Established a feedback loop to continually assess and improve data quality processes based on user input and observed results.

**Tools and Technologies**

•AWS Glue: For data extraction, transformation, and loading (ETL) pipeline creation.
•"Evaluate Data Quality" Transform: To apply specific rules ensuring data meets high standards.
•S3 Storage: For storing processed data in separate "passed" and "failed" folders.


**Deliverables**

•A comprehensive Data Quality Control plan detailing processes, metrics, and responsibilities.
•Documentation of data quality metrics and KPIs being tracked.
•Cleaned and validated datasets ready for analysis and reporting.
•A monitoring dashboard that visualizes data quality metrics in real-time.

**Timeline**

•Expected completion of the project: 8 weeks, including assessment, implementation, training, and monitoring setup.


