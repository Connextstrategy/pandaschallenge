# Rutgers Bootcamp Challenge - Pandas Challenge

In this assignment, you’ll create and manipulate Pandas DataFrames to analyze school and standardized test data.

# Description

I'm the new Chief Data Scientist for my city's school district. In this capacity, I'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, I've been asked to analyze the district-wide standardized test results. I'll be given access to every student's math and reading scores, as well as various information on the schools they attend. My task is to aggregate the data to showcase obvious trends in school performance.

# pycityschool

Using Pandas and Jupyter Notebook, create a report that includes the following data. Your report must include a written description of at least two observable trends based on the data.

Hint: Check out the sample solution called PyCitySchools_starter.ipynb located in the .zip file to review the desired format for this assignment.

## District Summary

Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame.

Include the following:

* Total number of unique schools

* Total students

* Total budget

* Average math score

* Average reading score

* % passing math (the percentage of students who passed math)

* % passing reading (the percentage of students who passed reading)

* % overall passing (the percentage of students who passed math AND reading)

## School Summary
Perform the necessary calculations and then create a DataFrame that summarizes key metrics about each school.

Include the following:

* School name

* School type

* Total students

* Total school budget

* Per student budget

* Average math score

* Average reading score

* % passing math (the percentage of students who passed math)

* % passing reading (the percentage of students who passed reading)

* % overall passing (the percentage of students who passed math AND reading)

## Highest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in descending order and display the top 5 rows.

Save the results in a DataFrame called "top_schools".

## Lowest-Performing Schools (by % Overall Passing)

Sort the schools by % Overall Passing in ascending order and display the top 5 rows.

Save the results in a DataFrame called "bottom_schools".

## Math Scores by Grade
Perform the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

## Reading Scores by Grade
Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

## Scores by School Spending
Create a table that breaks down school performance based on average spending ranges (per student).

Use the code provided below to create four bins with reasonable cutoff values to group school spending.

Use pd.cut on the "Total Students" column of the per_school_summary DataFrame.

Create a DataFrame called size_summary that breaks down school performance based on school size (small, medium, or large).

## Scores by School Type
Use the per_school_summary DataFrame from the previous step to create a new DataFrame called type_summary.

This new DataFrame should show school performance based on the "School Type".

# Dependencies

* Must have Anacondas installed installed to use Jupyter Notebooks

* Can use have Visual Studio Code to check code 

# Installing

* Use Resources files to use code 
* No modifications needed to be made to files/folders

# Help

No issues as it runs well on Microsoft Excel. Do recommend erasing the updated data to check the code every time. 

# Authors

Christopher Manfredi 

## Version History

    * Initial Release
