# Data-Science-Assessment
Project uses ABC company’s dataset (458 rows, 9 columns) to clean and analyze employee details. After correcting the height column with random values between 150–180, tasks include team distribution, positions, age groups, salary expenditure, and age–salary correlation, with insights presented through visualizations.

As a culminating project, you'll be working with a dataset from ABC company, consisting of 458 rows and 9 columns. The company requires a comprehensive report detailing information about their employees across various teams. Your tasks include preprocessing the dataset, analyzing the data, and presenting your findings graphically. 
Here's a breakdown of what you need to do: 
Preprocessing: 
● Correct the data in the "height" column by replacing it with random numbers between 150 and 180. Ensure data consistency and integrity before proceeding with analysis. 
Analysis Tasks: 
● Determine the distribution of employees across each team and calculate the percentage split relative to the total number of employees.● Segregate employees based on their positions within the company.
● Identify the predominant age group among employees.
● Discover which team and position have the highest salary expenditure.
● Investigate if there's any correlation between age and salary, and represent it visually. 
Graphical Representation: 
● For each of the five analysis tasks above, create appropriate visualizations to present your findings effectively.
Data Story: 
● Provide insights gained from the analysis, highlighting key trends, patterns, and correlations within the dataset.


Project Overview: ABC Company Employee Data Analysis

This project involves the analysis of employee data from 'ABC Company'. The analysis aims to understand various aspects of the employee base, including team distribution, age demographics, positional breakdown, salary expenditure, and the correlation between age and salary.

 Steps

1.  Data Loading: The initial dataset was loaded from an Excel file named 'ABC Company.xlsx' into  pandas DataFrame.
2.  Feature Engineering: A new column named 'height' was artificially generated using random integers between 150 and 180 to simulate employee heights.
3.  Categorical Binning: The 'Age' column was categorized into 'age_group' bins (20-29, 30-39, 40-49, 50-59) for demographic analysis.

Analysis Tasks & Graphical Representations

 1.Determine the distribution of employees across each team and calculate the percentage split relative to the total number of employees.
Analysis: Calculated the count and percentage of employees for each team.
Visualization: A bar graph showing the number of employees per team and a pie chart illustrating the percentage split of employees by team.
Insight: The New Orleans Pelicans have the highest number of employees (19), while the Orlando Magic and Minnesota Timberwolves have the lowest (14 each). Most other teams have approximately 15-16 employees.

2. Segregate employees based on their positions within the company.
Analysis: Counted the number of employees holding each position.
Visualization: A bar chart illustrating the distribution of employees across different positions (e.g., PG, SF, C).
Insights: 'Employees by Position', showed the distribution of employees across different positions. It revealed that 'SG' has the highest number of employees (102), followed by 'PF' with 100 employees. 'PG' has 92, 'SF' has 85, and 'C' has the least with 79 employees. This indicates a relatively balanced distribution, with a slight concentration in guard and forward positions.

3. Identify the predominant age group among employees.
Analysis: Determined the distribution of employees across defined age groups.
Visualization: A bar plot displaying the count of employees in each age group.
Insights: 'Predominant Age Group of Employees', shows that the largest number of employees fall within the '20-29' age group, with 334 individuals. The next significant group is '30-39' with 119 employees. There are very few employees in the '40-49' age group (only 3), and no employees are observed in the '50-59' age group. This indicates that the workforce is predominantly young, with the vast majority of employees being under 40 years old.

4. Discover which team and position have the highest salary expenditure.
Analysis: Calculated the total salary expenditure by team and by position.
Visualization: Salary Expenditure by Team: The first bar graph visualizes the total salary expenditure for each team. The output explicitly states that the Cleveland Cavaliers have the highest salary expenditure, indicating they invest the most in player salaries among all teams. It is the tallest bar in the first plot.Salary Expenditure by Position: The second bar graph shows the total salary expenditure per player position. It highlights that the 'C' position has the highest total salary expenditure. This suggests that centers, on average or due to fewer highly paid individuals, command the highest total salaries across the league, followed by 'PG', 'PF', 'SF', and 'SG' in decreasing order of total salary expenditure.


5. Investigate if there's any correlation between age and salary, and represent it visually.
Analysis: Investigated the relationship between an employee's age and their salary.
Visualization: A scatter plot showing age versus salary, with a regression line to indicate the trend.
Insights: The correlation coefficient between Age and Salary is approximately 0.214, suggesting a weak positive linear relationship. Salaries generally rise as age increases, but the relationship is not very strong. Younger employees display a wide range of salaries, suggesting that age is only one of many factors influencing earnings. Some younger professionals earn exceptionally high salaries, while some older employees earn less than their peers.

Additional Information

The dataset appears to be representative of a ABC Company, with 'Team', 'Position', 'Age', 'Height', 'Weight', and 'Salary' being key attributes. The analysis provides a foundational understanding of the company's employee demographics and salary structure.




