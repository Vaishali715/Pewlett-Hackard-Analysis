# Pewlett-Hackard-Analysis

## Overview of the analysis
This analysis is used to determine the number of retiring employees, their titles and how many employees are eligible to participate in the mentorship program.
First we queried our database to retrieve data and create a new table "Retirement_titles" where we got employees who are born between January 1, 1952 and December 31, 1955.
Next, we created a "unique_titles" table to find the first occurance of the employee number by using the DISTINCT ON function and then we did ORDER BY COUNT to show the total number of each "title" from unique_titles table that we created.

## Results

* The retirement_titles table shows all the eligible employees and how long they worked at each position over the course of their career.

* The unique_titles table shows the most recent titles for employees of retirement age.

* The retiring_titles shows the majority of the employees of retirement age (57,668/90,398 = 64%) have Senior titles.

(Image)

*The mentorship_eligibility shows that most of the employees have "Senior" titles.

Image


## Summary

* 90,398 roles will have to be filled as the "silver tsunami" begins to make an impact.

* There are 57,668 Senior staff employees eligible for mentorship and might be qualified enough but there is always a gap between the two generations whatever the comparison is between. For example; if we consider the technology, young generation is always more technology savvy and hence ahead as compared to the seniors. On the other hand, seniors always have a vast knowledge based on their experience. All this can help to mentor the next generation of Pewlett Hackard Employees.