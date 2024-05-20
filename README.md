# EDA on ABC company
Introduction
This project analyzes a dataset of basketball players, including information on their names, teams, numbers, positions, ages, heights, weights, colleges, and salaries. The goal is to preprocess the data, perform various analyses, visualize the results, and derive meaningful insights.

Preprocessing Steps
Initial Data Inspection
We first examined the dataset to understand its structure, including the number of columns, data types, and presence of missing values. The dataset has the following columns: Name, Team, Number, Position, Age, Height, Weight, College, Salary, AgeGroup, and Age_Group.

Missing Values Check
We determined the non-null count for each column to identify where data is missing.

Null Values Check
We identified columns with missing values, focusing on 'College' and 'Salary'.

Duplicate Values Check
We ensured there were no duplicate rows in the dataset.

Data Correction
We corrected the 'Height' column by replacing its values with random numbers between 150 and 180 cm to ensure data consistency.

Basic Summary of Numeric Columns
We computed mean, standard deviation, quartiles, and other statistics for numerical columns.

Data Insights
Salary Distribution
The histogram of salaries reveals a left-skewed distribution, indicating that most players earn lower salaries, with a few earning significantly higher salaries, creating a long tail on the right side.

Team Analysis
New Orleans Pelicans have the largest number of players, suggesting a robust and versatile roster.
Orlando Magic has the fewest players, indicating a more streamlined team or potential challenges in recruitment.
These disparities can influence gameplay dynamics, rotation strategies, and overall competitiveness within the league.
Team Size Relative to Total Players
New Orleans Pelicans constitute 4.15% of the total player count, reflecting a significant presence.
Minnesota Timberwolves represent 3.06%, indicating a slightly smaller share.
These percentages offer insights into team distribution and competitive balance within the league.
Position Distribution
Point Guards (92 players) lead the offense, focusing on playmaking.
Shooting Guards (102 players) prioritize scoring, often from long-range.
Power Forwards (100 players) excel in rebounding and inside scoring.
Small Forwards (85 players) balance scoring and defensive versatility.
Centers (79 players) anchor defense and excel in rebounding and rim protection.
This distribution reflects teams' strategic needs and player strengths, influencing game tactics and lineup formations.
Age Group Distribution
20-29 years: The largest group with 334 players, indicating a young and energetic player base.
30-39 years: 119 players, representing experienced athletes contributing leadership and seasoned skills.
40-49 years: Only 3 players, showing the rarity of older players continuing their careers.
This distribution highlights the diversity in player demographics and the varying contributions across different age brackets.
Salary Expenditure
Cleveland Cavaliers have the highest salary expenditure, reflecting significant investment in their roster.
Centers (C) command the highest salary expenditure, suggesting teams prioritize investing in dominant players for key roles like rebounding, defense, and scoring in the paint.
These trends show how financial resources are allocated to secure top talent and build competitive teams.
Correlation Analysis
The correlation between age and salary is 0.214, indicating a weak but positive relationship.
This suggests that, on average, older players tend to earn slightly higher salaries, likely due to experience, skill level, and market demand.
Understanding this correlation helps teams and players gauge salary expectations and career trajectories, aiding in contract negotiations and roster planning.
Conclusion
The analysis of the basketball players' dataset provides valuable insights into player demographics, team dynamics, and financial investments. Preprocessing steps ensured data integrity, while analyses unveiled patterns and correlations. The salary distribution highlights income disparities within the league. Team analysis reveals the impact of roster composition on gameplay and competitiveness. Position and age group distributions illustrate the diverse skills and contributions players bring to the court. The correlation between age and salary reflects the nuanced dynamics in player compensation. Overall, these insights are crucial for roster management, recruitment strategies, and financial planning in professional basketball.








