MY FIRST OFFICIAL DATA ANALYTICS PROJECT

HR ANALYTICS: TALENT SOURCING AND RECRUITMENT STRATEGIES DATA ANALYSIS REPORT

MAIN OBJECTIVE:

The main objective of this project is to optimize talent sourcing and recruitment strategies by leveraging a data-driven approach. Through analysis of the Talent sourcing/HR dataset, the goal is to identify patterns, draw insights, and formulate informed recommendations that enhance the efficiency of candidate selection processes.

DATA OVERVIEW: 

For this particular project, the source of my data was from 10Alytics an Ed-Tech company dedicated to building data and tech consciousness by providing premium tech skills to Africans and people of the Black community. 

DATASET DETAILS:

Fields: Employee ID, Source of Hire, Date of Hire, Position/Role, Department, Performance Score, Number of Promotions, Tenure, Reason for Leaving, Training Programs Attended, Employee Satisfaction Score, Peer Review Score, Salary Bracket, Employee Referrals, Mentorship Participation, Educational Background, Alma Mater, Skills/Certifications, Previous Employer, Industry Experience.

DIMENSIONS: 20 columns, 1002 rows.

KEY QUESTIONS TO ANSWER

1. How has the organization's workforce evolved over the years?
2. What are the specific employee counts for each year from 2018 to 2023?
3. What is the distribution of employees across different experience levels?
4. How many entry-level, mid-level, management-level, and senior-level employees are there?
5. What is the most sought-after skill among top-performing employees?
6. How does the popularity of skills correlate with performance scores?
7. How has the promotion rate changed over the years (2018-2023)?
8. What is the average promotion rate during this period?
9. Which sourcing channel has the best-performing employees?
10. How does the performance score vary across different sourcing channels?
11. Is there a correlation between educational background and performance scores?
12. How do employees with different degrees and alma maters perform?
13. What is the overall average employee satisfaction score?
14. Which department has the highest average satisfaction score?
15. What percentage of employees report high satisfaction levels?
16. Do employees from specific previous employers demonstrate higher performance?


TOOLS USED: EXCEL AND TABLEAU (PRIMARILY TABLEAU)

APPROACH USED

DATA CLEANING AND PREPARATION: 

No duplicates were discovered after checking. The "Reason for Leaving" column was removed because it contained empty cells, making it useless.
I introduced a new column called "YEAR" to calculate the "average promotion rate" and the "employee promotion rate per year." I accomplished this by using the Excel function "=TEXT([@[Date of Hire]], "YYYY")" to extract the year from the "date of hire" column.


DATA ANALYSIS INSIGHTS

Workforce Growth Analysis:
The organization has a total of 1001 employees. 
	There were 25 employees in 2018.
	In 2019, 180 employees were hired, and the total number of employees was 205.
	In 2020, 247 employees were hired, and the total number of employees was 452.
	In 2021, 251 employees were hired, and the total number of employees was 703.
	In 2022, 168 employees were hired, and the total number of employees was 871.
	In 2023, 130 employees were hired, and the total number of employees was 1001.

Experience Level:
There are 367 entry-level employees, 389 Mid-level, 405 Management-level, and 391 senior-level employees.

Popular Skill: Agile is the most sought-after skill among top-performing employees with a performance score 10.

Promotion Trends:
27% (268) of employees were promoted three times, 27% (267) of employees were also promoted two times, 21% (214) of employees were promoted just once, while 25% (252) of employees did not receive any promotion. Notably, some employees with a performance score above 8 were not promoted.

Promotion Statistics:
Analyzed promotion statistics using Excel, including promotion rates from 2018 to 2023. 

Overall, there were 1552 promotions across all departments from (2018-2023), with only 749 employees being promoted so far. 
The formula I used for calculating the promotion rate is the Total number of promotions divided by the total number of employees in the organization during a given year multiplied by 100.
The promotion rate per year was as follows:
	The 2018 promotion rate was 168%, with 19 employees promoted out of 25 and 42 promotions.
	The 2019 promotion rate was 128%, with 130 employees promoted out of 205 and a total of 262 promotions.
	The 2020 promotion rate was 80%, with 172 employees promoted out of 452 and 363 promotions.
	The 2021 promotion rate was 55%, with 186 employees promoted out of 703 and 390 promotions.
	The 2022 promotion rate was 32%, with 132 employees promoted out of 871 and 281 promotions.
	The 2023 promotion rate was 21%, with 110 employees promoted out of 1001 and 214 promotions.

The Average Promotion Rate is 81%: Using the average function, I was able to determine the average promotion rate from 2018 to 2023.


EMPLOYEE SOURCING INSIGHTS

Best-performing Source: The best-performing employees were found through LinkedIn, with an average performance score of 7.8.

Educational Background:
Explored the correlation between educational background and performance scores.

Employees with both Bachelor's and Master's Degrees averaged a performance score of 6.9.
Employees from Oxford University had the best average performance score of 7.7.
Performance Score Range: The highest performance score was 10, and the lowest was 3.

EMPLOYEE SATISFACTION AND DEPARTMENTAL ANALYSIS 

The average employee satisfaction score is 7.5.
Departmental Analysis: The design department has the highest average satisfaction score of 7.8.
Satisfaction Levels: 67.6% (677) of employees report a satisfaction score of 7 or higher. 16.6% (167) of employees report a perfect satisfaction score of 10.
The majority of the workforce (19%) is sourced through "Campus Recruitment" channels.


PREVIOUS EMPLOYER INSIGHTS
Top Performers: Employees from Deloitte and Facebook, regardless of experience level, demonstrated high average performance scores (8.4 and 8.3), respectively.


RECOMMENDATIONS

In light of the extensive data analysis, here are refined and enhanced recommendations to optimize talent sourcing and recruitment strategies:

1. Performance recognition and compensation

-- Conduct an in-depth appraisal to identify high-performing employees who have not been promoted.
-- Implement a compensation strategy to recognize and reward these individuals for their outstanding contributions.
-- Utilise data insights to determine key performance indicators for each role.

Anticipated Outcomes:
Employees are more satisfied now.
Reduction in turnover rates.
Improved overall organizational efficiency.
Enhanced objectivity in promotion decisions.

2. Leadership Transparency and Recognition

-- Establish open communication channels between leadership and employees.
-- Recognise and celebrate high-performing individuals' accomplishments to foster a positive workplace culture.
-- Encourage collaboration, teamwork, and mutual support.

Anticipated Outcomes:
Increased belief in the company's culture.
Sustained positive workplace culture.

3. Strategic talent sourcing

-- Expand your talent sourcing beyond LinkedIn by exploring other channels such as industry-specific job boards, professional organizations, and targeted events.
-- Make a concerted effort to source employees via LinkedIn, particularly for the Data Team and Operations departments. Take advantage of the proven high-performance scores (8.3 and 7.8) of current employees in these departments.
-- Use data analytics to determine the most efficient sourcing channels for each department.

Anticipated Outcomes:
Access to a database of qualified candidates with a proven track record of success.
Increased diversity in the candidate pool.
Access to a broader set of skills.

4. Educational Partnerships for Targeted Hires

-- To attract top talent, strengthen current partnerships with prestigious institutions such as Oxford University.
-- Collaborate with educational partners to create programs that meet the organization's skill requirements.
-- Make use of alumni networks to find potential recruits.

Anticipated Outcomes:
Access to a pipeline of skilled candidates.
Enhanced employer brand through academic partnerships.

5. Agile Skill Development

-- Prioritise the identification and recruitment of prospective Agile employees.
-- Start Agile training programs for current employees to provide opportunities for personal development.

Anticipated Outcomes:
Strengthened skillsets aligned with industry trends.
Enhanced project adaptability and efficiency.

LINK TO DASHBOARDS: http://tinyurl.com/HR-Analytics-Talent


