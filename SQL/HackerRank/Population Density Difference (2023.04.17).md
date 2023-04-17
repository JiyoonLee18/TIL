# Japan Population (1)

- 날짜: 2023.04.17
- 문제: [https://www.hackerrank.com/challenges/population-density-difference/problem?isFullScreen=true](https://www.hackerrank.com/challenges/population-density-difference/problem?isFullScreen=true)

### 문제

Query the difference between the maximum and minimum populations in **CITY.**

**Input Format**

The **CITY** table is described as follows:

![https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg](https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg)

### 답

```sql
SELECT  MAX(POPULATION)-MIN(POPULATION)
  FROM  CITY;
```

### 결과

```
# result
4695354
```