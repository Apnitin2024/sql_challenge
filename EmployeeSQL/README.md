**Data Analysis:**
The queries to get answers to the data analysis lists are found in data analysis.sql

Number of results for each query

300,024
36,150
24
331,603
20
52,245
137,952
1,638

**Data Engineering:**
The schemas for creating the six tables in the data base can be found in data engineering.sql.

dept_no and title_id/emp_title_id and sex are VARCHARs because they have a fixed length.
All other strings are TEXT because they could have a variable length.
first_name, last_name, could potentially be NULL as there is no guarantee that a person has a name1. However, for this data set, I will be using NOT NULL.
