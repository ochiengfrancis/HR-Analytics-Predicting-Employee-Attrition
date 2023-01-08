# HR-Analytics-Predicting-Employee-Attrition
Its important for companies to establish their employee attrition rates, BUT when most valuable employees start leaving the company, employers need to ask themselves what is the likely reason for this:
#### In this notebook, I look at a number of Hypothesis for important employees leaving their companies:
        i.	There is a significant Relationship between an Employees Salary and Employee Attrition Rate.
 ![image](https://user-images.githubusercontent.com/61507583/211185975-b3f6ba3a-44bf-42ec-abd9-063f81813ef3.png)
 
 
 In the graph Above(Salary Comparison)

* The management department has the highest difference between the salary of the employees who stayed and those that left.
* Its not possoble to see a huge difference in other departments.

        ii.	There is a significant Relationship between Safety of the company and employee Attrition Rate.
 ![image](https://user-images.githubusercontent.com/61507583/211186003-be4fb4f3-10a1-41e8-8725-c2e48ee8c019.png)

2169 -- Total Number of employees who had Work_accident

0.1446096406427095 --Percentage of employees who had a work accident

169 -- NUmber of employees who left and had a work-accident

About 14% of the employees had a work accident, although of the high number only of accidents only 169 employees data left the company had work a accident. Then this hypothesis is discarded.


        iii.There is a Significant Relationship between the perceived growth opportunities in a company and the Employee Attrition Rate.
 ![image](https://user-images.githubusercontent.com/61507583/211186096-06d215bb-bc3a-4d5d-a7aa-098d42ae901e.png)
 
Only 319 Employees have been prmoted, this is equal to only 2% of the employees in the company

In the last five years only 319 employees had promotion, this is equivalent to 2% of all employees. This may be a problem because if it is difficult to get promoted many employees become unmotivated and start looking for a new job.t the relationship between Satisfaction Level and Performance in a company and how does this influence the decision to leave the Company?

  #### How does the Years one has worked in a company influence their decision to leave the company? Or does it not?
![image](https://user-images.githubusercontent.com/61507583/211186214-a89026e7-e764-4b9c-86b4-2d7e73e20877.png)

*Employees with 7 or more years didn't leave, maybe because witht the passing of the years they are more comfortable and not so interested in looking for new challenges in other companies.

*The problem starts when the employees have more than 3 years and gets wors when they achieve 5 years.

*Its too early to say rhat the difficult to get promoted is the main reason for leaving the company,but more research is needed.

  #### What about the relationship between Satisfaction Level and Performance in a company and how does this influence the decision to leave the Company?
  ![image](https://user-images.githubusercontent.com/61507583/211186263-31b68396-0251-46d5-8f08-8b947437fa33.png)
  
          *poor_performance_left: 1531
          *poor_performance_stayed: 36


          *high_performance_left: 47
          *high_performance_stayed 889
  
  ![image](https://user-images.githubusercontent.com/61507583/211186273-87ba03db-bdcb-494b-a19b-33c64c8ee6eb.png)
  
      *It is possible to see that 98% of employees with few projects that left also have poor performance.

      *And 95% of the employees with 5 or more projects that left the company had the highest performance.

      *3 or 4 are the best number of projects.
      
 
 ![image](https://user-images.githubusercontent.com/61507583/211186341-ee254186-11a7-4210-9f39-49b7bbada9e4.png)

###### From the employees that left with high performance, 4 or more years in the company and working on 5 or more project had:

          1.Low satisfaction level,
          2.Worked more hours,
          3.Haven´t been promoted in the last five years.


![image](https://user-images.githubusercontent.com/61507583/211186381-195c3960-e7ac-4fff-98ac-3a94aaf37c76.png)


##### Summary of the Exploratory Data Analysis

      i.It is a relatively young company, on average, employees have 3 or 4 years in the company and the oldest employees are working 10 years.

      ii.The biggest difference in the salary from who stayed and those who left, was found in the managemnet department, in the other departments although the salaries of who stayed are higher in average, it is not a big difference.

      iii.The number of employees that had a work accident is about 14%, of which only 169 employees left the company, so doesn't seem to have a correlation with the employees leaving.

      iv. In five years only 2% of the employees were promoted. Is possible that many employees get unmotivated and start planning to leave.

      v. Employees with 7years or longer in the company didn't leave. Employees with less than 5 years have more chances are likely to leave.

      vi.There are 2 distincts groups of employees performance that left. A group with poor performance with 2 projects and others with high performance with 5 or more projects. It is not necessary to retain all the employees, the focus is on keeping employees with high performance.

      vii.The employees with 4 years in the company have the lowest average satisfaction level of all the company with (0.47).

      viii. The satisfaction drops when the employees are working in 5 or more projects. A number of 3 or 4 projects seems to be ideal independent of the time spend in the company.

      ix.The employees with 5 or more projects that left also worked at least 20% more hours than the average of the company.

      x.The satisfaction level of the employees that left is grouped in totally disappointed, below the average satisfaction and satisfied.
