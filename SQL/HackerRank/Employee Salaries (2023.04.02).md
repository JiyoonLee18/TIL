# Employee Salaries

- 날짜: 2023.04.02
- 문제: [https://www.hackerrank.com/challenges/salary-of-employees/problem?isFullScreen=true](https://www.hackerrank.com/challenges/salary-of-employees/problem?isFullScreen=true)

### 문제

Write a query that prints a list of employee names (i.e.: the *name*  attribute) for employees in **Employee** having a salary greater than 2000$ per month who have been employees for less than 
10 months. Sort your result by ascending *employee_id*.

**Input Format**

The **Employee** table containing employee data for a company is described as follows:

![https://s3.amazonaws.com/hr-challenge-images/19629/1458557872-4396838885-ScreenShot2016-03-21at4.27.13PM.png](https://s3.amazonaws.com/hr-challenge-images/19629/1458557872-4396838885-ScreenShot2016-03-21at4.27.13PM.png)

where *employee_id* is an employee's ID number, *name* is their name, *months* is the total number of months they've been working for the company, and *salary* is their monthly salary.

### 답

```sql
SELECT  NAME
  FROM  EMPLOYEE
 WHERE  SALARY>2000 AND MONTHS<10
 ORDER  BY EMPLOYEE_ID;
```

### 결과

```
# result
Rose 
Patrick 
Lisa 
Amy 
Pamela
...
```