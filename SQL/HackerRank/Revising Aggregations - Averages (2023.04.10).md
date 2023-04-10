# Revising Aggregations - Averages

- 날짜: 2023.04.10
- 문제: [https://www.hackerrank.com/challenges/revising-aggregations-the-average-function/problem?isFullScreen=true](https://www.hackerrank.com/challenges/revising-aggregations-the-average-function/problem?isFullScreen=true)

### 문제

Query the average population of all cities in **CITY** where *District* is **California**.

**Input Format**

The **CITY** table is described as follows:

![https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg](https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg)

### 답

```sql
SELECT  AVG(POPULATION)
  FROM  CITY
 WHERE  DISTRICT='California';
```

### 결과

```
# result
113000.6667
```