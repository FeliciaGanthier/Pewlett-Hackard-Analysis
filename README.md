# Pewlett-Hackard-Analysis

##**Overview of Project**

Pewlett Hackard is a large, long-standing company with several thousand employees and is looking toward the future as Baby Boomers retire by offering retirement packages for employees meeting certain criteria and thinking about which positions need to be filled due to retirements.

Raw data from six CSV files, Entity Relationship Diagrams (ERDs), Postgres and PG Admin were used to perform the analysis and create the requested lists. 

A Git Hub repository was created for the analysis so Bobby, an HR Analyst, and his manager can review the most recent work.

***Purpose of Analysis***

To help future-proof the company, I am generating a list of all retirement eligible employees and building a database by applying data modeling, engineering and analysis skills for Bobby, an HR Analyst performing research to find out who will be retiring in the next few years and how many positions will need to be filled because of the “Silver Tsunami”. 

###**Results**

Modeling the data by creating a flow chart to navigate the relationships between the CSV files was done with an online tool called Quick Database Diagrams (Quick DBD).

![Employee DB Pic](https://github.com/FeliciaGanthier/Pewlett-Hackard-Analysis/blob/master/EmployeeDB.png)

Then statements using conditionals were created to perform queries to learn when employees were hired as well as their age to determine how many people will be retiring and which are eligible for a retirement package. According to Bobby’s supervisor, employees born between 1952-1955 will likely begin to retire. Our query returned 90,398 results. 

For deeper analysis, I refined the list by birth year and updated the query to include a hiring range from 1985-1988, which reduced the number of employees by 45%. 

Employees By Birth Year

•	1952 – 21,209

•	1953 – 22,857

•	1954 – 23,228

•	1955 – 23,104

*Note: This list was recreated to show current retirement eligible employees. This list returned 33,118 employees- roughly a third of the original query.*

A table called Retirement Info was created that can use statements and functions to perform analyses and exported as a CSV file for sharing.  I also created a separate list of employees for each department by joining tables using an outline mapped out in an ERD. 
Because of the number of people leaving each department, I created four more specific lists to share with department supervisors to begin their future-proofing prep. 

1.	Employee Info – Which prompted Bobby to ask about raises

2.	Management – To highlight training gaps to fill open roles

3.	Department Retirees- To scrub list for duplicate entries 

4.	Department Employees – Added by request

*Deeper Analysis*

Breakdown of Retirement Age Employees By Most Recent Job Title

![D1C](https://github.com/FeliciaGanthier/Pewlett-Hackard-Analysis/blob/master/D1%20C.png)

*Key Takeaways*

•	Retirement age employees holding lower level titles are rare. 

•	With more than half of the retirement age employees, Senior Engineers (33%) and Senior Staff (31%) positions should be highest priority for training and/or filling 

•	Departments can leverage the knowledge of the employees in Engineer (16%) and Staff (14%) roles to mentor younger team members. 

####**Summary**

Pewlett Hackard is set to lose over 30,000 employees to retirement over the next few years.  Most of the retiring employees are in senior positions so to address the knowledge gap and lessen the impact of the “Silver Tsunami”, the company should develop a mentorship program. A query found there are 1,550 employees eligible for such a program. 

While future proofing the company, PH should also review the criteria for raises as compensation coupled with professional development/advancement opportunities can help retain and recruit non-retirement age employees to fill the immense need. 
