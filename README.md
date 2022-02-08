# School District Analysis

## Overview

Prepare all standardized test data for analysis, reporting and present data to provide insights about performance trends and patterns on the School District. 

Based on the information about Schools Funding and Student Standardized Test Scores we’ll help the board to make decisions regarding future budget approvals and priorities. 

## Results

We used the Python library Pandas for data manipulation and analysis of the School District's records.
We focused first on Thomas High School grades which showed evidence of academic dishonesty. Where we used the Pandas NumPy module to change the reading and math scores to NaN:

<img width="637" alt="9thgradescores" src="https://user-images.githubusercontent.com/90527212/152932696-13571316-47e0-4c5e-89a6-4139085cdb2b.png">

Then we prepared the data to run an analysis on the entire School District. First gettering basic status information of the School District results:

<img width="940" alt="Summary" src="https://user-images.githubusercontent.com/90527212/152933440-72311192-72d9-4fba-89bc-6c323a5e9a19.png">

Then analyzing the Schools in different categories; by Name, by Spending, by Size and by Type, f.e:

<img width="755" alt="Spending" src="https://user-images.githubusercontent.com/90527212/152933829-3008cda3-f2ff-4c2a-a563-df1a409718a3.png">

## Summary

Finally, we discovered that replacing the 9th graders results, overall, did not affect drastically the Analysis. The scores slightly dropped but in general the change is subtle. 
But in particular cases, such as the Thomas High School, it did represent an important change which even affected them not qualifying ti the top District Schools.
