# SQL_Problems
Welcome to the Database world . I am trying to solve SQL problems which will clear the concepts more and more! Let's Go!!! 


1.	How to find duplicate value in table
Ans:  select emp.id,count(1) from Employee 
          group by emp.id 
         having count(1) > 1;
