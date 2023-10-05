# Ex-No-5-Creating-Triggers-using-PL-SQL
# AIM: To create a Trigger using PL/SQL.
# Steps:

1.Create employee table with following attributes (empid NUMBER, empname VARCHAR(10), dept VARCHAR(10),salary NUMBER);

2.Create salary_log table with following attributes (log_id NUMBER GENERATED ALWAYS AS IDENTITY, empid NUMBER,empname VARCHAR(10),old_salary NUMBER,new_salary NUMBER,update_date DATE);

3.Create a trigger named as log_salary-update.

4.Inside the trigger block, Insert the values into the salary_log table whenever the salary is updated.

5.End the trigger.

6.Update the salary of an employee in employee table.

7.Whenever a salary is updated for the employee it must be logged into the salary_log table with old salary and new salary.

8.Display the employee table, salary_log table.

# Program:

![image](https://github.com/POKALAGURAVAIAH8121/Ex-No-5-Creating-Triggers-using-PL-SQL/assets/128034765/320d9e7f-c0cd-469e-adf8-f16479edf875)

# Create employee table
![image](https://github.com/POKALAGURAVAIAH8121/Ex-No-5-Creating-Triggers-using-PL-SQL/assets/128034765/da258159-43aa-430e-b9d2-32b77489abb0)
# Create salary_log table
![image](https://github.com/POKALAGURAVAIAH8121/Ex-No-5-Creating-Triggers-using-PL-SQL/assets/128034765/b12f8882-714c-40fb-9e0c-492d0ff80c14)
# PLSQL Trigger code
![image](https://github.com/POKALAGURAVAIAH8121/Ex-No-5-Creating-Triggers-using-PL-SQL/assets/128034765/16f0ab03-cf54-4677-bf64-0f2b4992fc0e)
# Output:
![image](https://github.com/POKALAGURAVAIAH8121/Ex-No-5-Creating-Triggers-using-PL-SQL/assets/128034765/912da7f0-6d58-4eca-a79f-fe1af32dfd19)
# Result:
The program has been implemented successfully
