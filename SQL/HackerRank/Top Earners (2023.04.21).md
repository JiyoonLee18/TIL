# Top Earners

- 날짜: 2023.04.21
- 문제: [https://www.hackerrank.com/challenges/earnings-of-employees/problem?isFullScreen=true](https://www.hackerrank.com/challenges/earnings-of-employees/problem?isFullScreen=true)

### 문제

We define an employee's *total earnings* to be their monthly  worked, and the *maximum total earnings* to be the maximum total earnings for any employee in the **Employee** table. Write a query to find the *maximum total earnings* for all employees as well as the total number of employees who have maximum total earnings. Then print these values as  space-separated integers.

**Input Format**

The **Employee** table containing employee data for a company is described as follows:

![https://s3.amazonaws.com/hr-challenge-images/19629/1458557872-4396838885-ScreenShot2016-03-21at4.27.13PM.png](https://s3.amazonaws.com/hr-challenge-images/19629/1458557872-4396838885-ScreenShot2016-03-21at4.27.13PM.png)

where *employee_id* is an employee's ID number, *name* is their name, *months* is the total number of months they've been working for the company, and *salary* is the their monthly salary.

### 답

```sql
SELECT  SALARY*MONTHS, COUNT(*)
  FROM  EMPLOYEE
 GROUP  BY 1
 ORDER  BY 1 DESC
 LIMIT  1 
;
```

### 결과

```
# result
108064 7
```