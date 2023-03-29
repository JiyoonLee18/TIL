# Employee Names

- 날짜: 2023.03.29
- 문제: [https://www.hackerrank.com/challenges/name-of-employees/problem?isFullScreen=true](https://www.hackerrank.com/challenges/name-of-employees/problem?isFullScreen=true)

### 문제

Write a query that prints a list of employee names (i.e.: the *name* attribute) from the **Employee** table in alphabetical order.

**Input Format**

The **Employee** table containing employee data for a company is described as follows:

![https://s3.amazonaws.com/hr-challenge-images/19629/1458557872-4396838885-ScreenShot2016-03-21at4.27.13PM.png](https://s3.amazonaws.com/hr-challenge-images/19629/1458557872-4396838885-ScreenShot2016-03-21at4.27.13PM.png)

where *employee_id* is an employee's ID number, *name* is their name, *months* is the total number of months they've been working for the company, and *salary* is their monthly salary.

### 답

```sql
SELECT  NAME
  FROM  EMPLOYEE
 ORDER  BY NAME;
```

### 결과

```
# result
Alan 
Amy 
Andrew 
Andrew 
Angela
...
```