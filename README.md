# Pewlett-Hackard-Analysis

## Overview

Pewlett-Hackard is a large company, with thousands of employees. As baby boomers begin to retire Pewlett-Hackard needs to know who is retiring, how many are retiring, and from what departments they are retiring. A large wave of retirements has the potential to leave a company in an uncompetitive position if handled incorrectly. The purpose of this analysis is to help future-proof Pewlett-Hackard and allow the company to properly prepare for the upcoming vacancies. The following analysis was performed in conjunction with Pewlett-Hackard human resources department as part of the employee research effort.

## Results

A significant part of the retirement analysis is a request to determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. This information will be used by stake holders within Pewlett-Hackard to help smooth the transition within the company's workforce. The following bulleted list highlights four of the major findings from the analysis. Detail of the code used for the analysis can be found 
![here.](/Queries/Employee_Database_challenge.sql)

* Finding 1

![retiring_titles](/Queries/retiring_titles.png)

The number of employees that are likely to retire is significant, especially in the senior roles. The senior engineers and senior staff positions are large contributors to the company, and also have the largest counts in likely retirements. These two roles should be prioritiezed in vacancy mitigation.   

* Finding 2

![retiring_titles1](/Queries/retiring_titles1.png)

Only two managers were found to be in the likely to retire category. This raises a flag to look further into how the data was gathered. Management is typically a more senior role and to only have two retiring requires further questioning. Do most managers not have "Manager" in their titles? If the titles do not include the word manager, but the role does require leading others, how can we target these individuals? Are the managers actually younger than many of the engineers and staffers? If so, maybe a bigger question needs to be asked about company culture and why our senior members are not advancing to management roles? This is possibly a significant finding and requires more investigation.

* Finding 3

![mentorship_eligibility](/Queries/mentorship_eligibility.png)

A list was created to target employees who could participate in a mentorship program. These individuals are from various departments within the company. This list can be given to managers to see if the candidates would like to participate in the program. These individuals have some experience but are not as likely to retire as soon as the majority of the baby boomers. 


* Finding 4

![mentorship_eligibility1](/Queries/mentorship_eligibility1.png)

With the current conditions used to define elegibility in the mentorship program, there are 1,549 individuals targeted. This is not enough to fill the potential vacancies. The conditionts to select individuals for the program needs to be expanded.

## Summary

![retirement_count](/Queries/retirement_count.png)

All in all, with 90,398 potential retirements in the near future Pewlett-Hackard needs to start preparing. The senior engineer and senior staff positions need to take priority, with the majority of potenital vacancies happening in these two titles. The mentorship program needs to be extended by a large amount to make sure there are enough qualified employees in the next generation. There is a lot of valuble knowledge and experience that is likely to leave in the near future. It is critical that there is a well designed system to transfer as much knowledge as possible, from senior to junior employees, to mitigate the risk to Pewlett-Hackard. 


