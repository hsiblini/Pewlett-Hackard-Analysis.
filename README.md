# Pewlett-Hackard-Analysis.
## OVERVIEW
The purpose of this challenge is to determine the count of each retiring position, as well as determine the count of mentorship eligibility within the employees at Pewlett Hackard.

## RESULTS 
The following are the results of the analyses

### RETIREMENT AGES
For purposes of this report, the retirement age includes all employees born between 1952 and 1955. These employees might have held multiple positions over their employment so it is important to ensure no duplicates. We use the employee number to make sure we consolidate instances where the same employee held more than one position. We also make sure to use their current title in our analysis. 

![retiring_titles]("resources/retiring_titles.png")

### RETIRING TITLES
Once we create a list of all retiring employees, we use this list to group all employees by their current title, and we get a count of each title to determine how many employees are retiring from each title in the company. 

![unique_titles]("resources/unique_titles.png")

### MENTORSHIP AVAILABILITY
Mentorship availability includes all employees born in the year 1965. We collect these employees numbers, names, and employment dates. 

### MENTORSHIP ELIGIBILE EMPLOYEES
Upon determining which employees are eligible for mentorship programs, we create a list.

![mentorship]("resources/mentorship.png")

## SUMMARY
It seems like there is a very large number of employees retiring, with over 90,000 employees. The mentorship eligible employees are much less than that, which could prove to be a problem in the future. A lot of hiring will need to happen.
