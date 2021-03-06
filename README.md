# Pewlett Hackard Analysis

## Overview
#### The company Pewlett Hackard uses thousands of employees throughout their various departments. As such a large company, Pewlett Hackard acknowledges that many of its employees are likely retiring soon. In order to maintain a steady workflow, the human resources department has been tasked with analyzing the company’s data to find information about the employees retiring, the subsequent positions opening, and the mentoring possibilities for incoming staff. Several tables of data were collected to highlight these metrics and assist the various departments in strategizing for the future workforce.

## Resources Utilized
##### Data Source: departments.csv, dept_emp.csv, dept_manager.csv, employees.csv, salaries.csv, titles.csv
##### Software: PgAdmin 4; PostgreSQL 11; Visual Studio Code 1.65.0

## Results
•	Several employees within the company held multiples positions through their career with Pewlett Hackard, which might indicate both vertical and lateral mobility for other employees in the company to fill the retiring positions.

•	Despite the number of positions opening up, only 1,549 current employees are eligible for the mentorship program.

•	There are only 7 titles that the retiring employees have within Pewlett Hackard (see image below for reference). 

•	The majority of positions that will need to be filled are Senior Engineers and Senior Staff, which comprise almost 50,000 of the employees retiring.

![PHA](https://user-images.githubusercontent.com/99554642/161401598-ef37923e-52ec-4ab9-b9f3-6ea539d0e553.png)

## Summary
A total of 72,458 employees with be retiring in the near future from Pewlett Hackard, signifying over 72,000 positions that will need to be filled to maintain the current workflow of the company. As stated previously, only 1,549 employees are currently suited to participate in the mentorship program. Unless Pewlett Hackard changes the requirements for the mentorship program, there is an extreme lack of employees eligible to mentor the next generation of employees. To broaden the scope of the mentorship program, other factors could be considered to utilize other qualified employees such as experience, work performance, and title. As it stands, the only parameter examined for the mentorship program is age, which could be excluding a large number of valuable candidates.

The queries performed in this analysis only show a small insight into the retiring workforce of Pewlett Hackard. Another table that could assist the human resources department in filling the opening positions is a table of employees retiring by location or branch office. If positions are evenly spread through every location, the effect of the mass retirement would have less of an impact than if the positions were skewed to different locations. Another table that could further the analysis is a table constructed of employees in lower-level positions that could be promoted to the opening positions to evaluate for qualified internal candidates. To gain a better understanding, the human resources department will have to take a closer look at the different employee data of Pewlett Hackard.
