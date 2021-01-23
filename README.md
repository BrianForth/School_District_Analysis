# School_District_Analysis
Analysis of the standardized testing scores of the high schools in a municipal school district

## Project Overview
An employee of the school district, Maria, requested an analysis be performed of the standardized testing scores for math and reading in the district's high schools. To work within the team, Anaconda was used to create a Development Environment with Python 3.7.9 and Jupyter Notebook. The analysis was pushed to a GitHub Repository, which this file describes.

## Resources
- Data Source: students_complete.csv, schools_complete.csv
- Software: Anaconda, Python 3.7.9, Jupyter Notebook

## Overview
The district comprises 15 high schools with a total of 39,170 students between them. The testing data in the csv files were placed into Pandas DataFrames to facilitate analysis while maintaining confidentiality of the students.

![District_Summary](resources/District_Summary.jpg)

## Results

  
## Challenge Overview
For the challenge, in addition to the 5 tasks defined above, the following tasks were given:

6. Get a complete list of counties reporting votes for this election.
7. Calculate the total number of votes each county reported.
8. Calculate the percentage of total votes reported from each county.
9. Determine the county the reported the most votes.

## Challenge Results
The challenge analysis further shows that:

- The counties reporting votes for this election were:
  - Jefferson
  - Denver
  - Arapahoe
- The counties reported each reported the following number of votes:
  - Jefferson County reported 10.5% of the vote and 38,855 votes.
  - Denver County reported 82.8% of the vote and 306,055 votes.
  - Arapahoe County reported 6.7% of the vote and 24,801 votes.
- The county reporting the greatest number of votes this election is:
  - Denver County, which reported 82.8% of the vote and 306,055 votes.
  
## Challenge Summary
As written, this script can analyze any single-vote election with data submitted in a .csv file with county data in the second column and vote selection in the third column.
Should the data not conform to these specifics, minor changes in lines 41 and/or 42 can track data in columns other than the second and third. If data were submitted, for instance with precinct or ward numbers, that information could also be analyzed if it is in the second or third columns, but best practices would advise to change variable names and the f-strings in lines 55-58, 78-82, 89-90, and 111-115 to be appropriate to the information tracked. 

Should more than two columns be analyzed, lines 54-85 could be copied en masse and pasted with changes to variable names and hardcoded outputs to match the categories analyzed. If more iterations are to be created, though, more variables should be established with those in lines 18-30, and those lists need to be populated as the current lists are in lines 44-50.

Alternatively, the script could be changed to print out headers for a .csv, and request user input on which field(s) to analyze, but that would require significant changes to the code.
