# Data_Science_Salaries_2023

**Data_Science_Salaries_2023** is a comprehensive data analysis tool designed to streamline data exploration, analysis, and visualisation. The tool supports multiple data formats and provides an intuitive interface for both novice and expert data scientists.


## Dataset Content

* Data_Science_Salaries_2023 is a dataset that comprises of the salaries of workers in the field of data science listing their Job Title, Work Type, location, Salary and job format whether remote, hybrid or office based


## Business Requirements

-The goal is to ascertain the roles that pays the most
-The influence of job title and experience level on salaries
-The impact of remote work in the data science field
-Company size affecting employee's salary


## Hypothesis and how to validate?

* Test # _____________|Hypothesis|___________|Test Type|_________________Purpose
1   Data Scientists earn significantly      Two-sample t-test	   Compare job titles
                                                                   more than Data Analysts

2	Average salary differs significantly    Two-sample t-test	   Remote work impact
    between Remote and On-site jobs	

3	Salaries vary significantly across 
company sizes (Small, Medium, Large)       ANOVA.      Test for differences       
                                                       differences between 3+ groups          
                                                          
4	Proportion of remote jobs        Chi-square test               Categorical association
by job title

## Project Plan
* I followed this plan:

1. ETL: Extract, Transform, Load

Loaded the dataset
Checked for duplicates and missing values
Created a new column () salary_in_gbp
Saved cleaned data

2. Data Analysis

Calculated mean average on salaries
Analysed the highest paying role
Compared data analyst role vs ML engineer to ascertain the most paying role
Find key drivers influencing salary variations

3. Visualisations:

Created charts using Matplotlip, Seaborn and Plotly

4. Documentation:

Wrote this README and added comments to my notebook

* How was the data managed throughout the collection, processing, analysis and interpretation steps?

1. Data Collection
I used a publicly available dataset that included details like job titles, salaries, experience levels, company sizes, and work locations. This gave a good overview of salaries in the data science field.

2. Data Processing
Before analysis, I cleaned the data to make sure it was accurate and ready to use:

By checcking for missing values and duplicates

3. Data Analysis
I explored the data using charts and graphs to spot trends—for example, how salaries change with experience or location. I also did some basic statistics and created models to understand which factors most affect salary.

4. Data Interpretation
Finally, I looked at what the results meant. I found, for example, that remote work and job title had a big effect on salary. I shared these findings through simple visuals and explained what they could mean for someone entering the field or hiring data professionals

* Why did you choose the research methodologies you used?

I chose a combination of Exploratory Data Analysis (EDA), quantitative research, and predictive modeling methodologies for analyzing the data science salaries dataset because they best aligned with my goals: to uncover trends, understand the factors influencing salary, and build a model to predict future salaries
Exploratory Data Analysis (EDA) was essential as a first step to understand the structure and quality of the dataset. It allowed me to:

Detect missing values and outliers

Visualize salary distributions across experience levels, job titles, countries, and employment types

Identify initial patterns and correlations between variables

Quantitative analysis was applied to measure and compare salary differences across categories. For instance:

I used grouped descriptive statistics to compare average salaries across regions

Correlation analysis helped identify the strength of relationships between numerical variables like experience level and salary

To gain deeper insights, I employed inferential statistics (like ANOVA and regression analysis) to test whether observed differences were statistically significant, especially between different job roles or geographic locations.

Finally, I used predictive modeling techniques (e.g., linear regression and decision trees) to forecast salaries based on features such as experience, education, company size, and remote work ratio. These models were evaluated using cross-validation and performance metrics like RMSE and R² to ensure reliability.

Overall, this methodological approach allowed me not only to describe the current state of data science salaries but also to predict and explain key drivers influencing salary variations.


## The rationale to map the business requirements to the Data Visualisations

1. Understanding Salary Distribution
Business Requirement: Identify overall salary trends and detect outliers.

Visualisation Used: Histogram and Boxplot

Rationale: These visuals made it easy to see the typical salary range, average pay, and any unusually high or low salaries.

2. Comparing Salaries by Role, Experience, and Location
Business Requirement: Help hiring managers and job seekers understand how salary changes based on different factors.

Visualisation Used: Bar charts and grouped boxplots

Rationale: Bar charts compared average salaries across roles or regions, while boxplots showed how experience level impacted salary.

3. Identifying Top-Paying Job Titles
Business Requirement: Help companies benchmark competitive salaries for specific roles.

Visualisation Used: Sorted bar chart

Rationale: Quickly highlights which job titles have the highest median salaries.

4. Remote vs In-Office Salary Comparison
Business Requirement: Evaluate whether remote roles pay more or less than office-based ones.

Visualisation Used: Grouped bar chart or side-by-side boxplot

Rationale: Easy visual comparison of remote, hybrid, and in-office salary trends.

5. Salary Prediction Factors
Business Requirement: Understand what drives salary increases.

Visualisation Used: Correlation heatmap or feature importance chart from model

Rationale: These visuals clearly show which variables (like experience, job title, or location) have the biggest impact on pay.

## Analysis techniques used

1. Data Analysis Methods Used and Limitations/Alternatives
I used a mix of exploratory data analysis (EDA), descriptive statistics, and predictive modeling:

EDA (e.g., histograms, bar charts) helped identify trends and patterns in salary distributions.

Correlation analysis revealed relationships between salary and variables like experience or remote work.

Regression models were used to predict salary outcomes.

Limitations:

No limitations


For imbalance, I tested resampling techniques or grouped categories for clearer trends.

2. How I Structured the Data Analysis Techniques
The analysis followed a logical structure:

Data Cleaning – Ensuring consistency and checking for missing values and duplicates

Exploration – Identifying patterns through visualisation

Statistical Analysis – Testing assumptions and relationships

Modeling – Using regression to predict salary

Interpretation – Drawing actionable insights

Justification:
This step-by-step structure ensured the data was well-understood before applying models, reducing the risk of misinterpretation.

3. Data Limitations and Alternative Solutions
Yes, the data had some limitations:

Geographic imbalance (e.g., most entries from the US or Europe)

Lack of context like company industry or job benefits

Alternatives Used:

Grouped countries into broader regions for better comparison.

Focused more on well-represented roles and levels to avoid misleading insights.

4. Use of Generative AI Tools
I used generative AI tools like ChatGPT and GoogleColab to support:

Ideation: Brainstormed key questions and hypotheses to explore (e.g., “What factors might influence salary the most?”)

Design Thinking: Structured the flow of visualisations to match business goals and user needs.

Code Optimisation: Improved Python and SQL code efficiency for data cleaning, analysis, and visualisation (e.g., reducing loops, optimising queries).

## Ethical considerations

* Were there any data privacy, bias or fairness issues with the data?
There were no employee personal identifiable information 


## Dashboard Design

I used Tableau for my dashboarding design
-Contents: 

Page 1: Comparative Analysis
Page 2: Salary Distribution
Page 3: Salary by company size
Page 4: Remote work by job titles

Visualisations used: Bar charts, Box plots, Stacked bar

* Later, during the project development, you may revisit your dashboard plan to update a given feature (for example, at the beginning of the project you were confident you would use a given plot to display an insight but subsequently you used another plot type).
* How were data insights communicated to technical and non-technical audiences?
* Explain how the dashboard was designed to communicate complex data insights to different audiences. 

## Unfixed Bugs
* Please mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a significant variable to consider, paucity of time and difficulty understanding implementation are not valid reasons to leave bugs unfixed.
* Did you recognise gaps in your knowledge, and how did you address them?
* If applicable, include evidence of feedback received (from peers or instructors) and how it improved your approach or understanding.

## Development Roadmap
* What challenges did you face, and what strategies were used to overcome these challenges?
* What new skills or tools do you plan to learn next based on your project experience? 



## Main Data Analysis Libraries
* Here you should list the libraries you used in the project and provide an example(s) of how you used these libraries.


## Credits 

Dataset: Kaggle - Data Science Salaries 2023
I used ChatGpt and GoogleColab to help me with coding, ideation and troubleshooting

* In this section, you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 
* You can break the credits section up into Content and Media, depending on what you have included in your project. 

## Conclusion 
* This is a data analysis of my Data_Science_Salaries_2023 project using a mix of EDA data analysis, visualisations, machine learning, hypothesis testing and dashboarding tools Tableau