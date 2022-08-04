# Pewlett-Hackard-Analysis





## Challenge
This new assignment consists of two technical analysis deliverables and a written report. You will submit the following:

Deliverable 1: The Number of Retiring Employees by Title
Deliverable 2: The Employees Eligible for the Mentorship Program
Deliverable 3: A written report on the employee database analysis (README.md)

## Deliverable 1: The Number of Retiring Employees by Title (50 points)
### Deliverable 1 Instructions
Using the ERD you created in this module as a reference and your knowledge of SQL queries, create a Retirement Titles table that holds all the titles of employees who were born between January 1, 1952 and December 31, 1955. Because some employees may have multiple titles in the database—for example, due to promotions—you’ll need to use the DISTINCT ON statement to create a table that contains the most recent title of each employee. Then, use the COUNT() function to create a table that has the number of retirement-age employees by most recent job title. Finally, because we want to include only current employees in our analysis, be sure to exclude those employees who have already left the company.

#### Deliverable 1 Requirements
You will earn a perfect score for Deliverable 1 by completing all requirements below:

   - A query is written and executed to create a Retirement Titles table for employees who are born between January 1, 1952 and December 31, 1955. (10 pt)
   - The Retirement Titles table is exported as retirement_titles.csv. (5 pt)
   - A query is written and executed to create a Unique Titles table that contains the employee number, first and last name, and most recent title. (15 pt)
   - The Unique Titles table is exported as unique_titles.csv. (5 pt)
   - A query is written and executed to create a Retiring Titles table that contains the number of titles filled by employees who are retiring. (10 pt)
     - The Retiring Titles table is exported as retiring_titles.csv. (5 pt)
    
   ## Deliverable 2: The Employees Eligible for the Mentorship Program (30 points)
### Deliverable 2 Instructions
Using the ERD you created in this module as a reference and your knowledge of SQL queries, create a mentorship-eligibility table that holds the current employees who were born between January 1, 1965 and December 31, 1965.

### Deliverable 2 Requirements
You will earn a perfect score for Deliverable 2 by completing all requirements below:

   - A query is written and executed to create a Mentorship Eligibility table for current employees who were born between January 1, 1965 and December 31, 1965. (25 pt)
   - The Mentorship Eligibility table is exported and saved as mentorship_eligibilty.csv. (5 pt)

## Deliverable 3: A written report on the employee database analysis (20 points)
### Deliverable 3 Instructions
For this part of the Challenge, you’ll write a report to help the manager prepare for the upcoming "silver tsunami."

The analysis should contain the following:

  1. Overview of the analysis: Explain the purpose of this analysis.
  2. Results: Provide a bulleted list with four major points from the two analysis deliverables. Use images as support where needed.
  3. Summary: Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."
     - How many roles will need to be filled as the "silver tsunami" begins to make an impact?
     - Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

### Deliverable 3 Requirements
Structure, Organization, and Formatting (6 points)
The written analysis has the following structure, organization, and formatting:

   - There is a title, and there are multiple sections. (2 pt)
   - Each section has a heading and subheading. (2 pt)
   - Links to images are working and displayed correctly. (2 pt)
     
  #### Analysis (14 points)
The written analysis has the following:

1. Overview of the analysis:
        - The purpose of the new analysis is well defined. (3 pt)
2. Results:
        - There is a bulleted list with four major points from the two analysis deliverables. (6 pt)
3. Summary:
       - The summary addresses the two questions and contains two additional queries or tables that may provide more insight. (5 pt)
