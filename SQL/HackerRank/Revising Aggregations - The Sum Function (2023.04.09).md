# Revising Aggregations - The Sum Function

- 날짜: 2023.04.09
- 문제: [https://www.hackerrank.com/challenges/revising-aggregations-sum/problem?isFullScreen=true&h_r=next-challenge&h_v=zen](https://www.hackerrank.com/challenges/revising-aggregations-sum/problem?isFullScreen=true&h_r=next-challenge&h_v=zen)

### 문제

Query the total population of all cities in **CITY** where *District* is **California.**

**Input Format**

The **CITY** table is described as follows:

![https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg](https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg)

### 답

```sql
SELECT  SUM(POPULATION)
  FROM  CITY
 WHERE  DISTRICT='California';
```

### 결과

```
# result
339002
```