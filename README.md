# Big Data Lab Assignment

In the previous 3 labs, you were asked to practice the ETL process learned from Chapter 2 of the recommended textbook “Data science on Google Cloud Platform”, during the labs part of the exercise is to gather UL timetables in the Spring semester per course per year.

This lab will be based on the BigQuery data you gathered in the previous lab exercises.

In this lab, you will be given a list of tasks, for each of the task you will need to:
- design a query to gather the information

- based on the visualization concept you learned from week 8 and week 9, choose the right chart type to visualize the data. (Note that you can use any tools you want, Excel, Google Data studio, gnuplot, etc.)

- By end of next week, Week10, please email your result in pdf to the lecturer.


## Tasks
In the following tasks we want to understand how are the classes being scheduled among each group of the students (students are grouped per course and year , e..g., students doing Master in Software Engineering is one group of students, and 4th year students doing Computer Systems is another group of students).
- Find out the daily course distribution for the second week (week 2). To be more specific, you should count how many groups of students are having classes on Monday, Tuesday, and so on.

- Find out the group hourly course distribution for Tuesday of the second week (week 2). Note that the time interval is per hour, if for a given group there is a class module spread over more than 1 hour (say 11:00 - 13:00), you will need to count the group in both  of the two time intervals(11:00 - 12:00, 12:00 - 13:00).

- In question 2, for each time interval, you count any group of students that are having class during the interval. Now in this question, for each of the intervals, you count a group of the students only if the class during it is the last class they are having for that day.