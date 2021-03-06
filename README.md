# Pewlett-Hackard-Analysis

## Overview of the analysis:
PH is a large company with several thousand employees, and it’s been around for a long time. As baby-boomers begin to retire at a rapid rate, PH is looking towards the future in two ways: 1. it offers a retirement package for those who meet certain criteria; 2. it’s starting to think about which positions will need to be filled in a near future. The number of upcoming retirements will leave thousands of job openings. Bobby, an HR analyst, is tasked to perform employee research, specifically he needs to find answers to the following questions: 1. Who will be retiring in the next few years, and 2. how many positions PH will need to fill.
## Purpose:
This analysis will help future proof PH by generating a list of all employees eligible for the retirement package.
We need to help Bobby 
* build an Employee Data Base with SQL by applying our data modeling, engineering, and analysis skills;
* determine number of employees retiring per title so that the position can be filled soon;
* look into the current employees to determine if some of them qualify for a mentoring program.
## Results:
* We creates a [Retiring_Titles Table](https://github.com/Cryptotwister/Pewlett-Hackard-Analysis/blob/main/Data/retiring_titles.csv) to find the number of employees retiring within the certain positions, which we saved in CSV file attached.
* ![retiring_titles Table](https://user-images.githubusercontent.com/42978221/146704995-51139d0e-d166-4c76-975a-9b496cd7f576.png)

* [Mentorship Eligibility Table](https://github.com/Cryptotwister/Pewlett-Hackard-Analysis/blob/main/Data/mentorship_eligibilty.csv) also was created to hold the employees who are eligible to participate in a mentorship program.
* ![Mentorship_eligibility Table](https://user-images.githubusercontent.com/42978221/146705016-18cdc224-fdfa-4466-bd56-d4ff82bba88d.png)
## Summary:
By selecting a SUM of all retirees from Retiting Titles table we see that there are about 90000 people who are will be leaving the company soon:
![Roles_to_fill](https://user-images.githubusercontent.com/42978221/146706869-fa5bf7ce-f733-4b33-988c-568956b2c75a.png)

That is a very considerable amount of employees to retire.
From the Mentorship Eligibility table, we see that there are only 1549 employees who are eligible to participate in a mentorship program. That is a very small number of people to help the company replace those who are retiring.
To sum up, PH need to come up with a HR strategy to be able to overcome that "tsunami" coming.
It seems that PH will have to hire a lot of new employees for the vacant roles and develop a mentorship program in a way that current employees will by able to maybe assume multiple roles at the Company.
