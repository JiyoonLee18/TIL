# Average Population

- 날짜: 2023.04.05
- 문제: [https://www.hackerrank.com/challenges/average-population/problem?isFullScreen=true](https://www.hackerrank.com/challenges/average-population/problem?isFullScreen=true)

### 문제

Query the average population for all cities in **CITY**, rounded *down* to the nearest integer.

**Input Format**

The **CITY** table is described as follows:

![https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg](https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg)

### 답

```sql
SELECT  ROUND(AVG(POPULATION),0)
  FROM  CITY;
```

### 결과

```
# result
454250
```